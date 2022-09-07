# seekr
A tool for finding and pages that contain words or phrases in the DOM.

## Overview

seekr is a tool for finding and pages that contain words or phrases in the DOM. 
It is a command line tool that takes a list of words or phrases in a file, and
traverses pages in search of those terms in the DOM. There is a feature that
will expand each word in the list to its additions, subtractions, substitutions,
and transpositions, and search for those as well. The tool will output a list of
pages that contain the terms.

seekr is currently wired to the Internet Computer as its source of pages to
search. It can be easily modified to search other sources.

## Requirements

seekr requires node.js and npm.

## Installation

```bash
npm install seekr
```

## Usage

```bash
npm run exec -- seek -d -e
```

## TODO
- [ ] Add other sources of pages to search
- [ ] Add tests