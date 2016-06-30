# Templates by ISTU guidelines

	СТО 005–2015
	СТАНДАРТ ОРГАНИЗАЦИИ
	СИСТЕМА МЕНЕДЖМЕНТА КАЧЕСТВА Учебно-методическая деятельность.
	Оформление курсовых проектов (работ) и выпускных квалификационных работ технических специальностей

There are two (yet) kinds of template: usual report and one for practice work. Difference in titles.

## Usage
1. Download ZIP or clone it to your computer
2. Rename needed title and info files. Fill your information in info.tex. Like name, group, teacher, etc.
3. Make report
4. Build with your favorite LaTeX-compiler
5. If table of content or bibliography didn't update compile one more time (it's not a bug it's a LaTeX feature)

## Features
### Page numbers
Page numbers start from second page (TOC).

### Chapter numbers
TOC, bibliography and appendixes doesn't numbering. Your own first chapter will have first number.

### Pictures
Defult path for your images "./pics". Change it if you want in "ISTU_practice.sty"

### Listings
There are two ways to include listings:

1. Built-in "listings"-package

	You can write your code in {lstlisting}-tag or include it by \lstinputlisting-command
	But this way doesn't support cyrillic-symbols
	And there's no complete style-set for languages

2. Stand-alone highlighter

	Recommended using [this one](http://www.andre-simon.de/doku/highlight/en/highlight.php)
	Xcode style included. Escape-characters included. You don't have to export style-file.

### Bibliography
Use BibTeX. You can use any editor or fill .bib-file manually.
But in bibs.tex you have to list all your items. That's a bug, but maybe it's my compiler.

### Tables
Longtable is supported. Header repeats on each page.

## Roadmap

- integrate gulp
