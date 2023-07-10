# Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch` 
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.


## APUNTES MIOS
### Tutorial principal
https://developers.sap.com/tutorials/cp-apm-nodejs-create-service.html
### Tests
http://localhost:4004/
http://localhost:4004/odata/v4/catalog/Authors
http://localhost:4004/odata/v4/catalog/Authors(101)?$expand=books($select=ID,title)
### Problemas para configurar la bd en modo db (archivo sqlite en lugar de memoria)
https://cap.cloud.sap/docs/guides/databases-sqlite
https://github.com/tiagobalmeida/sap-cloud-cap-cds-update-bug/blob/master/package.json
https://cap.cloud.sap/docs/advanced/troubleshooting#how-do-i-install-sqlite-on-windows
https://cap.cloud.sap/docs/releases/changelog/2020?q=no-save
https://blogs.sap.com/2021/04/25/cds-deploy-to-sqlite-in-memory-database/
https://stackoverflow.com/questions/56643837/cds-build-command-with-sap-cds-version-3-x-doesnt-place-csn-json-in-srv-mo
### Herramienta REST
https://vscode.dev/github/Huachao/vscode-restclient
