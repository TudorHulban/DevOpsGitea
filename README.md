# DevOpsGitea
Concentrating Devops knowledge with Gitea CI / CD.

## Default theme customization
Concentrate CSS style in `styles.css` file. Place this file in `custom/public` folder. If using Docker volume place the file in `data/custom/public` (given volume root in data).<br/>
Create `header.tmpl` as below and place it in `custom/templates/custom/header.tmpl`.
```html
<link rel="stylesheet" href="{{AppSubUrl}}/styles.css">
```

## Resources
```html
https://dev.to/ruanbekker/self-hosted-cicd-with-gitea-and-drone-ci-200l
https://docs.gitea.io/en-us/customizing-gitea/#example-plantuml
```
