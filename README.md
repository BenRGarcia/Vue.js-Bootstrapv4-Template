# Vue.js CLI webpack template + Bootstrap v4

(Last updated 2/16/2018)

> A Vue.js template made with [Vue.js' CLI webpack template](https://vuejs.org/v2/guide/installation.html#CLI), integrated with Bootstrap v4

Inspiration for making this template comes from [here](https://github.com/BenRGarcia/Vue-CLI-Notes)

## Use this template **if**:

1. You want to use Vue.js' CLI webpack template with Bootstrap v4 ready to go
2. You think that it would be neat to be able to automagically create/deploy  
your production build to GitHub pages (`gh-pages` branch) with a simple command:  
`$ npm run deploy`

## To-Do's after you clone repo:

1. in root directory, run:
`$ npm install`

2. `$ git init`  
  `$ git add .`  
  `$ git commit -m "Initial commit"`  
  `$ git remote add origin <github repo link here>`  
  `$ git push -u origin master`

3. in root directory's `package.json`:

  * update `"name"`, `"description"`, `"author"`, etc. to your info

  * find the `"deploy"` script, scroll waaaaay to the right, add your github repo link there, too

4. `$ npm run deploy` to automatically create a `gh-pages` branch, which GitHub will automatically 
set as your default GitHub page

5. You may want to consider `$ npm outdated` and/or `$ npm update` for package updates after the creation of this template