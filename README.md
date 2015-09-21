# Fucking Awesome Python

A curated list with Github stars and forks stats based on awesome [awesome-python](https://github.com/vinta/awesome-python), inspired by [fucking-awesome-go](https://github.com/hvnsweeting/fucking-awesome-go)

# Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Python frameworks, libraries and software. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

- [Awesome Python](#awesome-python)
    - [Environment Management](#environment-management)
    - [Package Management](#package-management)
    - [Package Repositories](#package-repositories)
    - [Distribution](#distribution)
    - [Build Tools](#build-tools)
    - [Interactive Interpreter](#interactive-interpreter)
    - [Files](#files)
    - [Date and Time](#date-and-time)
    - [Text Processing](#text-processing)
    - [Specific Formats Processing](#specific-formats-processing)
    - [Natural Language Processing](#natural-language-processing)
    - [Documentation](#documentation)
    - [Configuration](#configuration)
    - [Command-line Tools](#command-line-tools)
    - [Downloader](#downloader)
    - [Imagery](#imagery)
    - [OCR](#ocr)
    - [Audio](#audio)
    - [Video](#video)
    - [Geolocation](#geolocation)
    - [HTTP](#http)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [ORM](#orm)
    - [Web Frameworks](#web-frameworks)
    - [Permissions](#permissions)
    - [CMS](#cms)
    - [E-commerce](#e-commerce)
    - [RESTful API](#restful-api)
    - [Authentication](#authentication)
    - [Template Engine](#template-engine)
    - [Queue](#queue)
    - [Search](#search)
    - [News Feed](#news-feed)
    - [Asset Management](#asset-management)
    - [Caching](#caching)
    - [Email](#email)
    - [Internationalization](#internationalization)
    - [URL Manipulation](#url-manipulation)
    - [HTML Manipulation](#html-manipulation)
    - [Web Crawling](#web-crawling)
    - [Web Content Extracting](#web-content-extracting)
    - [Forms](#forms)
    - [Data Validation](#data-validation)
    - [Anti-spam](#anti-spam)
    - [Tagging](#tagging)
    - [Admin Panels](#admin-panels)
    - [Static Site Generator](#static-site-generator)
    - [Processes](#processes)
    - [Concurrency and Parallelism](#concurrency-and-parallelism)
    - [Networking](#networking)
    - [WebSocket](#websocket)
    - [WSGI Servers](#wsgi-servers)
    - [RPC Servers](#rpc-servers)
    - [Cryptography](#cryptography)
    - [GUI](#gui)
    - [Game Development](#game-development)
    - [Logging](#logging)
    - [Testing](#testing)
    - [Code Analysis and Linter](#code-analysis-and-linter)
    - [Debugging Tools](#debugging-tools)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Data Visualization](#data-visualization)
    - [Computer Vision](#computer-vision)
    - [Machine Learning](#machine-learning)
    - [Functional Programming](#functional-programming)
    - [MapReduce](#mapreduce)
    - [Third-party APIs](#third-party-apis)
    - [DevOps Tools](#devops-tools)
    - [Job Scheduler](#job-scheduler)
    - [Foreign Function Interface](#foreign-function-interface)
    - [High Performance](#high-performance)
    - [Network Virtualization and SDN](#network-virtualization-and-sdn)
    - [Hardware](#hardware)
    - [Compatibility](#compatibility)
    - [Miscellaneous](#miscellaneous)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [Editor Plugins](#editor-plugins)
    - [IDEs](#ides)
- [Services](#services)
    - [Continuous Integration](#continuous-integration)
    - [Code Quality](#code-quality)
- [Resources](#resources)
    - [Websites](#websites)
    - [Weekly](#weekly)
    - [Twitter](#twitter)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

- - -

## Environment Management

*Libraries for Python version and environment management.*

* [:octocat: p](https://github.com/qw3rtman/p) - Dead simple interactive Python version management. :star: 480 :fork_and_knife: 13
* [:octocat: pyenv](https://github.com/yyuu/pyenv) - Simple Python version management. :star: 3080 :fork_and_knife: 219
* [:earth_americas: PyRun](https://www.egenix.com/products/python/PyRun/) - A one-file, no-installation-needed version of Python.
* [:octocat: Vex](https://github.com/sashahart/vex) - Run a command in the named virtualenv. :star: 253 :fork_and_knife: 14
* [:earth_americas: virtualenv](https://pypi.python.org/pypi/virtualenv) - A tool to create isolated Python environments.
* [:earth_americas: virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) - A set of extensions to virtualenv.

## Package Management

*Libraries for package and dependency management.*

* [:earth_americas: pip](https://pip.pypa.io/) - The Python package and dependency manager.
    * [:earth_americas: Python Package Index](https://pypi.python.org/pypi)
* [:octocat: conda](https://github.com/conda/conda/) - Cross-platform, Python-agnostic binary package manager. :star: 461 :fork_and_knife: 149
* [:earth_americas: Curdling](http://clarete.li/curdling/) - Curdling is a command line tool for managing Python packages.
* [:earth_americas: wheel](http://pythonwheels.com/) - The new standard of Python distribution and are intended to replace eggs.

## Package Repositories

*Local PyPI repository server and proxies.*

* [:octocat: warehouse](https://github.com/pypa/warehouse) - Next generation Python Package Repository (PyPI). :star: 278 :fork_and_knife: 61
    * [:earth_americas: Warehouse](https://warehouse.python.org/)
* [:earth_americas: bandersnatch](https://bitbucket.org/pypa/bandersnatch) - PyPI mirroring tool provided by Python Packaging Authority (PyPA).
* [:earth_americas: devpi](http://doc.devpi.net/) - PyPI server and packaging/testing/release tool.
* [:octocat: localshop](https://github.com/mvantellingen/localshop) - Local PyPI server (custom packages and auto-mirroring of pypi). :star: 248 :fork_and_knife: 88

## Distribution

*Libraries to create packaged executables for release distribution.*

* [:octocat: PyInstaller](https://github.com/pyinstaller/pyinstaller) - Converts Python programs into stand-alone executables (cross-platform). :star: 1126 :fork_and_knife: 323
* [:earth_americas: dh-virtualenv](http://dh-virtualenv.readthedocs.org/) - Build and distribute a virtualenv as a Debian package.
* [:earth_americas: Nuitka](http://nuitka.net/) - Compile scripts, modules, packages to an executable or extension module.
* [:earth_americas: py2app](http://pythonhosted.org/py2app/) - Freezes Python scripts (Mac OS X).
* [:earth_americas: py2exe](http://www.py2exe.org/) - Freezes Python scripts (Windows).
* [:earth_americas: pynsist](http://pynsist.readthedocs.org/) - A tool to build Windows installers, installers bundle Python itself.

## Build Tools

*Compile software from source code.*

* [:earth_americas: buildout](http://www.buildout.org/) - A build system for creating, assembling and deploying applications from multiple parts.
* [:earth_americas: BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html) - A make-like build tool for embedded Linux.
* [:earth_americas: fabricate](https://code.google.com/p/fabricate/) - A build tool that finds dependencies automatically for any language.
* [:octocat: PlatformIO](https://github.com/ivankravets/platformio) - A console tool to build code with different development platforms. :star: 267 :fork_and_knife: 29
* [:octocat: PyBuilder](https://github.com/pybuilder/pybuilder) - A continuous build tool written in pure Python. :star: 467 :fork_and_knife: 113
* [:earth_americas: SCons](http://www.scons.org/) - A software construction tool.

## Interactive Interpreter

*Interactive Python interpreters (REPL).*

* [:octocat: IPython](https://github.com/ipython/ipython) - A rich toolkit to help you make the most out of using Python interactively. :star: 7464 :fork_and_knife: 2204
* [:earth_americas: bpython](http://bpython-interpreter.org) – A fancy interface to the Python interpreter.
* [:octocat: ptpython](https://github.com/jonathanslenders/ptpython) - Advanced Python REPL built on top of the [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). :star: 771 :fork_and_knife: 19

## Files

*Libraries for file manipulation and MIME type detection.*

* [:earth_americas: imghdr](https://docs.python.org/2/library/imghdr.html) - (Python standard library) Determine the type of an image.
* [:earth_americas: mimetypes](https://docs.python.org/2/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [:octocat: path.py](https://github.com/jaraco/path.py) - A module wrapper for [os.path](https://docs.python.org/2/library/os.path.html). :star: 529 :fork_and_knife: 72
* [:earth_americas: pathlib](https://pathlib.readthedocs.org/en/pep428/) - (Python standard library in Python 3.4+) An cross-platform, object-oriented path library.
* [:octocat: python-magic](https://github.com/ahupp/python-magic) - A Python interface to the libmagic file type identification library. :star: 515 :fork_and_knife: 84
* [:octocat: Unipath](https://github.com/mikeorr/Unipath) - An object-oriented approach to file/directory operations. :star: 315 :fork_and_knife: 27
* [:octocat: watchdog](https://github.com/gorakhargosh/watchdog) - API and shell utilities to monitor file system events. :star: 1778 :fork_and_knife: 239

## Date and Time

*Libraries for working with dates and times.*

* [:octocat: arrow](https://github.com/crsmithdev/arrow) - Better dates & times for Python. :star: 2503 :fork_and_knife: 212
* [:octocat: Chronyk](https://github.com/KoffeinFlummi/Chronyk) - A Python 3 library for parsing human-written times and dates. :star: 203 :fork_and_knife: 7
* [:earth_americas: dateutil](https://pypi.python.org/pypi/python-dateutil) - Extensions to the standard Python [datetime](https://docs.python.org/2/library/datetime.html) module.
* [:octocat: delorean](https://github.com/myusuf3/delorean/) - A library for clearing up the inconvenient truths that arise dealing with datetimes. :star: 833 :fork_and_knife: 48
* [:octocat: moment](https://github.com/zachwill/moment) - A Python library for dealing with dates/times. Inspired by [Moment.js](http://momentjs.com/). :star: 246 :fork_and_knife: 8
* [:octocat: PyTime](https://github.com/shnode/PyTime) - A easy-use Python module which aims to operate date/time/datetime by string. :star: 93 :fork_and_knife: 8
* [:earth_americas: pytz](https://launchpad.net/pytz) - World timezone definitions, modern and historical. Brings the [tz database](http://en.wikipedia.org/wiki/Tz_database) into Python.
* [:octocat: when.py](https://github.com/dirn/When.py) - Providing user-friendly functions to help perform common date and time actions. :star: 123 :fork_and_knife: 11

## Text Processing

*Libraries for parsing and manipulating plain texts.*

* General
    * [:octocat: chardet](https://github.com/chardet/chardet) - Python 2/3 compatible character encoding detector. :star: 368 :fork_and_knife: 60
    * [:earth_americas: difflib](https://docs.python.org/2/library/difflib.html) - (Python standard library) Helpers for computing deltas.
    * [:earth_americas: esmre](https://code.google.com/p/esmre/) - Regular expression accelerator.
    * [:octocat: ftfy](https://github.com/LuminosoInsight/python-ftfy) - Makes Unicode text less broken and more consistent automagically. :star: 1015 :fork_and_knife: 36
    * [:octocat: fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching. :star: 1963 :fork_and_knife: 175
    * [:octocat: Levenshtein](https://github.com/ztane/python-Levenshtein/) - Fast computation of Levenshtein distance and string similarity. :star: 149 :fork_and_knife: 32
    * [:octocat: pangu.py](https://github.com/vinta/pangu.py) - Spacing texts for CJK and alphanumerics. :star: 30 :fork_and_knife: 6
    * [:octocat: pyfiglet](https://github.com/pwaller/pyfiglet) - An implementation of figlet written in Python. :star: 114 :fork_and_knife: 12
    * [:octocat: shortuuid](https://github.com/stochastic-technologies/shortuuid) - A generator library for concise, unambiguous and URL-safe UUIDs. :star: 488 :fork_and_knife: 35
    * [:earth_americas: unidecode](https://pypi.python.org/pypi/Unidecode) - ASCII transliterations of Unicode text.
    * [:octocat: uniout](https://github.com/moskytw/uniout) - Print readable chars instead of the escaped string. :star: 70 :fork_and_knife: 6
    * [:octocat: xpinyin](https://github.com/lxneng/xpinyin) - A library to translate Chinese hanzi (漢字) to pinyin (拼音). :star: 248 :fork_and_knife: 65
* Slugify
    * [:octocat: awesome-slugify](https://github.com/dimka665/awesome-slugify) - A Python slugify library that can preserve unicode. :star: 223 :fork_and_knife: 15
    * [:octocat: python-slugify](https://github.com/un33k/python-slugify) - A Python slugify library that translates unicode to ASCII. :star: 172 :fork_and_knife: 25
    * [:octocat: unicode-slugify](https://github.com/mozilla/unicode-slugify) - A slugifier that generates unicode slugs with Django as a dependency. :star: 169 :fork_and_knife: 29
* Parser
    * [:octocat: phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - Parsing, formatting, storing and validating international phone numbers. :star: 971 :fork_and_knife: 124
    * [:earth_americas: PLY](http://www.dabeaz.com/ply/) - Implementation of lex and yacc parsing tools for Python
    * [:earth_americas: Pygments](http://pygments.org/) - A generic syntax highlighter.
    * [:earth_americas: pyparsing](http://pyparsing.wikispaces.com/) - A general purpose framework for generating parsers.
    * [:octocat: python-nameparser](https://github.com/derek73/python-nameparser) - Parsing human names into their individual components. :star: 101 :fork_and_knife: 16
    * [:octocat: python-user-agents](https://github.com/selwin/python-user-agents) - Browser user agent parser. :star: 242 :fork_and_knife: 52
    * [:earth_americas: sqlparse](https://sqlparse.readthedocs.org/) - A non-validating SQL parser.

## Specific Formats Processing

*Libraries for parsing and manipulating specific text formats.*

* General
    * [:octocat: tablib](https://github.com/kennethreitz/tablib) - A module for Tabular Datasets in XLS, CSV, JSON, YAML. :star: 1568 :fork_and_knife: 218
* Office
    * [:octocat: Marmir](https://github.com/brianray/mm) - Takes Python data structures and turns them into spreadsheets. :star: 109 :fork_and_knife: 15
    * [:earth_americas: openpyxl](https://openpyxl.readthedocs.org/en/latest/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
    * [:octocat: python-docx](https://github.com/python-openxml/python-docx) - Reads, queries and modifies Microsoft Word 2007/2008 docx files. :star: 356 :fork_and_knife: 127
    * [:octocat: unoconv](https://github.com/dagwieers/unoconv) - Convert between any document format supported by LibreOffice/OpenOffice. :star: 586 :fork_and_knife: 194
    * [:earth_americas: XlsxWriter](https://xlsxwriter.readthedocs.org/) - A Python module for creating Excel .xlsx files.
    * [:earth_americas: xlwings](http://xlwings.org/) - A BSD-licensed library that makes it easy to call Python from Excel and vice versa.
    * [:octocat: xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - Writing and reading data and formatting information from Excel files. :star: 435 :fork_and_knife: 150
* PDF
    * [:octocat: PDFMiner](https://github.com/euske/pdfminer) - A tool for extracting information from PDF documents. :star: 1201 :fork_and_knife: 299
    * [:octocat: PyPDF2](https://github.com/mstamy2/PyPDF2) - A library capable of splitting, merging and transforming PDF pages. :star: 736 :fork_and_knife: 228
    * [:earth_americas: ReportLab](http://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* Markdown
    * [:octocat: Mistune](https://github.com/lepture/mistune) - Fastest and full featured pure Python parsers of Markdown. :star: 470 :fork_and_knife: 34
    * [:octocat: Python-Markdown](https://github.com/waylan/Python-Markdown) - A Python implementation of John Gruber’s Markdown. :star: 763 :fork_and_knife: 212
* YAML
    * [:earth_americas: PyYAML](http://pyyaml.org/) - YAML implementations for Python.
* CSV
    * [:octocat: csvkit](https://github.com/onyxfish/csvkit) - Utilities for converting to and working with CSV. :star: 1673 :fork_and_knife: 253
* Archive
    * [:octocat: unp](https://github.com/mitsuhiko/unp) - A command line tool that can unpack archives easily. :star: 207 :fork_and_knife: 8

## Natural Language Processing

*Libraries for working with human languages.*

* [:earth_americas: NLTK](http://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
* [:octocat: jieba](https://github.com/fxsjy/jieba) - Chinese Words Segmentation Utilities. :star: 3648 :fork_and_knife: 1138
* [:octocat: langid.py](https://github.com/saffsd/langid.py) - Stand-alone language identification system. :star: 425 :fork_and_knife: 75
* [:earth_americas: Pattern](http://www.clips.ua.ac.be/pattern) - A web mining module for the Python.
* [:octocat: SnowNLP](https://github.com/isnowfy/snownlp) - A library for processing Chinese text. :star: 978 :fork_and_knife: 263
* [:earth_americas: TextBlob](http://textblob.readthedocs.org/) - Providing a consistent API for diving into common NLP tasks.

## Documentation

*Libraries for generating project documentation.*

* [:earth_americas: Sphinx](http://sphinx-doc.org/) - Python Documentation generator.
    * [:octocat: awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc) :star: 113 :fork_and_knife: 8
* [:earth_americas: MkDocs](http://www.mkdocs.org/) - Markdown friendly documentation generator.
* [:octocat: pdoc](https://github.com/BurntSushi/pdoc) - Epydoc replacement to auto generate API documentation for Python libraries. :star: 121 :fork_and_knife: 23
* [:earth_americas: Pycco](http://fitzgen.github.io/pycco/) - The literate-programming-style documentation generator.

## Configuration

*Libraries for storing configuration options.*

* [:earth_americas: config](http://www.red-dove.com/config-doc/) - Hierarchical config from the author of [logging](https://docs.python.org/2/library/logging.html).
* [:earth_americas: ConfigObj](http://www.voidspace.org.uk/python/configobj.html) - INI file parser with validation.
* [:earth_americas: ConfigParser](https://docs.python.org/2/library/configparser.html) - (Python standard library) INI file parser.
* [:earth_americas: profig](http://profig.readthedocs.org/) - Config from multiple formats with value conversion.

## Command-line Tools

*Libraries for building command-line application.*

* Command-line Application Development
    * [:earth_americas: cement](http://builtoncement.com/) - Providing a light-weight and fully featured foundation to build anything from single file scripts to complex and intricately designed applications.
    * [:earth_americas: click](http://click.pocoo.org/) - A package for creating beautiful command line interfaces in a composable way.
    * [:earth_americas: cliff](http://docs.openstack.org/developer/cliff/) - A framework for creating command-line programs with multi-level commands.
    * [:earth_americas: Clime](http://clime.mosky.tw) – Clime lets you convert any module into a multi-command CLI program without any configuration.
    * [:octocat: clint](https://github.com/kennethreitz/clint) - Python Command-line Application Tools. :star: 1787 :fork_and_knife: 167
    * [:earth_americas: colorama](https://pypi.python.org/pypi/colorama) - Cross-platform colored terminal text.
    * [:earth_americas: docopt](http://docopt.org/) - Pythonic command line arguments parser.
    * [:octocat: Gooey](https://github.com/chriskiehl/Gooey) - Turn command line programs into a full GUI application with one line :star: 3655 :fork_and_knife: 172
    * [:earth_americas: pyCLI](https://pythonhosted.org/pyCLI/) - Command-line applications supporting standard command line parsing, logging, unit and functional testing.
    * [:octocat: python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - A Library for building powerful interactive command lines. :star: 1681 :fork_and_knife: 75
* Productivity Tools
    * [:octocat: bashplotlib](https://github.com/glamp/bashplotlib) - Making basic plots in the terminal. It's a quick way to visualize data without GUI. :star: 303 :fork_and_knife: 22
    * [:octocat: caniusepython3](https://github.com/brettcannon/caniusepython3) - Determine what projects are blocking you from porting to Python 3. :star: 206 :fork_and_knife: 21
    * [:octocat: cookiecutter](https://github.com/audreyr/cookiecutter) - A command-line utility that creates projects from cookiecutters (project templates). E.g. Python package projects, jQuery plugin projects. :star: 2275 :fork_and_knife: 274
    * [:octocat: doitlive](https://github.com/sloria/doitlive) - A tool for live presentations in the terminal. :star: 594 :fork_and_knife: 17
    * [:octocat: httpie](https://github.com/jakubroztocil/httpie) - A command line HTTP client, a user-friendly cURL replacement. :star: 17764 :fork_and_knife: 1004
    * [:octocat: PathPicker](https://github.com/facebook/PathPicker) - Select files out of bash output. :star: 2501 :fork_and_knife: 115
    * [:octocat: percol](https://github.com/mooz/percol) - Adds flavor of interactive selection to the traditional pipe concept on UNIX. :star: 1772 :fork_and_knife: 71
    * [:earth_americas: RainbowStream](http://www.rainbowstream.org/) - Smart and nice Twitter client on terminal.
    * [:octocat: thefuck](https://github.com/nvbn/thefuck) - Correcting your previous console command. :star: 13547 :fork_and_knife: 640

## Downloader

*Libraries for downloading.*

* [:octocat: coursera](https://github.com/coursera-dl/coursera) - Script for downloading Coursera.org videos and naming them. :star: 2473 :fork_and_knife: 900
* [:octocat: s3cmd](https://github.com/s3tools/s3cmd) - A command line tool for managing Amazon S3 and CloudFront. :star: 1556 :fork_and_knife: 514
* [:octocat: s4cmd](https://github.com/bloomreach/s4cmd) - Super S3 command line tool, good for higher performance. :star: 275 :fork_and_knife: 54
* [:octocat: subliminal](https://github.com/Diaoul/subliminal) - Library and command line tool to search and download subtitles. :star: 754 :fork_and_knife: 180
* [:octocat: WikiTeam](https://github.com/WikiTeam/wikiteam) - Tools for downloading and preserving wikis. :star: 75 :fork_and_knife: 26
* [:earth_americas: you-get](http://www.soimort.org/you-get/) - A YouTube/Youku/Niconico video downloader written in Python 3.
* [:earth_americas: youtube-dl](http://rg3.github.io/youtube-dl/) - A small command-line program to download videos from YouTube.

## Imagery

*Libraries for manipulating images.*

* [:earth_americas: pillow](http://pillow.readthedocs.org/) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork.
* [:octocat: hmap](https://github.com/rossgoodwin/hmap) - Image histogram remapping. :star: 97 :fork_and_knife: 5
* [:earth_americas: imgSeek](http://www.imgseek.net/) - A project for searching a collection of images using visual similarity.
* [:octocat: nude.py](https://github.com/hhatto/nude.py) - Nudity detection. :star: 274 :fork_and_knife: 28
* [:earth_americas: pyBarcode](https://pythonhosted.org/pyBarcode/) - Create barcodes in Python without needing PIL.
* [:octocat: pygram](https://github.com/ajkumar25/pygram) - Instagram-like image filters. :star: 31 :fork_and_knife: 3
* [:octocat: python-qrcode](https://github.com/lincolnloop/python-qrcode) - A pure Python QR Code generator. :star: 722 :fork_and_knife: 169
* [:octocat: Quads](https://github.com/fogleman/Quads) - Computer art based on quadtrees. :star: 486 :fork_and_knife: 34
* [:earth_americas: scikit-image](http://scikit-image.org/) - A Python library for (scientific) image processing.
* [:octocat: thumbor](https://github.com/thumbor/thumbor) - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images. :star: 3281 :fork_and_knife: 304
* [:octocat: wand](https://github.com/dahlia/wand) - Python bindings for [MagickWand](http://www.imagemagick.org/script/magick-wand.php), C API for ImageMagick. :star: 476 :fork_and_knife: 112

## OCR

*Libraries for Optical Character Recognition.*

* [:octocat: pyocr](https://github.com/jflesch/pyocr) - A wrapper for Tesseract and Cuneiform. :star: 151 :fork_and_knife: 36
* [:octocat: pytesseract](https://github.com/madmaze/pytesseract) - Another wrapper for Google Tesseract OCR. :star: 257 :fork_and_knife: 69
* [:earth_americas: python-tesseract](https://code.google.com/p/python-tesseract) - A wrapper class for [Google Tesseract OCR](https://code.google.com/p/tesseract-ocr/).

## Audio

*Libraries for manipulating audio.*

* [:octocat: audiolazy](https://github.com/danilobellini/audiolazy) - Expressive Digital Signal Processing (DSP) package for Python. :star: 184 :fork_and_knife: 18
* [:octocat: audioread](https://github.com/sampsyo/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding. :star: 78 :fork_and_knife: 20
* [:earth_americas: beets](http://beets.radbox.org/) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
* [:octocat: dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition. :star: 1782 :fork_and_knife: 282
* [:octocat: django-elastic-transcoder](https://github.com/StreetVoice/django-elastic-transcoder) - Django + [Amazon Elastic Transcoder](http://aws.amazon.com/elastictranscoder/). :star: 17 :fork_and_knife: 9
* [:earth_americas: eyeD3](http://eyed3.nicfit.net/) - A tool for working with audio files, specifically MP3 files containing ID3 metadata.
* [:earth_americas: id3reader](http://nedbatchelder.com/code/modules/id3reader.py) - A Python module for reading MP3 meta data.
* [:octocat: m3u8](https://github.com/globocom/m3u8) - A module for parsing m3u8 file. :star: 119 :fork_and_knife: 50
* [:earth_americas: mutagen](https://bitbucket.org/lazka/mutagen) - A Python module to handle audio metadata.
* [:octocat: pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface. :star: 1207 :fork_and_knife: 110
* [:octocat: pyechonest](https://github.com/echonest/pyechonest) - Python client for the [Echo Nest](http://developer.echonest.com/docs/) API. :star: 479 :fork_and_knife: 889
* [:earth_americas: talkbox](http://scikits.appspot.com/talkbox) - A Python library for speech/signal processing.
* [:octocat: TimeSide](https://github.com/yomguy/TimeSide) - Open web audio processing framework. :star: 124 :fork_and_knife: 14
* [:octocat: tinytag](https://github.com/devsnd/tinytag) - A library for reading music meta data of MP3, OGG, FLAC and Wave files. :star: 136 :fork_and_knife: 14

## Video

*Libraries for manipulating video and GIFs.*

* [:earth_americas: moviepy](http://zulko.github.io/moviepy/) - A module for script-based movie editing with many formats, including animated GIFs.
* [:octocat: scikit-video](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy. :star: 24 :fork_and_knife: 2
* [:earth_americas: shorten.tv](http://www.shorten.tv/) - Video summarization.

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [:earth_americas: GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.
* [:octocat: GeoIP](https://github.com/maxmind/geoip-api-python) - Python API for MaxMind GeoIP Legacy Database. :star: 103 :fork_and_knife: 29
* [:octocat: geojson](https://github.com/frewsxcv/python-geojson) - Python bindings and utilities for GeoJSON. :star: 161 :fork_and_knife: 26
* [:octocat: geopy](https://github.com/geopy/geopy) - Python Geocoding Toolbox. :star: 840 :fork_and_knife: 224
* [:octocat: pygeoip](https://github.com/appliedsec/pygeoip) - Pure Python GeoIP API. :star: 372 :fork_and_knife: 78
* [:octocat: django-countries](https://github.com/SmileyChris/django-countries) - A Django app that provides country choices for use with forms, flag icons static files, and a country field for models. :star: 178 :fork_and_knife: 66

## HTTP

*Libraries for working with HTTP.*

* [:earth_americas: requests](http://docs.python-requests.org/) - HTTP Requests for Humans™.
* [:octocat: grequests](https://github.com/kennethreitz/grequests) - requests + gevent for asynchronous HTTP requests. :star: 1108 :fork_and_knife: 131
* [:octocat: httplib2](https://github.com/jcgregorio/httplib2) - Comprehensive HTTP client library. :star: 283 :fork_and_knife: 139
* [:octocat: treq](https://github.com/dreid/treq) - Python requests like API built on top of Twisted's HTTP client. :star: 208 :fork_and_knife: 58
* [:octocat: urllib3](https://github.com/shazow/urllib3) - A HTTP library with thread-safe connection pooling, file post support, sanity friendly. :star: 902 :fork_and_knife: 273

## Database

*Databases implemented in Python.*

* [:earth_americas: pickleDB](https://pythonhosted.org/pickleDB/) - A simple and lightweight key-value store for Python.
* [:earth_americas: PipelineDB](http://www.pipelinedb.com/) - The Streaming SQL Database.
* [:octocat: TinyDB](https://github.com/msiemens/tinydb) - A tiny, document-oriented database. :star: 526 :fork_and_knife: 38
* [:earth_americas: ZODB](http://www.zodb.org/) - A native object database for Python. A key-value and object graph database.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [:earth_americas: apsw](http://rogerbinns.github.io/apsw/) - Another Python SQLite wrapper.
    * [:octocat: dataset](https://github.com/pudo/dataset) - Store Python dicts in a database - works with SQLite, MySQL, and PostgreSQL. :star: 1544 :fork_and_knife: 97
    * [:earth_americas: mysql-connector-python](https://pypi.python.org/pypi/mysql-connector-python) - A pure Python MySQL driver from Oracle.
    * [:earth_americas: mysql-python](http://sourceforge.net/projects/mysql-python/) - The MySQL database connector for Python.
    * [:octocat: mysqlclient](https://github.com/PyMySQL/mysqlclient-python) - mysql-python fork supporting Python 3. :star: 168 :fork_and_knife: 17
    * [:earth_americas: oursql](https://pythonhosted.org/oursql/) - A better MySQL connector with support for native prepared statements and BLOBs.
    * [:earth_americas: psycopg2](http://initd.org/psycopg/) - The most popular PostgreSQL adapter for Python.
    * [:octocat: PyMySQL](https://github.com/PyMySQL/PyMySQL) - Pure Python MySQL driver compatible to mysql-python. :star: 1202 :fork_and_knife: 283
    * [:octocat: queries](https://github.com/gmr/queries) - A wrapper of the psycopg2 library for interacting with PostgreSQL. :star: 109 :fork_and_knife: 7
    * [:earth_americas: txpostgres](http://txpostgres.readthedocs.org/) - Twisted based asynchronous driver for PostgreSQL.
* NoSQL Databases
    * [:octocat: cassandra-python-driver](https://github.com/datastax/python-driver) - Python driver for Cassandra. :star: 390 :fork_and_knife: 192
    * [:earth_americas: HappyBase](http://happybase.readthedocs.org/) - A developer-friendly library for Apache HBase.
    * [:earth_americas: Plyvel](https://plyvel.readthedocs.org/) - A fast and feature-rich Python interface to LevelDB.
    * [:earth_americas: py2neo](http://book.py2neo.org/) - Python wrapper client for Neo4j's restful interface.
    * [:octocat: pycassa](https://github.com/pycassa/pycassa) - Python Thrift driver for Cassandra. :star: 488 :fork_and_knife: 133
    * [:earth_americas: PyMongo](http://docs.mongodb.org/ecosystem/drivers/python/) - The official Python client for MongoDB.
    * [:octocat: redis-py](https://github.com/andymccurdy/redis-py) - The Redis Python Client. :star: 3553 :fork_and_knife: 870
    * [:octocat: telephus](https://github.com/driftx/Telephus) - Twisted based client for Cassandra. :star: 90 :fork_and_knife: 33
    * [:octocat: txRedis](https://github.com/deldotdr/txRedis) - Twisted based client for Redis. :star: 95 :fork_and_knife: 30

## ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
    * [:earth_americas: Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/) - A part of Django.
    * [:earth_americas: SQLAlchemy](http://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper.
        * [:octocat: awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) :star: 895 :fork_and_knife: 56
    * [:octocat: peewee](https://github.com/coleifer/peewee) - A small, expressive ORM. :star: 2162 :fork_and_knife: 357
    * [:earth_americas: PonyORM](http://ponyorm.com) - ORM that provides a generator-oriented interface to SQL.
* NoSQL Databases
    * [:octocat: django-mongodb-engine](https://github.com/django-nonrel/mongodb-engine) - Django MongoDB Backend. :star: 570 :fork_and_knife: 177
    * [:octocat: PynamoDB](https://github.com/jlafon/PynamoDB) - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/). :star: 128 :fork_and_knife: 38
    * [:octocat: flywheel](https://github.com/mathcamp/flywheel) - Object mapper for Amazon DynamoDB. :star: 38 :fork_and_knife: 6
    * [:earth_americas: MongoEngine](http://mongoengine.org/) - A Python Object-Document-Mapper for working with MongoDB.
    * [:octocat: hot-redis](https://github.com/stephenmcd/hot-redis) - Rich Python data types for Redis. :star: 155 :fork_and_knife: 9
    * [:octocat: redisco](https://github.com/kiddouk/redisco) - A Python Library for Simple Models and Containers Persisted in Redis. :star: 259 :fork_and_knife: 46
* Others
    * [:octocat: butterdb](https://github.com/Widdershin/butterdb) - A Python ORM for Google Drive Spreadsheets. :star: 287 :fork_and_knife: 12

## Web Frameworks

*Full stack web frameworks.*

* [:earth_americas: Django](https://www.djangoproject.com/) - The most popular web framework in Python.
    * [:octocat: awesome-django](https://github.com/rosarior/awesome-django) :star: 2677 :fork_and_knife: 402
* [:earth_americas: Flask](http://flask.pocoo.org/) - A microframework for Python.
    * [:octocat: awesome-flask](https://github.com/humiaozuzu/awesome-flask) :star: 1441 :fork_and_knife: 186
* [:earth_americas: Pyramid](http://www.pylonsproject.org/) - A small, fast, down-to-earth, open source Python web framework.
    * [:octocat: awesome-pyramid](https://github.com/ITCase/awesome-pyramid) :star: 174 :fork_and_knife: 17
* [:earth_americas: Bluebream](http://bluebream.zope.org/) - An open-source web application server, framework and library, formerly known as Zope 3.
* [:earth_americas: Bottle](http://bottlepy.org/) - A fast, simple and lightweight WSGI micro web-framework.
* [:earth_americas: CherryPy](http://www.cherrypy.org/) - A Minimalist Python Web Framework, HTTP/1.1-compliant and WSGI thread-pooled.
* [:earth_americas: Grok](http://grok.zope.org/) - A framework built on the existing Zope 3 libraries.
* [:octocat: guava](https://github.com/flatpeach/guava) - A lightweight and high performance web framework for Python written in C. :star: 128 :fork_and_knife: 8
* [:earth_americas: TurboGears](http://www.turbogears.org/) - The Web Framework that starts as a microframework and scales up to a full stack solution.
* [:earth_americas: web.py](http://webpy.org/) - A web framework for Python that is as simple as it is powerful.
* [:earth_americas: web2py](http://www.web2py.com) - A full stack web framework and platform focused in the ease of use.

## Permissions

*Libraries that allow or deny users access to data or functionality.*

* [:earth_americas: Carteblanche](http://www.github.com/neuman/python-carteblanche/) - Module to align code with thoughts of users and designers. Also magically handles navigation and permissions.
* [:octocat: django-guardian](https://github.com/lukaszb/django-guardian) - Implementation of per object permissions for Django 1.2+ :star: 945 :fork_and_knife: 267
* [:octocat: django-rules](https://github.com/dfunckt/django-rules) - A tiny but powerful app providing object-level permissions to Django, without requiring a database. :star: 218 :fork_and_knife: 17

## CMS

*Content Management Systems.*

* [:earth_americas: django-cms](https://www.django-cms.org/en/) - An Open source enterprise CMS based on the Django.
* [:earth_americas: djedi-cms](http://djedi-cms.org/) - A lightweight but yet powerful Django CMS with plugins, inline editing and performance in mind.
* [:earth_americas: FeinCMS](http://www.feincms.org/) - One of the most advanced Content Management Systems built on Django.
* [:earth_americas: Kotte](http://kotti.pylonsproject.org/) - A high-level, Pythonic web application framework built on Pyramid.
* [:earth_americas: Mezzanine](http://mezzanine.jupo.org/) - A powerful, consistent, and flexible content management platform.
* [:earth_americas: Opps](http://oppsproject.org/) - A Django-based CMS for magazines, newspapers websites and portals with high-traffic.
* [:earth_americas: Plone](http://plone.org/) - A CMS built on top of the open source application server Zope.
* [:earth_americas: Quokka](http://quokkaproject.org/) - Flexible, extensible, small CMS powered by Flask and MongoDB.
* [:earth_americas: Wagtail](http://wagtail.io/) - A Django content management system.
* [:earth_americas: Widgy](http://wid.gy/) - Last CMS framework, based on Django.

## E-commerce

*Frameworks and libraries for e-commerce and payments.*

* [:earth_americas: django-oscar](http://oscarcommerce.com/) - An open-source e-commerce framework for Django.
* [:earth_americas: django-shop](https://www.django-cms.org/) - A Django based shop system.
* [:octocat: Cartridge](https://github.com/stephenmcd/cartridge) - A shopping cart app built using the Mezzanine. :star: 416 :fork_and_knife: 194
* [:earth_americas: shoop](https://www.shoop.io/) - An open source E-Commerce platform based on Django.
* [:octocat: alipay](https://github.com/lxneng/alipay) - Unofficial Alipay API for Python. :star: 77 :fork_and_knife: 32
* [:octocat: merchant](https://github.com/agiliq/merchant) - A Django app to accept payments from various payment processors. :star: 791 :fork_and_knife: 140
* [:octocat: money](https://github.com/carlospalol/money) - Money class with optional CLDR-backed locale-aware formatting and an extensible currency exchange solution. :star: 42 :fork_and_knife: 5
* [:octocat: python-currencies](https://github.com/Alir3z4/python-currencies) - Display money format and its filthy currencies. :star: 15 :fork_and_knife: 0

## RESTful API

*Libraries for developing RESTful APIs.*

* [:earth_americas: django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit that makes it easy to build Web APIs.
* [:earth_americas: django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* [:octocat: django-formapi](https://github.com/5monkeys/django-formapi) - Create JSON APIs with HMAC authentication and Django form-validation. :star: 17 :fork_and_knife: 8
* [:earth_americas: flask-api](http://www.flaskapi.org/) - Browsable Web APIs for Flask.
* [:earth_americas: flask-restful](http://flask-restful.readthedocs.org/) - An extension for Flask that adds support for quickly building REST APIs.
* [:earth_americas: flask-restless](https://flask-restless.readthedocs.org/en/latest/) - Generating RESTful APIs for database models defined with SQLAlchemy.
* [:octocat: flask-api-utils](https://github.com/marselester/flask-api-utils) - Flask extension that takes care of API representation and authentication. :star: 18 :fork_and_knife: 2
* [:earth_americas: falcon](http://falconframework.org/) - A high-performance Python framework for building cloud APIs and web app backends.
* [:octocat: eve](https://github.com/nicolaiarocci/eve) - REST API framework powered by Flask, MongoDB and good intentions. :star: 2583 :fork_and_knife: 354
* [:octocat: sandman](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems. :star: 2088 :fork_and_knife: 162
* [:earth_americas: restless](http://restless.readthedocs.org/en/latest/) - Framework agnostic REST framework based on lessons learned from TastyPie.
* [:octocat: savory-pie](https://github.com/RueLaLa/savory-pie/) - REST API building library (Django, and others) :star: 6 :fork_and_knife: 7
* [:octocat: ripozo](https://github.com/vertical-knowledge/ripozo) - Quickly creating REST/HATEOAS/Hypermedia APIs with extensions for Flask and Django. :star: 109 :fork_and_knife: 5
* [:earth_americas: cornice](https://cornice.readthedocs.org/) - A REST framework for Pyramid.

## Authentication

*Libraries for implementing authentications schemes.*

* OAuth
    * [:earth_americas: Authomatic](http://peterhudec.github.io/authomatic/) - Simple but powerful framework agnostic authentication/authorization client.
    * [:octocat: django-allauth](https://github.com/pennersr/django-allauth) - Authentication app for Django that "just works." :star: 1957 :fork_and_knife: 706
    * [:octocat: django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - OAuth2 goodies for the Djangonauts. :star: 547 :fork_and_knife: 172
    * [:octocat: django-oauth2-provider](https://github.com/caffeinehit/django-oauth2-provider) - Providing OAuth2 access to Django app. :star: 270 :fork_and_knife: 201
    * [:octocat: Flask-OAuthlib](https://github.com/lepture/flask-oauthlib) - OAuth 1.0/a, 2.0 implementation of client and provider for Flask. :star: 535 :fork_and_knife: 159
    * [:octocat: OAuthLib](https://github.com/idan/oauthlib) - A generic and thorough implementation of the OAuth request-signing logic. :star: 958 :fork_and_knife: 216
    * [:octocat: python-oauth2](https://github.com/simplegeo/python-oauth2) - A fully tested, abstract interface to creating OAuth clients and servers. :star: 2278 :fork_and_knife: 902
    * [:octocat: python-social-auth](https://github.com/omab/python-social-auth) - An easy-to-setup social authentication mechanism. :star: 1855 :fork_and_knife: 765
    * [:octocat: rauth](https://github.com/litl/rauth) - A Python library for OAuth 1.0/a, 2.0, and Ofly. :star: 1369 :fork_and_knife: 140
    * [:octocat: sanction](https://github.com/demianbrecht/sanction) - A dead simple OAuth2 client implementation. :star: 136 :fork_and_knife: 34
* Others
    * [:octocat: jose](https://github.com/demonware/jose) - JavaScript Object Signing and Encryption draft implementation. :star: 28 :fork_and_knife: 10
    * [:octocat: PyJWT](https://github.com/progrium/pyjwt) - Implementation of the JSON Web Token draft 01. :star: 515 :fork_and_knife: 89
    * [:octocat: python-jws](https://github.com/brianloveswords/python-jws) - Implementation of JSON Web Signatures draft 02. :star: 30 :fork_and_knife: 12
    * [:octocat: python-jwt](https://github.com/davedoesdev/python-jwt) - Module for generating and verifying JSON Web Tokens. :star: 73 :fork_and_knife: 7

## Template Engine

*Libraries and tools for templating and lexing.*

* [:octocat: Jinja2](https://github.com/mitsuhiko/jinja2) - A modern and designer friendly templating language. :star: 2690 :fork_and_knife: 553
* [:earth_americas: Chameleon](https://chameleon.readthedocs.org/) - An HTML/XML template engine. Modeled after ZPT, optimized for speed.
* [:earth_americas: Genshi](http://genshi.edgewall.org/) - Python templating toolkit for generation of web-aware output.
* [:earth_americas: Mako](http://www.makotemplates.org/) - Hyperfast and lightweight templating for the Python platform.
* [:earth_americas: Spitfire](https://code.google.com/p/spitfire/) - A very fast Python template compiler.

## Queue

*Libraries for working with event and task queues.*

* [:earth_americas: celery](http://www.celeryproject.org/) - An asynchronous task queue/job queue based on distributed message passing.
* [:octocat: huey](https://github.com/coleifer/huey) - Little multi-threaded task queue. :star: 730 :fork_and_knife: 68
* [:octocat: mrq](https://github.com/pricingassistant/mrq) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent. :star: 299 :fork_and_knife: 15
* [:earth_americas: rq](http://python-rq.org/) - Simple job queues for Python.
* [:octocat: simpleq](https://github.com/rdegges/simpleq) - A simple, infinitely scalable, Amazon SQS based queue. :star: 87 :fork_and_knife: 5

## Search

*Libraries and software for indexing and performing search queries on data.*

* [:octocat: django-haystack](https://github.com/toastdriven/django-haystack) - Modular search for Django. :star: 1794 :fork_and_knife: 761
* [:earth_americas: elasticsearch-py](http://www.elasticsearch.org/guide/en/elasticsearch/client/python-api/current/) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [:octocat: elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch. :star: 506 :fork_and_knife: 120
* [:earth_americas: solrpy](https://code.google.com/p/solrpy/) - A Python client for [solr](http://lucene.apache.org/solr/).
* [:earth_americas: Whoosh](http://whoosh.readthedocs.org/) - A fast, pure Python search engine library.

## News Feed

*Libraries for building user's activities.*

* [:octocat: django-activity-stream](https://github.com/justquick/django-activity-stream) - Generate generic activity streams from the actions on your site. :star: 899 :fork_and_knife: 271
* [:octocat: Feedly](https://github.com/tschellenbach/Feedly) - A library to build newsfeed and notification systems using Cassandra and Redis. :star: 1740 :fork_and_knife: 208

## Asset Management

*Tools for managing, compressing and minifying website assets.*

* [:octocat: django-compressor](https://github.com/django-compressor/django-compressor) - Compresses linked and inline JavaScript or CSS into a single cached file. :star: 1551 :fork_and_knife: 439
* [:earth_americas: django-storages](http://code.larlet.fr/django-storages/) - A collection of custom storage back ends for Django.
* [:earth_americas: fanstatic](http://www.fanstatic.org/) - Packages, optimizes, and serves static file dependencies as Python packages.
* [:earth_americas: File Conveyor](http://fileconveyor.org/) - A daemon to detect and sync files to CDNs, S3 and FTP.
* [:earth_americas: Flask-Assets](http://flask-assets.readthedocs.org/) - Helps you integrate webassets into your Flask app.
* [:earth_americas: glue](http://gluecss.com) - Glue is a simple command line tool to generate CSS sprites.
* [:octocat: jinja-assets-compressor](https://github.com/jaysonsantos/jinja-assets-compressor) - A Jinja extension to compile and compress your assets. :star: 28 :fork_and_knife: 8
* [:earth_americas: webassets](http://webassets.readthedocs.org/) - Bundles, optimizes, and manages unique cache-busting URLs for static resources.

## Caching

*Libraries for caching data.*

* [:earth_americas: Beaker](http://beaker.readthedocs.org/) - A library for caching and sessions for use with web applications and stand-alone Python scripts and applications.
* [:octocat: django-cache-machine](https://github.com/jbalogh/django-cache-machine) - Automatic caching and invalidation for Django models. :star: 574 :fork_and_knife: 118
* [:octocat: django-cacheops](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation. :star: 435 :fork_and_knife: 71
* [:octocat: django-viewlet](https://github.com/5monkeys/django-viewlet) - Render template parts with extended cache control. :star: 52 :fork_and_knife: 8
* [:earth_americas: dogpile.cache](http://dogpilecache.readthedocs.org/) - dogpile.cache is next generation replacement for Beaker made by same authors.
* [:earth_americas: HermesCache](https://pypi.python.org/pypi/HermesCache) - Python caching library with tag-based invalidation and dogpile effect prevention.
* [:octocat: johnny-cache](https://github.com/jmoiron/johnny-cache) - A caching framework for django applications. :star: 242 :fork_and_knife: 87
* [:octocat: pylibmc](https://github.com/lericson/pylibmc) - A Python wrapper around the [libmemcached](http://libmemcached.org/libMemcached.html) interface. :star: 305 :fork_and_knife: 106

## Email

*Libraries for sending and parsing email.*

* [:octocat: django-celery-ses](https://github.com/StreetVoice/django-celery-ses) - Django email back end with AWS SES and Celery. :star: 14 :fork_and_knife: 2
* [:earth_americas: envelopes](http://tomekwojcik.github.io/envelopes/) - Mailing for human beings.
* [:octocat: flanker](https://github.com/mailgun/flanker) - A email address and Mime parsing library. :star: 817 :fork_and_knife: 73
* [:octocat: imbox](https://github.com/martinrusev/imbox) - Python IMAP for Humans. :star: 578 :fork_and_knife: 70
* [:octocat: inbox.py](https://github.com/kennethreitz/inbox.py) - Python SMTP Server for Humans. :star: 1135 :fork_and_knife: 72
* [:octocat: inbox](https://github.com/inboxapp/inbox) - The open source email toolkit. :star: 2167 :fork_and_knife: 184
* [:octocat: lamson](https://github.com/zedshaw/lamson) - Pythonic SMTP Application Server. :star: 498 :fork_and_knife: 121
* [:octocat: mailjet](https://github.com/WoLpH/mailjet) - Mailjet API implementation for batch mailing, statistics and more. :star: 12 :fork_and_knife: 11
* [:octocat: marrow.mailer](https://github.com/marrow/marrow.mailer) - High-performance extensible mail delivery framework. :star: 87 :fork_and_knife: 23
* [:octocat: modoboa](https://github.com/tonioo/modoboa) - A mail hosting and management platform including a modern and simplified Web UI. :star: 411 :fork_and_knife: 67
* [:earth_americas: pyzmail](http://www.magiksys.net/pyzmail/) - Compose, send and parse emails.
* [:octocat: Talon](https://github.com/mailgun/talon) - Mailgun library to extract message quotations and signatures. :star: 480 :fork_and_knife: 62

## Internationalization

*Libraries for working with i18n.*

* [:earth_americas: Babel](http://babel.pocoo.org/) - An internationalization library for Python.
* [:earth_americas: Korean](https://korean.readthedocs.org/) - A library for [Korean](http://en.wikipedia.org/wiki/Korean_language) morphology.

## URL Manipulation

*Libraries for parsing URLs.*

* [:octocat: furl](https://github.com/gruns/furl) - A small Python library that makes manipulating URLs simple. :star: 815 :fork_and_knife: 48
* [:octocat: purl](https://github.com/codeinthehole/purl) - A simple, immutable URL class with a clean API for interrogation and manipulation. :star: 128 :fork_and_knife: 17
* [:octocat: pyshorteners](https://github.com/ellisonleao/pyshorteners) - A pure Python URL shortening lib. :star: 81 :fork_and_knife: 14
* [:octocat: short_url](https://github.com/Alir3z4/python-short_url) - Python implementation for generating Tiny URL and bit.ly-like URLs. :star: 37 :fork_and_knife: 6
* [:octocat: webargs](https://github.com/sloria/webargs) - A friendly library for parsing HTTP request arguments, with built-in support for popular web frameworks, including Flask, Django, Bottle, Tornado, and Pyramid. :star: 220 :fork_and_knife: 22

## HTML Manipulation

*Libraries for working with HTML and XML.*

* [:earth_americas: BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.
* [:earth_americas: bleach](http://bleach.readthedocs.org/) - A whitelist-based HTML sanitization and text linkification library.
* [:earth_americas: cssutils](https://pypi.python.org/pypi/cssutils/) - A CSS library for Python.
* [:octocat: html5lib](https://github.com/html5lib/html5lib-python) - A standards-compliant library for parsing and serializing HTML documents and fragments. :star: 367 :fork_and_knife: 88
* [:earth_americas: lxml](http://lxml.de/) - A very fast, easy-to-use and versatile library for handling HTML and XML.
* [:octocat: MarkupSafe](https://github.com/mitsuhiko/markupsafe) - Implements a XML/HTML/XHTML Markup safe string for Python. :star: 93 :fork_and_knife: 39
* [:octocat: pyquery](https://github.com/gawel/pyquery) - A jQuery-like library for parsing HTML. :star: 759 :fork_and_knife: 72
* [:octocat: untangle](https://github.com/stchris/untangle) - Converts XML documents to Python objects for easy access. :star: 112 :fork_and_knife: 12
* [:octocat: xhtml2pdf](https://github.com/chrisglass/xhtml2pdf) - HTML/CSS to PDF converter. :star: 1019 :fork_and_knife: 359
* [:octocat: xmltodict](https://github.com/martinblech/xmltodict) - Working with XML feel like you are working with JSON. :star: 1734 :fork_and_knife: 159

## Web Crawling

*Libraries for scraping websites.*

* [:earth_americas: Scrapy](http://scrapy.org/) - A fast high-level screen scraping and web crawling framework.
* [:octocat: cola](https://github.com/chineking/cola) - A distributed crawling framework. :star: 671 :fork_and_knife: 378
* [:octocat: Demiurge](https://github.com/matiasb/demiurge) - PyQuery-based scraping micro-framework. :star: 21 :fork_and_knife: 2
* [:earth_americas: feedparser](http://pythonhosted.org/feedparser/) - Universal feed parser.
* [:earth_americas: Grab](http://grablib.org/) - Site scraping framework.
* [:octocat: MechanicalSoup](https://github.com/hickford/MechanicalSoup) - A Python library for automating interaction with websites. :star: 1221 :fork_and_knife: 40
* [:octocat: portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy. :star: 3414 :fork_and_knife: 470
* [:octocat: pyspider](https://github.com/binux/pyspider) - A powerful spider system. :star: 5154 :fork_and_knife: 1196
* [:octocat: RoboBrowser](https://github.com/jmcarp/robobrowser) - A simple, Pythonic library for browsing the web without a standalone web browser. :star: 1068 :fork_and_knife: 78

## Web Content Extracting

*Libraries for extracting web contents.*

* [:octocat: Haul](https://github.com/vinta/Haul) - An Extensible Image Crawler. :star: 34 :fork_and_knife: 6
* [:octocat: html2text](https://github.com/Alir3z4/html2text) - Convert HTML to Markdown-formatted text. :star: 133 :fork_and_knife: 33
* [:octocat: lassie](https://github.com/michaelhelmick/lassie) - Web Content Retrieval for Humans. :star: 288 :fork_and_knife: 16
* [:octocat: micawber](https://github.com/coleifer/micawber) - A small library for extracting rich content from URLs. :star: 265 :fork_and_knife: 40
* [:octocat: newspaper](https://github.com/codelucas/newspaper) - News extraction, article extraction and content curation in Python. :star: 2518 :fork_and_knife: 314
* [:octocat: opengraph](https://github.com/erikriver/opengraph) - A Python module to parse the Open Graph Protocol :star: 57 :fork_and_knife: 35
* [:octocat: python-goose](https://github.com/grangier/python-goose) - HTML Content/Article Extractor. :star: 1562 :fork_and_knife: 352
* [:octocat: python-readability](https://github.com/buriy/python-readability) - Fast Python port of arc90's readability tool. :star: 737 :fork_and_knife: 156
* [:octocat: sanitize](https://github.com/Alir3z4/sanitize) - Bringing sanity to world of messed-up data. :star: 10 :fork_and_knife: 0
* [:octocat: sumy](https://github.com/miso-belica/sumy) - A module for automatic summarization of text documents and HTML pages. :star: 227 :fork_and_knife: 45
* [:octocat: textract](https://github.com/deanmalmgren/textract) - Extract text from any document, Word, PowerPoint, PDFs, etc. :star: 1605 :fork_and_knife: 124

## Forms

*Libraries for working with forms.*

* [:earth_americas: Deform](http://deform.readthedocs.org/) - Python HTML form generation library influenced by the formish form generation library.
* [:octocat: django-bootstrap3](https://github.com/dyve/django-bootstrap3) - Bootstrap 3 integration with Django. :star: 1105 :fork_and_knife: 346
* [:earth_americas: django-crispy-forms](http://django-crispy-forms.readthedocs.org/) - A Django app which lets you create beautiful forms in a very elegant and DRY way.
* [:octocat: django-remote-forms](https://github.com/WiserTogether/django-remote-forms) - A platform independent Django form serializer. :star: 135 :fork_and_knife: 59
* [:earth_americas: WTForms-JSON](http://wtforms-json.readthedocs.org/) - A WTForms extension for JSON data handling.
* [:earth_americas: WTForms](http://wtforms.readthedocs.org/) - A flexible forms validation and rendering library.

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

* [:earth_americas: Cerberus](http://python-cerberus.org) - A mappings-validator with a variety of rules, normalization-features and simple customization that uses a pythonic schema-definition.
* [:earth_americas: colander](http://docs.pylonsproject.org/projects/colander/) - A system for validating and deserializing data obtained via XML, JSON, an HTML form post or any other equally simple data serialization.
* [:octocat: kmatch](https://github.com/ambitioninc/kmatch) - A language for matching/validating/filtering Python dictionaries. :star: 35 :fork_and_knife: 4
* [:octocat: schema](https://github.com/halst/schema) - A library for validating Python data structures. :star: 630 :fork_and_knife: 56
* [:octocat: Schematics](https://github.com/schematics/schematics) - Data Structure Validation. :star: 1433 :fork_and_knife: 182
* [:octocat: valideer](https://github.com/podio/valideer) - Lightweight extensible data validation and adaptation library. :star: 143 :fork_and_knife: 7
* [:octocat: voluptuous](https://github.com/alecthomas/voluptuous) - A Python data validation library. It is primarily intended for validating data coming into Python as JSON, YAML, etc. :star: 452 :fork_and_knife: 72

## Anti-spam

*Libraries for fighting spam.*

* [:octocat: django-simple-captcha](https://github.com/mbi/django-simple-captcha) - A simple and highly customizable Django app to add captcha images to any Django form. :star: 304 :fork_and_knife: 134
* [:octocat: django-simple-spam-blocker](https://github.com/moqada/django-simple-spam-blocker) - Simple spam blocker for Django. :star: 4 :fork_and_knife: 0

## Tagging

*Libraries for tagging items.*

* [:octocat: django-taggit](https://github.com/alex/django-taggit) - Simple tagging for Django. :star: 1321 :fork_and_knife: 374

## Admin Panels

*Libraries for administrative interfaces.*

* [:octocat: Ajenti](https://github.com/Eugeny/ajenti) - The admin panel your servers deserve. :star: 54 :fork_and_knife: 12
* [:earth_americas: django-suit](http://djangosuit.com/) - Alternative Django Admin-Interface (free only for Non-commercial use).
* [:octocat: django-xadmin](https://github.com/sshwsfc/django-xadmin) - Drop-in replacement of Django admin comes with lots of goodies. :star: 1396 :fork_and_knife: 427
* [:octocat: flask-admin](https://github.com/mrjoes/flask-admin) - Simple and extensible administrative interface framework for Flask. :star: 18 :fork_and_knife: 5
* [:octocat: flower](https://github.com/mher/flower) - Real-time monitor and web admin for Celery. :star: 1381 :fork_and_knife: 248
* [:earth_americas: Grappelli](http://grappelliproject.com) – A jazzy skin for the Django Admin-Interface.
* [:octocat: Wooey](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts. :star: 472 :fork_and_knife: 25

## Static Site Generator

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [:earth_americas: Pelican](http://blog.getpelican.com/) - Uses Markdown or ReST for content and Jinja 2 for themes. Supports DVCS, Disqus. AGPL.
* [:earth_americas: Cactus](http://github.com/koenbok/Cactus/) – Static site generator for designers.
* [:earth_americas: Hyde](https://hyde.github.com/) - Jinja2-based static web site generator.
* [:earth_americas: Nikola](http://www.getnikola.com/) - A static website and blog generator.
* [:earth_americas: Tinkerer](http://tinkerer.me/) - Tinkerer is a blogging engine/.static website generator powered by Sphinx.

## Processes

*Libraries for starting and communicating with OS processes.*

* [:octocat: envoy](https://github.com/kennethreitz/envoy) - Python [subprocess](https://docs.python.org/2/library/subprocess.html) for Humans™. :star: 1555 :fork_and_knife: 101
* [:earth_americas: sarge](http://sarge.readthedocs.org/) - Yet another wrapper for subprocess.
* [:octocat: sh](https://github.com/amoffat/sh) - A full-fledged subprocess replacement for Python. :star: 3037 :fork_and_knife: 248

## Concurrency and Parallelism

*Libraries for concurrent and parallel execution.*

* [:earth_americas: multiprocessing](https://docs.python.org/2/library/multiprocessing.html) - (Python standard library) Process-based "threading" interface.
* [:earth_americas: threading](https://docs.python.org/2/library/threading.html) - (Python standard library) Higher-level threading interface.
* [:earth_americas: eventlet](http://eventlet.net/) - Asynchronous framework with WSGI support.
* [:octocat: gevent](http://www.gevent.org/) - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet). :star: 531 :fork_and_knife: 100
* [:octocat: Tomorrow](https://github.com/madisonmay/Tomorrow) - Magic decorator syntax for asynchronous code. :star: 894 :fork_and_knife: 41

## Networking

*Libraries for networking programming.*

* [:earth_americas: asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
* [:earth_americas: Tornado](http://www.tornadoweb.org/) - A Web framework and asynchronous networking library.
* [:earth_americas: Twisted](https://twistedmatrix.com/trac/) - An event-driven networking engine.
* [:octocat: pulsar](https://github.com/quantmind/pulsar) - Event-driven concurrent framework for Python. :star: 1116 :fork_and_knife: 61
* [:octocat: diesel](https://github.com/jamwt/diesel) - Greenlet-based event I/O Framework for Python. :star: 503 :fork_and_knife: 51
* [:earth_americas: pyzmq](http://zeromq.github.io/pyzmq/) - A Python wrapper for the ZeroMQ message library.
* [:octocat: txZMQ](https://github.com/smira/txZMQ) - Twisted based wrapper for the ZeroMQ message library. :star: 109 :fork_and_knife: 34

## WebSocket

*Libraries for working with WebSocket.*

* [:octocat: AutobahnPython](https://github.com/tavendo/AutobahnPython) - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html). :star: 865 :fork_and_knife: 278
* [:octocat: Crossbar](https://github.com/crossbario/crossbar/) - Open-source Unified Application Router (Websocket & WAMP for Python on Autobahn). :star: 690 :fork_and_knife: 82
* [:octocat: django-socketio](https://github.com/stephenmcd/django-socketio) - WebSockets for Django. :star: 784 :fork_and_knife: 147
* [:octocat: WebSocket-for-Python](https://github.com/Lawouach/WebSocket-for-Python) - WebSocket client and server library for Python 2 and 3 as well as PyPy. :star: 591 :fork_and_knife: 140

## WSGI Servers

*WSGI-compatible web servers.*

* [:earth_americas: gunicorn](http://pypi.python.org/pypi/gunicorn) - Pre-forked, partly written in C.
* [:earth_americas: uwsgi](https://uwsgi-docs.readthedocs.org/en/latest/) - A project aims at developing a full stack for building hosting services, written in C.
* [:earth_americas: bjoern](http://pypi.python.org/pypi/bjoern) - Asynchronous, very fast and written in C.
* [:earth_americas: fapws3](http://www.fapws.org/) - Asynchronous (network side only), written in C.
* [:earth_americas: meinheld](http://pypi.python.org/pypi/meinheld) - Asynchronous, partly written in C.
* [:octocat: netius](https://github.com/hivesolutions/netius) - Asynchronous, very fast. :star: 29 :fork_and_knife: 0
* [:earth_americas: paste](http://pythonpaste.org/) - Multi-threaded, stable, tried and tested.
* [:earth_americas: rocket](http://pypi.python.org/pypi/rocket) - Multi-threaded.
* [:earth_americas: waitress](https://waitress.readthedocs.org/) - Multi-threaded, poweres Pyramid.
* [:earth_americas: Werkzeug](http://werkzeug.pocoo.org/) - A WSGI utility library for Python that powers Flask and can easily be embedded into your own projects.

## RPC Servers

*RPC-compatible servers.*

* [:octocat: SimpleJSONRPCServer](https://github.com/joshmarshall/jsonrpclib/) - This library is an implementation of the JSON-RPC specification. :star: 225 :fork_and_knife: 89
* [:earth_americas: SimpleXMLRPCServer](https://docs.python.org/2/library/simplexmlrpcserver.html) - (Python standard library) Simple XML-RPC server implementation, single-threaded.
* [:octocat: zeroRPC](https://github.com/dotcloud/zerorpc-python) - zerorpc is a flexible RPC implementation based on [ZeroMQ](http://zeromq.org/) and [MessagePack](http://msgpack.org/). :star: 1524 :fork_and_knife: 169

## Cryptography

* [:earth_americas: cryptography](https://cryptography.io/) - A package designed to expose cryptographic primitives and recipes to Python developers.
* [:octocat: hashids](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python. :star: 320 :fork_and_knife: 31
* [:earth_americas: Paramiko](http://www.paramiko.org/) - A Python (2.6+, 3.3+) implementation of the SSHv2 protocol, providing both client and server functionality.
* [:earth_americas: Passlib](https://pythonhosted.org/passlib/) - Secure password storage/hashing library, very high level.
* [:earth_americas: PyCrypto](https://www.dlitz.net/software/pycrypto/) - The Python Cryptography Toolkit.
* [:octocat: PyNacl](https://github.com/pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library. :star: 225 :fork_and_knife: 44

## GUI

*Libraries for working with graphical user interface applications.*

* [:earth_americas: curses](https://docs.python.org/2/library/curses.html#module-curses) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.
* [:octocat: enaml](https://github.com/nucleic/enaml) - Creating beautiful user-interfaces with Declaratic Syntax like QML. :star: 402 :fork_and_knife: 53
* [:earth_americas: kivy](http://kivy.org/) - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
* [:earth_americas: pyglet](http://www.pyglet.org/) - A cross-platform windowing and multimedia library for Python.
* [:earth_americas: PyQt](http://www.riverbankcomputing.co.uk/software/pyqt/intro) - Python bindings for the [Qt](http://qt-project.org/) cross-platform application and UI framework, with support for both Qt v4 and Qt v5 frameworks.
* [:earth_americas: PySide](http://qt-project.org/wiki/pyside) - Python bindings for the [Qt](http://qt-project.org/) cross-platform application and UI framework, supporting the Qt v4 framework.
* [:earth_americas: Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter is Python's de-facto standard GUI package.
* [:octocat: Toga](https://github.com/pybee/toga) - A Python native, OS native GUI toolkit. :star: 676 :fork_and_knife: 44
* [:earth_americas: urwid](http://urwid.org/) - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
* [:earth_americas: wxPython](http://wxpython.org/) - A blending of the wxWidgets C++ class library with the Python.

## Game Development

*Awesome game development libraries.*

* [:earth_americas: Cocos2d](http://cocos2d.org/) - cocos2d is a framework for building 2D games, demos, and other graphical/interactive applications. It is based on pyglet.
* [:earth_americas: Panda3D](https://www.panda3d.org/) - 3D game engine developed by Disney and maintained by Carnegie Mellon's Entertainment Technology Center. Written in C++, completely wrapped in Python.
* [:earth_americas: Pygame](http://www.pygame.org/news.html) - Pygame is a set of Python modules designed for writing games.
* [:earth_americas: PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre) - Python bindings for the Ogre 3D render engine, can be used for games, simulations, anything 3D.
* [:earth_americas: PyOpenGL](http://pyopengl.sourceforge.net/) - Python ctypes bindings for OpenGL and it's related APIs.
* [:earth_americas: PySDL2](http://pysdl2.readthedocs.org/) - A ctypes based wrapper for the SDL2 library.
* [:earth_americas: PySFML](http://www.python-sfml.org/) - Python bindings for [SFML](http://www.sfml-dev.org/)
* [:earth_americas: RenPy](http://www.renpy.org/) - A Visual Novel engine.

## Logging

*Libraries for generating and working with logs.*

* [:earth_americas: logging](https://docs.python.org/2/library/logging.html) - (Python standard library) Logging facility for Python.
* [:earth_americas: logbook](http://pythonhosted.org/Logbook/) - Logging replacement for Python.
* [:earth_americas: Eliot](https://eliot.readthedocs.org/) - Logging for complex & distributed systems.
* [:earth_americas: Raven](http://raven.readthedocs.org/) - The Python client for Sentry.
* [:earth_americas: Sentry](https://pypi.python.org/pypi/sentry) - A realtime logging and aggregation server.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [:earth_americas: unittest](https://docs.python.org/2/library/unittest.html) - (Python standard library) Unit testing framework.
    * [:earth_americas: nose](https://nose.readthedocs.org/) - nose extends unittest.
    * [:octocat: contexts](https://github.com/benjamin-hodgson/Contexts) - A BDD framework for Python 3.3+. Inspired by C#'s `Machine.Specifications`. :star: 30 :fork_and_knife: 4
    * [:octocat: hypothesis](https://github.com/DRMacIver/hypothesis) - Hypothesis is an advanced Quickcheck style property based testing library. :star: 814 :fork_and_knife: 70
    * [:earth_americas: mamba](https://nestorsalceda.github.io/mamba) - The definitive testing tool for Python. Born under the banner of BDD.
    * [:octocat: PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI is a cross-platform GUI automation Python module for human beings. :star: 252 :fork_and_knife: 32
    * [:octocat: pyshould](https://github.com/drslump/pyshould) - Should style asserts based on [PyHamcrest](https://github.com/hamcrest/PyHamcrest). :star: 26 :fork_and_knife: 7
    * [:earth_americas: pytest](http://pytest.org/) - A mature full-featured Python testing tool.
    * [:earth_americas: pyvows](http://heynemann.github.io/pyvows/) - BDD style testing for Python. Inspired by [Vows.js](http://vowsjs.org/).
    * [:octocat: Robot Framework](https://github.com/robotframework/robotframework) - A generic test automation framework. :star: 565 :fork_and_knife: 214
* Web Testing
    * [:earth_americas: Selenium](https://pypi.python.org/pypi/selenium) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
    * [:octocat: locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python. :star: 2725 :fork_and_knife: 342
    * [:octocat: sixpack](https://github.com/seatgeek/sixpack) - A language-agnostic A/B Testing framework. :star: 915 :fork_and_knife: 84
    * [:earth_americas: splinter](https://splinter.readthedocs.org/en/latest/) - Open source tool for testing web applications.
* Mock
    * [:earth_americas: mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
    * [:earth_americas: doublex](https://pypi.python.org/pypi/doublex) - Powerful test doubles framework for Python.
    * [:octocat: freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module. :star: 552 :fork_and_knife: 54
    * [:octocat: httmock](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+. :star: 215 :fork_and_knife: 21
    * [:earth_americas: httpretty](http://falcao.it/HTTPretty/) - HTTP request mock tool for Python.
    * [:octocat: responses](https://github.com/dropbox/responses) - A utility library for mocking out the requests Python library. :star: 1044 :fork_and_knife: 77
    * [:octocat: VCR.py](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests. :star: 496 :fork_and_knife: 75
* Object Factories
    * [:octocat: factory_boy](https://github.com/rbarrois/factory_boy) - A test fixtures replacement for Python. :star: 746 :fork_and_knife: 110
    * [:octocat: mixer](https://github.com/klen/mixer) - Another fixtures replacement. Supported Django, Flask, SQLAlchemy, Peewee and etc. :star: 255 :fork_and_knife: 27
    * [:octocat: model_mommy](https://github.com/vandersonmota/model_mommy) - Creating random fixtures for testing in Django. :star: 517 :fork_and_knife: 115
* Code Coverage
    * [:earth_americas: coverage](https://pypi.python.org/pypi/coverage) - Code coverage measurement.
* Fake Data
    * [:earth_americas: faker](http://www.joke2k.net/faker/) - A Python package that generates fake data.
    * [:octocat: fake2db](https://github.com/emirozer/fake2db) - Fake database generator. :star: 1598 :fork_and_knife: 75
    * [:earth_americas: radar](https://pypi.python.org/pypi/radar) - Generate random datetime / time.
* Error Handler
    * [:octocat: FuckIt.py](https://github.com/ajalt/fuckitpy) - FuckIt.py uses state-of-the-art technology to make sure your Python code runs whether it has any right to or not. :star: 1808 :fork_and_knife: 65


## Code Analysis and Linter

*Libraries and tools for analysing, parsing and manipulation codebases.*

* Code Analysis
    * [:octocat: code2flow](https://github.com/scottrogowski/code2flow) - Turn your Python and JavaScript code into DOT flowcharts. :star: 181 :fork_and_knife: 21
    * [:octocat: pycallgraph](https://github.com/gak/pycallgraph) - A library that visualises the flow (call graph) of your Python application. :star: 502 :fork_and_knife: 85
    * [:octocat: pysonar2](https://github.com/yinwang0/pysonar2) - A type inferencer and indexer for Python. :star: 1720 :fork_and_knife: 440
* Linter
    * [:earth_americas: Flake8](https://pypi.python.org/pypi/flake8) - The modular source code checker: pep8, pyflakes and co.
    * [:earth_americas: Pylint](http://www.pylint.org/) - A source code analyzer.
    * [:earth_americas: pylama](https://pylama.readthedocs.org/) - Code audit tool for Python and JavaScript.

## Debugging Tools

*Libraries for debugging code.*

* Debugger
    * [:earth_americas: ipdb](https://pypi.python.org/pypi/ipdb) - IPython-enabled [pdb](https://docs.python.org/2/library/pdb.html).
    * [:earth_americas: pudb](https://pypi.python.org/pypi/pudb) – A full-screen, console-based Python debugger.
    * [:octocat: pyringe](https://github.com/google/pyringe) - Debugger capable of attaching to and injecting code into Python processes. :star: 1314 :fork_and_knife: 45
    * [:octocat: wdb](https://github.com/Kozea/wdb) - An improbable web debugger through WebSockets. :star: 758 :fork_and_knife: 38
    * [:earth_americas: winpdb](http://winpdb.org/) - A Platform Independent Python Debugger with GUI, capable of remote debugging based on rpdb2.
    * [:octocat: django-debug-toolbar](https://github.com/django-debug-toolbar/django-debug-toolbar) - Display various debug information about the current request/response. :star: 3278 :fork_and_knife: 625
    * [:octocat: django-devserver](https://github.com/dcramer/django-devserver) - A drop-in replacement for Django's runserver. :star: 1078 :fork_and_knife: 111
    * [:octocat: flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) - A port of the django-debug-toolbar to flask. :star: 383 :fork_and_knife: 68
* Profiler
    * [:octocat: line_profiler](https://github.com/rkern/line_profiler) - Line-by-line profiling. :star: 493 :fork_and_knife: 29
    * [:octocat: memory_profiler](https://github.com/fabianp/memory_profiler) - Monitor Memory usage of Python code. :star: 611 :fork_and_knife: 73
    * [:octocat: profiling](https://github.com/what-studio/profiling) - An interactive Python profiler. :star: 2256 :fork_and_knife: 69
* Others
    * [:octocat: pyelftools](https://github.com/eliben/pyelftools) - A pure-Python library for parsing and analyzing ELF files and DWARF debugging information. :star: 212 :fork_and_knife: 77
    * [:octocat: python-statsd](https://github.com/WoLpH/python-statsd) - Python Client for the [statsd](https://github.com/etsy/statsd/) server. :star: 75 :fork_and_knife: 32

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [:earth_americas: astropy](http://www.astropy.org/) - A community Python library for Astronomy.
* [:octocat: bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) - A toolkit providing best-practice pipelines for fully automated high throughput sequencing analysis. :star: 233 :fork_and_knife: 120
* [:octocat: bccb](https://github.com/chapmanb/bcbb) - Collection of useful code related to biological analysis. :star: 273 :fork_and_knife: 135
* [:earth_americas: Biopython](http://biopython.org/wiki/Main_Page) - Biopython is a set of freely available tools for biological computation.
* [:earth_americas: blaze](http://blaze.pydata.org/en/latest/) - NumPy and Pandas interface to Big Data.
* [:earth_americas: cclib](http://cclib.github.io/) - A library for parsing and interpreting the results of computational chemistry packages.
* [:earth_americas: NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [:earth_americas: Numba](http://numba.pydata.org/) - Python JIT (just in time) complier to LLVM aimed at scientific Python by the developers of Cython and NumPy.
* [:earth_americas: NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [:earth_americas: Open Babel](http://openbabel.org/wiki/Main_Page) - A chemical toolbox designed to speak the many languages of chemical data.
* [:octocat: Open Mining](https://github.com/avelino/mining) - Business Intelligence (BI) in Python (Pandas web interface) :star: 467 :fork_and_knife: 70
* [:earth_americas: orange](http://orange.biolab.si/) - Data mining, data visualization, analysis and machine learning through visual programming or Python scripting.
* [:earth_americas: Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [:earth_americas: PyDy](https://pydy.org/) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion based around NumPy, SciPy, IPython, and matplotlib.
* [:octocat: PyMC](https://github.com/pymc-devs/pymc3) - Markov Chain Monte Carlo sampling toolkit. :star: 1220 :fork_and_knife: 256
* [:earth_americas: RDKit](http://www.rdkit.org/) - Cheminformatics and Machine Learning Software.
* [:earth_americas: SciPy](http://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [:octocat: statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python. :star: 1125 :fork_and_knife: 490
* [:octocat: SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics. :star: 2341 :fork_and_knife: 1143
* [:octocat: zipline](https://github.com/quantopian/zipline) - A Pythonic algorithmic trading library. :star: 2549 :fork_and_knife: 690

## Data Visualization

*Libraries for visualizing data. See: [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [:earth_americas: matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [:octocat: bokeh](https://github.com/ContinuumIO/bokeh) - Interactive Web Plotting for Python. :star: 3240 :fork_and_knife: 578
* [:octocat: ggplot](https://github.com/yhat/ggplot) - Same API as ggplot2 for R. :star: 2267 :fork_and_knife: 276
* [:earth_americas: plotly](https://plot.ly/python) - Collaborative web plotting for Python and matplotlib.
* [:earth_americas: pygal](http://pygal.org/) - A Python SVG Charts Creator.
* [:earth_americas: pygraphviz](https://pypi.python.org/pypi/pygraphviz) - Python interface to [Graphviz](http://www.graphviz.org/).
* [:earth_americas: PyQtGraph](http://www.pyqtgraph.org/) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
* [:earth_americas: SnakeViz](https://jiffyclub.github.io/snakeviz) - A browser based graphical viewer for the output of Python's cProfile module.
* [:octocat: vincent](https://github.com/wrobstory/vincent) - A Python to Vega translator. :star: 1494 :fork_and_knife: 164
* [:earth_americas: VisPy](http://vispy.org/) - High-performance scientific visualization based on OpenGL.

## Computer Vision

*Libraries for computer vision.*

* [:earth_americas: OpenCV](http://opencv.org/) - Open Source Computer Vision Library.
* [:earth_americas: SimpleCV](http://simplecv.org/) - An open source framework for building computer vision applications.

## Machine Learning

*Libraries for Machine Learning. See: [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [:octocat: Crab](https://github.com/muricoca/crab) - A ﬂexible, fast recommender engine. :star: 560 :fork_and_knife: 207
* [:octocat: gensim](https://github.com/piskvorky/gensim) - Topic Modelling for Humans. :star: 1758 :fork_and_knife: 638
* [:octocat: hebel](https://github.com/hannes-brt/hebel) - GPU-Accelerated Deep Learning Library in Python. :star: 1100 :fork_and_knife: 95
* [:octocat: NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing. :star: 3430 :fork_and_knife: 919
* [:octocat: pattern](https://github.com/clips/pattern) - Web mining module for Python. :star: 3564 :fork_and_knife: 548
* [:octocat: PyBrain](https://github.com/pybrain/pybrain) - Another Python Machine Learning Library. :star: 1411 :fork_and_knife: 441
* [:octocat: Pylearn2](https://github.com/lisa-lab/pylearn2) - A Machine Learning library based on [Theano](https://github.com/Theano/Theano). :star: 1751 :fork_and_knife: 695
* [:octocat: python-recsys](https://github.com/ocelma/python-recsys) - A Python library for implementing a Recommender System. :star: 445 :fork_and_knife: 191
* [:earth_americas: scikit-learn](http://scikit-learn.org/) - A Python module for machine learning built on top of SciPy.
* [:octocat: vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) - A lightweight Python wrapper for [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/). :star: 107 :fork_and_knife: 27

## MapReduce

*Framworks and libraries for MapReduce.*

* [:octocat: dpark](https://github.com/douban/dpark) - Python clone of Spark, a MapReduce alike framework in Python. :star: 1457 :fork_and_knife: 344
* [:octocat: dumbo](https://github.com/klbostee/dumbo) - Python module that allows one to easily write and run Hadoop programs. :star: 952 :fork_and_knife: 153
* [:octocat: luigi](https://github.com/spotify/luigi) - A module that helps you build complex pipelines of batch jobs. :star: 3172 :fork_and_knife: 570
* [:octocat: mrjob](https://github.com/Yelp/mrjob) - Run MapReduce jobs on Hadoop or Amazon Web Services. :star: 1522 :fork_and_knife: 394
* [:earth_americas: PySpark](http://spark.apache.org/docs/latest/programming-guide.html) - The Spark Python API.
* [:octocat: streamparse](https://github.com/Parsely/streamparse) - Run Python code against real-time streams of data. Integrates with [Apache Storm](https://storm.incubator.apache.org/). :star: 835 :fork_and_knife: 99

## Functional Programming

*Functional Programming with Python.*

* [:octocat: CyToolz](https://github.com/pytoolz/cytoolz/) - Cython implementation of Toolz: High performance functional utilities. :star: 201 :fork_and_knife: 16
* [:octocat: fn.py](https://github.com/kachayev/fn.py) - Functional programming in Python: implementation of missing features to enjoy FP. :star: 1672 :fork_and_knife: 94
* [:octocat: funcy](https://github.com/Suor/funcy) - A fancy and practical functional tools. :star: 1186 :fork_and_knife: 60
* [:octocat: Toolz](https://github.com/pytoolz/toolz) - A collection of functional utilities for iterators, functions, and dictionaries. :star: 860 :fork_and_knife: 69

## Third-party APIs

*Libraries for accessing third party services APIs. See: [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers).*

* [:earth_americas: apache-libcloud](https://libcloud.apache.org/) - One Python library for all clouds.
* [:octocat: boto](https://github.com/boto/boto) - Python interface to Amazon Web Services. :star: 5124 :fork_and_knife: 1849
* [:octocat: django-wordpress](https://github.com/sunlightlabs/django-wordpress/) - WordPress models and views for Django. :star: 191 :fork_and_knife: 41
* [:octocat: facebook-sdk](https://github.com/pythonforfacebook/facebook-sdk) - Facebook Platform Python SDK. :star: 1454 :fork_and_knife: 530
* [:octocat: facepy](https://github.com/jgorset/facepy) - Facepy makes it really easy to interact with Facebook's Graph API :star: 387 :fork_and_knife: 117
* [:octocat: gmail](https://github.com/charlierguo/gmail) - A Pythonic interface for Gmail. :star: 1141 :fork_and_knife: 177
* [:octocat: google-api-python-client](https://github.com/google/google-api-python-client) - Google APIs Client Library for Python. :star: 597 :fork_and_knife: 228
* [:octocat: gspread](https://github.com/burnash/gspread) - Google Spreadsheets Python API. :star: 1280 :fork_and_knife: 249
* [:octocat: twython](https://github.com/ryanmcgrath/twython) - A Python wrapper for the Twitter API. :star: 1043 :fork_and_knife: 273

## DevOps Tools

*Software and libraries for DevOps.*

* [:octocat: Ansible](https://github.com/ansible/ansible) - A radically simple IT automation platform. :star: 12749 :fork_and_knife: 3794
* [:octocat: SaltStack](https://github.com/saltstack/salt) - Infrastructure automation and management system. :star: 5659 :fork_and_knife: 2409
* [:earth_americas: Fabric](http://www.fabfile.org/) - A simple, Pythonic tool for remote execution and deployment.
* [:octocat: cuisine](https://github.com/sebastien/cuisine) - Chef-like functionality for Fabric. :star: 1118 :fork_and_knife: 139
* [:earth_americas: Docker Compose](https://docs.docker.com/compose/) - Fast, isolated development environments using [Docker](https://www.docker.com/).
* [:octocat: Fabtools](https://github.com/ronnix/fabtools) - Tools for writing awesome Fabric files. :star: 875 :fork_and_knife: 180
* [:earth_americas: gitapi](http://bitbucket.org/haard/gitapi) - Pure-Python API for git.
* [:octocat: gunnery](https://github.com/gunnery/gunnery) - Multipurpose task execution tool for distributed systems with web-based interface. :star: 553 :fork_and_knife: 49
* [:earth_americas: hgapi](http://bitbucket.org/haard/hgapi) - Pure-Python API for Mercurial.
* [:octocat: honcho](https://github.com/nickstenning/honcho) - A Python port of [Foreman](https://github.com/ddollar/foreman), a tool for managing Procfile-based applications. :star: 646 :fork_and_knife: 74
* [:earth_americas: OpenStack](http://www.openstack.org/) - Open source software for building private and public clouds.
* [:octocat: pexpect](https://github.com/pexpect/pexpect) - Controlling interactive programs in a pseudo-terminal like GNU expect. :star: 403 :fork_and_knife: 116
* [:octocat: provy](https://github.com/python-provy/provy) - An easy-to-use provisioning system in Python. :star: 104 :fork_and_knife: 20
* [:octocat: psutil](https://github.com/giampaolo/psutil) - A cross-platform process and system utilities module. :star: 1013 :fork_and_knife: 159
* [:octocat: supervisor](https://github.com/Supervisor/supervisor) - Supervisor process control system for UNIX. :star: 1930 :fork_and_knife: 415

## Job Scheduler

*Libraries for scheduling jobs.*

* [:earth_americas: APScheduler](http://apscheduler.readthedocs.org/) - A light but powerful in-process task scheduler that lets you schedule functions.
* [:octocat: django-schedule](https://github.com/thauber/django-schedule) - A calendaring app for Django. :star: 600 :fork_and_knife: 248
* [:earth_americas: doit](http://pydoit.org/) - A task runner/build tool.
* [:earth_americas: Joblib](http://pythonhosted.org/joblib/index.html) - A set of tools to provide lightweight pipelining in Python.
* [:octocat: Plan](https://github.com/fengsp/plan) - Writing crontab file in Python like a charm. :star: 830 :fork_and_knife: 59
* [:octocat: schedule](https://github.com/dbader/schedule) - Python job scheduling for humans. :star: 1073 :fork_and_knife: 110
* [:octocat: Spiff](https://github.com/knipknap/SpiffWorkflow) - A powerful workflow engine implemented in pure Python. :star: 253 :fork_and_knife: 67
* [:earth_americas: TaskFlow](http://docs.openstack.org/developer/taskflow/) - A Python library that helps to make task execution easy, consistent and reliable.

## Foreign Function Interface

*Libraries for providing foreign function interface.*

* [:earth_americas: cffi](https://pypi.python.org/pypi/cffi) - Foreign Function Interface for Python calling C code.
* [:earth_americas: ctypes](https://docs.python.org/2/library/ctypes.html) - (Python standard library) Foreign Function Interface for Python calling C code.
* [:earth_americas: PyCUDA](http://mathema.tician.de/software/pycuda/) - A Python wrapper for Nvidia's CUDA API.
* [:earth_americas: SWIG](http://www.swig.org/Doc1.3/Python.html) - Simplified Wrapper and Interface Generator.

## High Performance

*Libraries for making Python faster.*

* [:earth_americas: Cython](http://cython.org/) - Optimizing Static Compiler for Python. Uses type mixins to compile Python into C or C++ modules resulting in large performance gains.
* [:earth_americas: PyPy](http://pypy.org/) - An implementation of Python in Python. The interpreter uses black magic to make Python very fast without having to add in additional type information.
* [:octocat: Pyston](https://github.com/dropbox/pyston) - A Python implementation built using LLVM and modern JIT techniques with the goal of achieving good performance. :star: 3134 :fork_and_knife: 221
* [:earth_americas: Stackless Python](http://www.stackless.com/) - An enhanced version of the Python.

## Microsoft Windows

*Python programming on Microsoft Windows.*

* [:earth_americas: Python(x,y)](https://code.google.com/p/pythonxy/) - Scientific-applications-oriented Python Distribution based on Qt and Spyder.
* [:earth_americas: pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/) - Unofficial Windows binaries for Python extension packages.
* [:octocat: PythonNet](https://github.com/pythonnet/pythonnet) - Python Integration with the .NET Common Language Runtime (CLR). :star: 87 :fork_and_knife: 42
* [:earth_americas: PyWin32](http://sourceforge.net/projects/pywin32/) - Python Extensions for Windows.
* [:earth_americas: WinPython](https://winpython.github.io/) - Portable development environment for Windows 7/8.

## Network Virtualization and SDN

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*

* [:earth_americas: Mininet](http://mininet.org/) - A popular network emulator and API written in Python.
* [:earth_americas: POX](http://www.noxrepo.org/pox/about-pox/) - An open source development platform for Python-based Software Defined Networking (SDN) control applications, such as OpenFlow SDN controllers.
* [:earth_americas: Pyretic](http://frenetic-lang.org/pyretic/) - A member of the Frenetic family of SDN programming languages that provides powerful abstractions over network switches or emulators.
* [:octocat: SDX Platform](https://github.com/sdn-ixp/internet2award) - SDN based IXP implementation that leverages Mininet, POX and Pyretic. :star: 6 :fork_and_knife: 3

## Hardware

*Libraries for programming with hardware.*

* [:earth_americas: ino](http://inotool.org/) - Command line toolkit for working with [Arduino](http://www.arduino.cc/).
* [:earth_americas: Pyro](http://pyrorobotics.com/) - Python Robotics.
* [:octocat: PyUserInput](https://github.com/SavinaRoja/PyUserInput) - A module for cross-platform control of the mouse and keyboard. :star: 312 :fork_and_knife: 64
* [:earth_americas: scapy](http://www.secdev.org/projects/scapy/) - A brilliant packet manipulation library.
* [:earth_americas: wifi](https://wifi.readthedocs.org/) - A Python library and command line tool for working with WiFi on Linux.

## Compatibility

*Libraries for migrating from Python 2 to 3.*

* [:earth_americas: Python-Future](http://python-future.org/index.html) - The missing compatibility layer between Python 2 and Python 3.
* [:octocat: Python-Modernize](https://github.com/mitsuhiko/python-modernize) - Modernizes Python code for eventual Python 3 migration. :star: 355 :fork_and_knife: 28
* [:earth_americas: Six](https://pypi.python.org/pypi/six) - Python 2 and 3 compatibility utilities.

## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [:octocat: blinker](https://github.com/jek/blinker) - A fast Python in-process signal/event dispatching system. :star: 229 :fork_and_knife: 25
* [:octocat: itsdangerous](https://github.com/mitsuhiko/itsdangerous) - Various helpers to pass trusted data to untrusted environments. :star: 739 :fork_and_knife: 65
* [:octocat: pluginbase](https://github.com/mitsuhiko/pluginbase) - A simple but flexible plugin system for Python. :star: 338 :fork_and_knife: 20
* [:octocat: Pychievements](https://github.com/PacketPerception/pychievements) - A framework for creating and tracking achievements. :star: 67 :fork_and_knife: 4

## Algorithms and Design Patterns

*Python implementation of algorithms and design patterns.*

* [:octocat: algorithms](https://github.com/nryoung/algorithms) - A module of algorithms for Python. :star: 1137 :fork_and_knife: 277
* [:octocat: python-patterns](https://github.com/faif/python-patterns) - A collection of design patterns in Python. :star: 6829 :fork_and_knife: 1597

## Editor Plugins

*Plugins for editors and IDEs.*

* Emacs
    * [:octocat: Elpy](https://github.com/jorgenschaefer/elpy) - Emacs Python Development Environment. :star: 532 :fork_and_knife: 80
* Sublime Text
    * [:octocat: SublimeJEDI](https://github.com/srusskih/SublimeJEDI) - A Sublime Text plugin to the awesome auto-complete library Jedi. :star: 535 :fork_and_knife: 60
    * [:octocat: Anaconda](https://github.com/DamnWidget/anaconda) - Anaconda turns your Sublime Text 3 in a full featured Python development IDE. :star: 831 :fork_and_knife: 81
* Vim
    * [:octocat: YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - Includes [Jedi](https://github.com/davidhalter/jedi)-based completion engine for Python. :star: 8532 :fork_and_knife: 976
    * [:octocat: Jedi-vim](https://github.com/davidhalter/jedi-vim) - Vim bindings for the Jedi auto-completion library for Python. :star: 1946 :fork_and_knife: 163
    * [:octocat: Python-mode](https://github.com/klen/python-mode) - An all in one plugin for turning Vim into a Python IDE. :star: 2634 :fork_and_knife: 546
* Visual Studio
    * [:octocat: PTVS](https://github.com/Microsoft/PTVS) - Python Tools for Visual Studio. :star: 556 :fork_and_knife: 123

## IDEs

*Popular Python IDEs.*

* [:earth_americas: PyCharm](https://www.jetbrains.com/pycharm/) - Commercial Python IDE by JetBrains. Has free community edition available.
* [:earth_americas: Komodo](http://komodoide.com/) - Commercial polyglot IDE with support for Python.
* [:earth_americas: LiClipse](http://www.liclipse.com/) - Free polyglot IDE based on Eclipse. Uses PyDev for Python support.
* [:octocat: Spyder](https://github.com/spyder-ide/spyder) - Open Source Python IDE. :star: 519 :fork_and_knife: 146
* [:earth_americas: WingIDE](http://wingide.com/) - Commercial IDE for Python.

# Services

Online tools and APIs to simplify development.

## Continuous Integration

*See: [awesome-CIandCD](https://github.com/ciandcd/awesome-ciandcd#online-build-system).*

* [:earth_americas: Travis CI](https://travis-ci.org) - A popular CI service for your open source and [private](https://travis-ci.com) projects. (GitHub only)
* [:earth_americas: CircleCI](https://circleci.com/) - A CI service that can run very fast parallel testing. (GitHub only)
* [:earth_americas: Vexor CI](https://vexor.io) - A continuous integration tool for private apps with pay-per-minute billing model.
* [:earth_americas: Wercker](http://wercker.com/) - A Docker-based platform for building and deploying applications and microservices.

## Code Quality

* [:earth_americas: Landscape](https://landscape.io/) - An early warning system for your Python codebase.
* [:earth_americas: QuantifiedCode](https://www.quantifiedcode.com/) - A data-driven, automated, continuous code review tool.

# Resources

Where to discover new Python libraries.

## Websites

* [:earth_americas: r/Python](http://www.reddit.com/r/python)
* [:earth_americas: CoolGithubProjects](http://coolgithubprojects.com/)
* [:earth_americas: Django Packages](https://www.djangopackages.com/)
* [:earth_americas: Full Stack Python](http://www.fullstackpython.com/)
* [:earth_americas: Python 3 Wall of Superpowers](http://python3wos.appspot.com/)
* [:earth_americas: Python Hackers](http://pythonhackers.com/open-source/)
* [:earth_americas: Python ZEEF](https://python.zeef.com/alan.richmond)
* [:octocat: Trending Python repositories on GitHub today](https://github.com/trending?l=python)

## Weekly

* [:earth_americas: Import Python Newsletter](http://importpython.com/newsletter/)
* [:earth_americas: Pycoder's Weekly](http://pycoders.com/)
* [:earth_americas: Python Weekly](http://www.pythonweekly.com/)

## Twitter

* [:earth_americas: @codetengu](https://twitter.com/codetengu)
* [:earth_americas: @getpy](https://twitter.com/getpy)
* [:earth_americas: @planetpython](https://twitter.com/planetpython)
* [:earth_americas: @pycoders](https://twitter.com/pycoders)
* [:earth_americas: @pypi](https://twitter.com/pypi)
* [:earth_americas: @pythontrending](https://twitter.com/pythontrending)
* [:earth_americas: @PythonWeekly](https://twitter.com/PythonWeekly)

# Other Awesome Lists

List of lists.

* Python
    * [:octocat: pycrumbs](https://github.com/kirang89/pycrumbs/blob/master/pycrumbs.md)
    * [:octocat: python-github-projects](https://github.com/checkcheckzz/python-github-projects) :star: 139 :fork_and_knife: 17
    * [:octocat: python_reference](https://github.com/rasbt/python_reference) :star: 1340 :fork_and_knife: 207
    * [:octocat: pythonidae](https://github.com/svaksha/pythonidae) :star: 248 :fork_and_knife: 47
* Monty
    * [:octocat: awesome](https://github.com/sindresorhus/awesome) :star: 18272 :fork_and_knife: 1883
    * [:octocat: lists](https://github.com/jnv/lists) :star: 3381 :fork_and_knife: 203

# [Contributing](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md)

Your contributions are always welcome!
