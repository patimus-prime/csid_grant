Hello. Get Python (3.1 is fine it'll run) and Quarto first and install; Quarto is system-level and distributed as a .deb etc. Then, come in here and run 

```bash
pip install -r requirements.txt
```
Poetry not convenient to use here so yeah.

Can then use VSCode extension Quarto, preview button. And then to be able to neatly distribute this, a few options; I've chosen git to house the repo and CI/CD and deploy with Netlify. This demands quarto output as a website, which is what _quarto.yml is specifying.

