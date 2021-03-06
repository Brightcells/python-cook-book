# Summary

* [Introduction](README.md)
* [Book](Book/README.md)
* [Class](Class/README.md)
  * [MetaClass](Class/meta-class.md)
  * [Method Resolution Order(MRO)](Class/method_resolution_order.md)
  * Super
* [Codec](Codec/README.md)
* Command-line
  * argparse
  * [click — Click is a command line library for Python](http://click.pocoo.org/)
  * [docopt — Command-line interface description language](http://docopt.org/)
  * getopt
  * sys.argv
* [Compile](Compile/README.md)
  * Pyc
  * Pyd
  * Pyo
* [Data Types](DataTypes/README.md)
  * [Array](DataTypes/Array/README.md)
  * [Datetime](DataTypes/Datetime/README.md)
    * [ISO 8601](DataTypes/Datetime/ISO8601/README.md)
      * [Week](DataTypes/Datetime/ISO8601/Week.md)
    * [Strftime](DataTypes/Datetime/Strftime.md)
    * VS.
      * ``aware`` vs. ``navie``
      * ``CST`` vs. ``LMT``
      * ``STD`` vs. ``DST``
  * [Decimal](DataTypes/Decimal/README.md)
  * [Int](DataTypes/Int/README.md)
  * [List](DataTypes/List/README.md)
    * [Repeat Elements](DataTypes/List/repeat-elements.md)
    * [Count Not None](DataTypes/List/count-not-none.md)
  * [String](DataTypes/String/README.md)
    * [Modify Characters In String](DataTypes/String/modify-characters-in-string.md)
    * [Padding](DataTypes/String/padding.md)
    * [Remove Whitespace](DataTypes/String/remove-white-space.md)
    * [Split Every N Character](DataTypes/String/split-every-n-character.md)
    * [``+`` vs. ``join``](DataTypes/String/plus-vs-join.md)
    * [``%`` vs. ``format``](DataTypes/String/percent-sign-vs-format.md)
* [Debug](Debug/README.md)
  * [ipdb](Debug/ipdb.md)
* [Descriptor](Descriptor/README.md)
  * [``__get__``/``__set__``/``__delete__``](Descriptor/__get__-__set__-__delete__.md)
  * [Property](Descriptor/Property.md)
* [Extension](Extension/README.md)
  * [C](Extension/C/README.md)
    * CTypes
    * Cython
    * SWIG
    * [Python/C API](Extension/C/python-c-api.md)
* [File](File/README.md)
  * [Common](File/Common/README.md)
    * [Create File or Dir](File/Common/create-file-or-dir.md)
    * [Create Huge File](File/Common/create-huge-file.md)
    * [Delete File or Dir](File/Common/delete-file-or-dir.md)
  * [Format](File/Common/README.md)
    * CSV
    * EXCEL
    * XML
    * YAML
* [Function](Function/README.md)
  * [Built-in](Function/Built-in/README.md)
    * [next](Function/Built-in/next.md)
    * [setattr/getattr/hasattr](Function/Built-in/setattr-getattr-hasattr.md)
    * [zip](Function/Built-in/zip.md)
* [Generator](Generator/README.md)
  * [itertools](Generator/itertools/README.md)
    * [groupby](Generator/itertools/groupby.md)
    * permutations
    * combinations
  * [more_itertools — More routines for operating on iterables, beyond itertools](Generator/more_itertools.md)
  * [yield](Generator/yield.md)
* [Image](Image/README.md)
  * Data
    * Binary
    * Base64
  * Format
    * WebP
  * Function
    * Compression
    * Cropper
    * Thumbnail
    * Verification Code
* [Import](Import/README.md)
  * [``__all__``](Import/all.md)
  * [absolute_import](Import/absolute_import.md)
  * [Circular Imports](Import/circular-imports.md)
  * [Import From Parent Folder](Import/import-from-parent-folder.md)
  * [iSort Imports](Import/iSort-imports.md)
* [Interprocess Communication](InterprocessCommunication/README.md)
  * [Calling External Command](InterprocessCommunication/calling-external-command.md)
* [Lambda](Lambda/README.md)
* [Library](Library/README.md)
  * [3rd](Library/3rd/README.md)
    * [pandas — powerful Python data analysis toolkit](Library/3rd/pandas.md)
    * [versions — Software Version Comparison](Library/3rd/versions.md)
  * [Standard](Library/Standard/README.md)
    * [ConfigParser — Configuration file parser](Library/Standard/ConfigParser.md)
    * [Libs and cLibs](Library/Standard/libs-and-clibs.md)
    * [argparse — Parser for command-line options, arguments and sub-commands](Library/Standard/argparse.md)
    * [collections — High-performance container datatypes](Library/Standard/collections.md)
    * [copy — Shallow and deep copy operations](Library/Standard/copy.md)
    * [functools — Higher-order functions and operations on callable objects](Library/Standard/functools.md)
    * [itertools — Functions creating iterators for efficient looping](Library/Standard/itertools.md)
    * [json — JSON encoder and decoder](Library/Standard/json.md)
    * os.path — Common pathname manipulations
    * [operator — Standard operators as functions](Library/Standard/operator.md)
    * [shutil — High-level file operations](Library/Standard/shutil.md)
* [Magic Method](MagicMethod/README.md)
  * [Abstract Base Classes](MagicMethod/AbstractBaseClasses/README.md)
    * [``__get__``/``__set__``/``__delete__``](MagicMethod/AbstractBaseClasses/__get__-__set__-__delete__.md)
  * [Construction and Initialization](MagicMethod/ConstructionandInitialization/README.md)
    * [``__new__``/``__init__``/``__del__``](MagicMethod/ConstructionandInitialization/__new__-__init__-__del__.md)
* [Packaging](Packaging/README.md)
  * [Binary Eggs](Packaging/binary-eggs.md)
  * [Requirements.txt](Packaging/requirements.txt.md)
  * [Upload PyPI](Packaging/upload-pypi.md)
    * reStructuredText
* [Python3](Python3/README.md)
  * await/async
  * [Compatibility](Python3/Compatibility/README.md)
    * [``__future__`` — Future statement definitions](Python3/Compatibility/__future__.md)
    * [Compat](Python3/Compatibility/Compat.md)
    * [Future — Easy, clean, reliable Python 2/3 compatibility](Python3/Compatibility/Future.md)
    * [Six — a Python 2 and 3 compatibility library](Python3/Compatibility/Six.md)
  * [Hug](Python3/Hug.md)
* [Safety](Safety/README.md)
  * [eval](Safety/eval.md)
* [Serialization](Serialization/README.md)
  * [JSON](Serialization/JSON.md)
* [Socket](Socket/README.md)
  * [socket — Low-level networking interface](Socket/Socket.md)
* [Sort](Sort/README.md)
  * [Lambda](Sort/Lambda.md)
  * [Operator.itemgetter](Sort/Operator.itemgetter.md)
* [Style Guide](StyleGuide/README.md)
  * [PEP 8](StyleGuide/PEP8.md)
* [Syntax](Syntax/README.md)
  * [Dict Comprehensions](Syntax/dict-comprehensions.md)
  * [Generator Expressions](Syntax/generator-expressions.md)
  * [List Comprehensions](Syntax/list-comprehensions.md)
  * [Set Comprehensions](Syntax/set-comprehensions.md)
* [Test](Test/README.md)
  * Docstring
  * Nose2
  * Pytest
  * [Unittest](Test/unittest.md)
  * Tox
* [Workflow](Workflow/README.md)
  * [Pyenv — Simple Python version management](Workflow/Pyenv.md)
  * Pip — The PyPA recommended tool for installing Python packages
    * Pipfile — `Pipfile` and its sister `Pipfile.lock` are a replacement for the existing standard [pip](https://pip.pypa.io/en/stable/)'s `requirements.txt` file.
  * Virtualenv — Virtual Python Environment builder
  * [Pipenv — Sacred Marriage of Pipfile, Pip, & Virtualenv](Workflow/Pipenv.md)

# Appendix

* [PyPI](PyPI/README.md)
  * [Source](PyPI/source.md)
* [Why Ever](WhyEver/README.md)
  * [Single Element Tuple](WhyEver/single-element-tuple.md)
* [Idiom](Idiom/README.md)