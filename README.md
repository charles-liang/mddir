forked from https://github.com/JohnByrneRepo/mddir

Mddir generates a markdown file/folder structure for readme files

https://www.npmjs.com/package/mddir

Usage
node mddir "../relative/path/"

To install: npm install https://github.com/charles-liang/mddir -g

To generate markdown for current directory: mddir

To generate for any absolute path: mddir /absolute/path

To generate for a relative path: mddir ~/Documents/whatever.

The md file gets generated in your working directory.

Currently ignores node_modules, and .git folders.

Version
1.0.8

Todo's
Write Tests
Add Grunt task/wrapper
Read git ignore for folder ignore list
License
MIT

Example generated markdown file structure 'directoryList.md'
This output allows markdown to automatically generate lists and links
``` markdown
- me
  - [directoryList.md](directoryList.md)
  - [readme.md](readme.md)
    - 1
        - 1.1
            - 1.1.1
              - [my.md](1/1.1/1.1.1/my.md)
```