The `BibTeX_ivotron.js` file is a modified version of the default 
translator that leaves out:

  - annote
  - note
  - comment
  - file
  - abstract
  - urldate
  - keywords

I use this translator along with [AutoZotBib].

I post-process the generated `.bib` file with 
`postprocess-zotero-bibtex`.

[AutoZotBib]: http://www.rtwilson.com/academic/autozotbib
