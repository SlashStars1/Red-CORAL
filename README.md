# Red CORAL

Interactive map of organized crime in South America.

[Production Site](https://redcoralmap.web.app)
[QA Site](https://red-coral-map.web.app/)

## Details

See the [Google Drive Folder](https://drive.google.com/drive/folders/1U2VPsuXm2Jfzjbf39y73rK3O6BKxV4Jy) for details. The Architecture document is most relevant.

Analytics for the web app can be viewed at https://net.tsuni.dev/redcoralmap.web.app.

## Contributing

Assign an issue to yourself, or work on one that has been assigned to you by cloning this repository, creating a new branch, pushing your changes, and creating a pull request into main. You'll get a preview link on the PR linked to the QA environment. Once you recieve an approval, feel free to merge into main! This will build deploy your code to production.

## Running Locally

First, make sure you have [Node.js](https://nodejs.org/) installed and you've made a .env file in the root of the project with contents from the Secrets doc (QA environment) in the Drive folder. Then it's as easy as running:

```bash
npm i && npm run dev
```