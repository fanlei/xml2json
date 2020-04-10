# xml2json

Command-line tool to convert XML to JSON

## Requirements

PHP needs to be a minimum version of PHP 7.0.0.

## Installation

Globally by using [Composer](https://getcomposer.org/):

```shell
$ composer global require codegear/xml2json
```

## Usage

### In Command-Line

Convert XML format data in file `data.xml` and output to screen:
```shell
$ xml2json data.xml
```
Convert XML format data in file `data.xml` and save to JSON file `data.json`:
```shell
$ xml2json data.xml > data.json
```
    
### In VIM

Format current file:
```viml
:%!xml2json %
```

or add a keymap in `vimrc`:
```viml
nnoremap <Leader>xj :%!xml2json %<CR>
```
