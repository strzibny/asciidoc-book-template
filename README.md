# AsciiDoc Book Template

This is a simple technical book template to publish PDF and ePUB books, used to build books like [Kamal Handbook](https://kamalmanual.com/handbook/) and [Test Driving Rails](https://testdrivingrails.com).

## Features

This template focuses on basic features that are enough to produce a small technical book:

- Cover image
- Code blocks with syntax highlighting
- Images
- Notes
- Tables

## Install

Install Ruby and run `bundle install`:

```bash
$ bundle install
```

## Write

Write your book using [AsciiDoc](https://asciidoc.org) in `book.adoc`. The examples in the repository are tested with PDF and ePUB in mind. Not every feature of AsciiDoc is well supported in all formats.

Create a book cover and saved it as `cover.png`.

## Print

Print your digital book with Foreman:

```bash
$ foreman run print
```

Or print specifically for the format you want:

```bash
$ foreman run pdf
$ foreman run epub
```

The results will show up in `output/`.