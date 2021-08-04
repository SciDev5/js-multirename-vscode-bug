This is a repo created to demonstrate a bug in VSCode from this issue: https://github.com/microsoft/vscode/issues/130067

When file2 and file3 are moved together, file1 and file2 update, but file3 remains untouched and other files do not update their refrences to it.