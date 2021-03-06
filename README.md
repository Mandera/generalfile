# generalfile 2.3.3
Easily manage files cross platform.

[![workflow Actions Status](https://github.com/ManderaGeneral/generalfile/workflows/workflow/badge.svg)](https://github.com/ManderaGeneral/generalfile/actions)
![GitHub last commit](https://img.shields.io/github/last-commit/ManderaGeneral/generalfile)
[![PyPI version shields.io](https://img.shields.io/pypi/v/generalfile.svg)](https://pypi.org/project/generalfile/)
[![PyPI pyversions](https://img.shields.io/pypi/pyversions/generalfile.svg)](https://pypi.python.org/pypi/generalfile/)
[![Generic badge](https://img.shields.io/badge/platforms-windows%20%7C%20ubuntu-blue.svg)](https://shields.io/)

## Contents
<pre>
<a href='#generalfile-2.3.3'>generalfile 2.3.3</a>
├─ <a href='#Contents'>Contents</a>
├─ <a href='#Installation'>Installation</a>
├─ <a href='#Attributes'>Attributes</a>
└─ <a href='#Todo'>Todo</a>
</pre>

## Installation
| Command                                | <a href='https://pypi.org/project/generallibrary'>generallibrary</a>   | <a href='https://pypi.org/project/send2trash'>send2trash</a>   | <a href='https://pypi.org/project/appdirs'>appdirs</a>   | <a href='https://pypi.org/project/pandas'>pandas</a>   |
|:---------------------------------------|:-----------------------------------------------------------------------|:---------------------------------------------------------------|:---------------------------------------------------------|:-------------------------------------------------------|
| `pip install generalfile`              | Yes                                                                    | Yes                                                            | Yes                                                      | No                                                     |
| `pip install generalfile[spreadsheet]` | Yes                                                                    | Yes                                                            | Yes                                                      | Yes                                                    |
| `pip install generalfile[full]`        | Yes                                                                    | Yes                                                            | Yes                                                      | Yes                                                    |

## Attributes
<pre>
<a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/__init__.py#L1'>Module: generalfile</a>
├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/errors.py#L4'>Class: CaseSensitivityError</a>
├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/errors.py#L5'>Class: InvalidCharacterError</a>
└─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path.py#L17'>Class: Path</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path.py#L17'>Class: Path</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L56'>Method: absolute</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_lock.py#L124'>Method: as_working_dir</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L11'>Method: copy</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L211'>Method: copy_to_folder</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L312'>Method: create_folder</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L35'>Method: delete</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L35'>Method: delete_folder_content</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L99'>Method: endswith</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L239'>Method: exists</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L29'>Method: get_alternative_path</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L329'>Method: get_cache_dir</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L337'>Method: get_lock_dir</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L39'>Method: get_lock_path</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path.py#L34'>Method: get_parent</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L45'>Method: get_path_from_alternative</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L11'>Method: get_paths_in_folder</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L11'>Method: get_paths_recursive</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L19'>Method: get_replaced_alternative_characters</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L345'>Method: get_working_dir</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L79'>Method: is_absolute</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L227'>Method: is_file</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L233'>Method: is_folder</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L85'>Method: is_relative</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_lock.py#L115'>Method: lock</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L219'>Method: move</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L153'>Method: name</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L322'>Method: open_folder</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L94'>Method: open_operation</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L147'>Method: parts</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L120'>Method: read</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L67'>Method: relative</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L123'>Method: remove_end</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L107'>Method: remove_start</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L11'>Method: rename</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L139'>Method: same_destination</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L11'>Method: seconds_since_creation</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L11'>Method: seconds_since_modified</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L365'>Method: set_working_dir</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L91'>Method: startswith</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L167'>Method: stem</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L195'>Method: suffix</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L234'>Method: suffixes</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L35'>Method: trash</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L35'>Method: trash_folder_content</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L181'>Method: true_stem</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path.py#L110'>Method: view</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L159'>Method: with_name</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L173'>Method: with_stem</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L201'>Method: with_suffix</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L240'>Method: with_suffixes</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_strings.py#L187'>Method: with_true_stem</a>
   ├─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L259'>Method: without_file</a>
   └─ <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_operations.py#L108'>Method: write</a>
</pre>

## Todo
| Module              | Message                                                                                     |
|:--------------------|:--------------------------------------------------------------------------------------------|
| path\_lock.py        | other\_paths                                                                                 |
| decorators.py       | Put this in library                                                                         |
| path.py             | Add a proper place for all variables, add working\_dir, sys.executable and sys.prefix to it. |
| path.py             | Raise suppressable warning if space in Path.                                                |
| path\_operations.py  | Can we not just change signature to rename(self, new\_path, overwrite=False) ?               |
| path\_operations.py  | Filter for Path.get\_paths\_* like we have in ObjInfo.                                        |
| path\_operations.py  | Add this error parameter for more methods                                                   |
| path\_spreadsheet.py | Make it order columns if there are any so that they line up with append.                    |
| path\_spreadsheet.py | Should probably support DataFrame and Series as well.                                       |

<sup>
Generated 2021-02-02 15:02 CET for commit <a href='https://github.com/ManderaGeneral/generalfile/commit/master'>master</a>.
</sup>
