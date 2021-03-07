# Alloy 4 KDE-style XML syntax definition

This is an [Alloy 4](http://alloytools.org) [KDE-style XML definition](https://docs.kde.org/stable5/en/applications/katepart/highlight.html) that I use 
with [pandoc](http://pandoc.org) to get syntax highlighting for alloy code blocks.

## Usage

```shell
$ pandoc --syntax-definition alloy.xml file.md -o file.pdf
```

## Contributing

This is my first syntax definition. It works for me, i.e. provides results
good enough for my lectures.

I make it available to save time for people with the same needs.

It should ultimately be added in the [KDE repository of syntax definitions](https://github.com/KDE/syntax-highlighting/tree/master/data/syntax) to be useful (i.e. to allow tools to support that language out of the box).

This requires quite some work in terms of testing and integration in the full framework, much more than the time I spent to write this definition file.

Please feel free to do contribute to make it happen.
