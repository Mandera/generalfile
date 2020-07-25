# Package: generalfile
File manager for windows made by me.
An attempt to make the handling of windows files easier with intuitive and easy to use methods.

#### File
Every filetype has it's functionality bound to one class which File then inherits from.
This means that the only class you need is File, which contains all methods categorized by each filetype.
File class is never instantiated, all it's methods are classmethods.
Has a built-in race condition protection with automatic locks.

#### Path
Seperates relative and absolute filepaths, can convert from one to the other.
Allows easy concatenation of filepaths with built-in scrubbing for valid filepaths.
Can change for example filename with one simple method.
File can take either str or Path as filepaths as Path inherits str.

#### Disadvantage with structure
One current disadvantage is that the requirements list and package size grows with each added filetype.
So pandas is a requirement even though you won't be using tsv files for example.

## Installation
```
pip install generalfile
```

## Usage example
```python
from generalfile import File, Path


File.write("newfolder/test.txt", "foobar")  # Automatically creates new folder
assert File.read("newfolder/test.txt") == "foobar"
File.delete("newfolder")  # Delete entire folder

assert File.getWorkingDir() == Path().getAbsolute()
assert Path("C:/folder/test.txt").getPathWithoutFile() == "C:/folder"
assert Path("folder/test.txt").setFilenamePure("foobar") == "folder/foobar.txt"

File.openFolder("")  # Opens current working directory
```

## Todo
- Write more Todos
- Add csv support, inherit tsv's functionality somehow.
- File.move(path, destination)
- Possibly create a package for each filetype which can be pip installed seperately.