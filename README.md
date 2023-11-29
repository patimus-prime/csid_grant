Hello. This is the repo for the preliminary work I've done on CSID, including literature review and using a protein language model for variant effect prediction. The website this builds to is available [here](https://csidgrantproposal.netlify.app/grant.html). It is built using Quarto, basically Rmarkdown 2.0, which enables the integration of scientific manuscript writing with relevant computation.


To reproduce and run this yourself:
Get Python (3.1 is fine it'll run) and [Quarto](https://quarto.org/) first and install; Quarto is system-level and distributed as a .deb etc. Then, come in here and run 

```bash
pip install -r requirements.txt
```
Poetry not convenient to use here since Quarto requires VSCode extension to easily use, so pip employed instead.


Can then use the VSCode extension Quarto, preview button. And then to be able to neatly distribute this, a few options; I've chosen git to house the repo and CI/CD and deploy with Netlify. This demands quarto output as a website, which is what _quarto.yml is specifying. The .csl's are for citation style in the document. Citations available in .bib and organized using Zotero.

