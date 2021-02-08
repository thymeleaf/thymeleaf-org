# Creation and maintenance of the CLA documents

## Creating the PDF files from markdown

First, the markdown files need to be converted to LibreOffice format with:

```
$ pandoc {file.markdown} -o {file.odt}
```

Then from LibreOffice, make sure the _Deja Vu_ font family is used for all the
texts and add some air between paragraphs. Font size for normal text is 10pt.

### Adding forms

Create the form fields as explained
in [this tutorial][pdf-form] but make sure the font for the form fields is
Arial (11pt).

When exporting to PDF, remember to set _changes_ to only
_"fill in form fields"_ first.


[pdf-form]: https://www.linuxuprising.com/2019/02/how-to-create-fillable-pdf-forms-with.html
