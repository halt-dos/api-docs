# Haltdos API Docs

Haltdos API Docs are created using Redocly API. 

### Prerequisites
- Node.js (16 or above)
- NPM
- API JSON / YAML based on OpenAPI 3 Standards


### Steps: 
1. Install Redocly CLI in your machine
```
npm i -g @redocly/cli@latest
```

2. Run the build-docs command, where you have placed the JSON/YAML file. Static HTML File (**index.html**) will be generated.
```
redocly build-docs filename.json -o index.html
```

3. Push the index.html to api-docs repository, and it will automatically get build and deployed to GitHub Pages.

