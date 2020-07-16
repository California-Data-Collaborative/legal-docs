# legal-docs
Legal agreements used by the California Data Collaborative

### Editing
Editing should be done in markdown where possible to facilitate easy version control. 

After editing in markdown, [Pandoc](https://pandoc.org/) can be used to convert the markdown files to MS Word or PDF as needed. For example, the following command will generate a .docx file from a markdown file written using [Github Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

```bash
pandoc member_nda.md -f gfm -t docx -o member_nda.docx
```
