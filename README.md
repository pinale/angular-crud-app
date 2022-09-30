template project: 
https://www.itsolutionstuff.com/post/angular-13-crud-application-example-tutorialexample.html

deploy and angular project to github pages:
https://medium.com/tech-insights/how-to-deploy-angular-apps-to-github-pages-gh-pages-896c4e10f9b4




method 2

git branch gh-pages
git checkout gh-pages
git push origin gh-pages
npm install -g angular-cli-ghpages
ng build --prod --base-href https://[username].github.io/[repo]/
ng build --prod --base-href https://pinale.github.io/angular-crud-app/
ngh --dir=dist/[project-name]
ngh --dir=dist/angular-crud-app

pubblicato a questo url
https://pinale.github.io/angular-crud-app/

