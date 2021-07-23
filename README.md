# baseless.bingo
All of the bingo, none of the research. Baseless bingo is a bingo sheet randomiser for the podcast Baseless Speculation built with Jekyll and Pure CSS for minimal web bloat.

## Installation

## Contribution
New episode of Baseless Speculation with new potential bingo sheets come out weekly. You can add any missing bingo sheets by forking this repo and submitting a pull request with your new sheet randomiser. All sheets are placed in "src/_posts" and are formated in markdown with YAML headers.

The sheet randomisers are formatted as follows:
```Markdown
---
title: "Movie Title"
layout: bingo
eplink: Link to BS episode
freesq: free center square
squares:
    - Each
    - other
    - bingo
    - square
---
Description of movie (can just be taken from IMDB).
```
A full sheet requires 24 squares and 1 free square.