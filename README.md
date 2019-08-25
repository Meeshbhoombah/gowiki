# gowiki
Follows ["Writing Web Applications" tutorial](https://golang.org/doc/articles/wiki/).

**Table of Contents**
- Data Structures
- Introducing the net/http package 
- Using net/http to serve wiki pages
- Editing Pages
- The html/template package
- Handling non-existent pages
- Saving Pages
- Error handling
- Template caching
- Validation
- Introducing Function Literals and Closures

## Structure
```
.
├── README.md
├── edit.html
├── view.html
└── wiki.go
```

Files ending in `.html` are templates, `wiki.go` contains main logic for the 
Wiki.

