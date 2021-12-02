# Codelabs demo

[Google Codelabs](https://github.com/googlecodelabs/tools) demo site.
Uses GitHub Pages to serve, Google Doc as a source.

## Prerequisites

- Codelabs command line tool, [claat](https://github.com/googlecodelabs/tools/tree/main/claat#install)
- Google Doc
- GitHub account and repo for public hosting

## Generate source

```shell
./claat export 1mPJoEbc-r5uPwT7xASusBkmBSfgaBrIhiaTL-_9ez9Q
```

Add to `gh-pages` branch.

## Serve

Configure GitHub to serve using the `gh-pages` branch.

## Notes

Can use either Google Doc or Markdown as a source: don´t try to use both!
