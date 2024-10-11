### HTML tutorial

HTML stands for Hyper Text Markup Language. The code describes the structure of a web page using elements. The goal is to make the default, page, and post templates on _layouts to use.

- `<!DOCTYPE html>` decalaration
- `<html>` element is the root element of the page. Specify language, etc. `<html lang="{{ page.lang | default: site.lang | default: "en" }}">` sets language variable `page.lang`, and default to variable `site.lang`.
- `{% include head.html %}` includes the head.html file
- `<body>` is the element that defines the document's body.
- `<a>` tag defines a hyperlink
- `<img>` tag used to imbed image
- `<!-- Write comments like this -->`
- 