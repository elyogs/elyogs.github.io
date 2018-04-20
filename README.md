Visit my CV online @ [https://elyogs.github.io/resume](https://elyogs.github.io/resume)

# Markdown to HTML with [Pandoc](https://pandoc.org)

```
$ pandoc --standalone --quiet -c style.css -o resume.html resume.md
```

# HTML to PDF with [WKhtmlToPDF](https://wkhtmltopdf.org)

```
$ wkhtmltopdf -L 20mm -R 20mm resume.html resume.pdf
```
