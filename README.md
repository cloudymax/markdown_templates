# markdown to svg static webpage tool

converts a markdown readme file into a static webpage inside of a SVG.
allows you to use CSS and in-line html w/ markdown to make a full webpage.

Why? fun with github readmes, small file web pages, host a webpage from a blob storage bucket,
use an svg w/ css as a UI in unity engine.

WIP.

https://pragmaticpineapple.com/adding-custom-html-and-css-to-github-readme/

## flow

- original markdown file holds your notes/structure
- originla markdown gets converted to html
- css file makes the syle for the html
- Svg contains a foreign object with the style and html inside
- final readme.md contains the built svg
- svg can be served as a webpage


original_markdown.md -> original_markdown.html

final_readme {
svg {
    foreignobject{
        style.css,
        readme.html
    }
}
}
