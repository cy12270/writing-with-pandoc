# Academic writing with pandoc

1. Install pandoc.
2. run this command to convert the markdown file to a cited docx file:
  ```shell
  pandoc --cite --bibliography=sample_citation.bib sample_text.md -o cited_sample_text.docx
  ```
