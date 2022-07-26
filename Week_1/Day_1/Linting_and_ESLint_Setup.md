### ESLint Setup

npm install -g eslint

ESLint is highly configurable. Different teams have different preferences. For example, at Lighthouse we prefer 2 spaces for indentation. Various other teams prefer 4 spaces.
Each team and/or project will tend to have its own ESLint config file, shared by all devs working on that team/project.
Lighthouse has its own ESLint file that we shall use.

curl -o .eslintrc.json https://gist.githubusercontent.com/kvirani/6cdb9511522d4357839718a050e7dd3b/raw/.eslintrc.json

### Running ESLint

eslint [options] file.js [file.js] [dir]

eslint app.js

or even:
eslint .  
(would run ESLint for all JS files in the current directory.)