# HTML
The default markup language is HTML5 polygot.

## Polyglot
If ever in any doubt, markup should be valid XML.

Attributes are always quoted.  The default quotes for attributes are double quotes.

Self closing tags should include the closing `/`.

## Doctype
The following doctype is used:

`<!DOCTYPE htm>`

[The HTML5 doctype is specified as case insensitive but using an upper case doctype declaration maintains compatibility with XML.]

## `<head>` ordering

 1. Charset
 1. JavaScript styling hook
 1. External CSS files
 1. External asynchronous JavaScript
 1. Prefetch declarations
 1. Viewport
 1. Inline CSS
 1. Title
 1. Meta elements

## Charset
The character set should be defined as UTF-8.  If using a `<meta>` tag then it should be the first child of the `<head>` to allow browsers to determine the character set as soon as possible to avoid having to re-parse the markup after a determination has been made.

The definition of the charset as a meta tag is: `<meta charset="utf-8"/>`

## Viewport
The following viewport is used: `<meta name="viewport" content="width=device-width,initial-scale=1"/>`


