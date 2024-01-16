<!-- es-lint config working -->
//floow channel
https://www.youtube.com/watch?v=xinJSYiOB6Q
steps-----
after create project first check all list plugin if exist don't install
$ yarn add eslint --save-dev
///check eslink with in list or not
npm ls eslint
$ yarn add eslint-plugin-react --save-dev
/// check eslint-plugin-react in list or not
npm ls eslint-plugin-react
//check eslintplugin-react-hooks
$ yarn ls eslint

///create new file name .eslintrc.json
past the configration from json file eslintconfig
{
"extend":[
    "react-app",
    "react-app/jest",
    "prettier"          //add after eslint-config-prettier --save -dev step
    ]
    }

now add pritter install
$ yarn add prettier --save-dev --save-exact
create .prettierrc.json file empty
create .prettierignore file also add 
    /node_module

$ yarn add eslint-config-prettier --save-dev
    add pritter in .eslintrc.json file
    "prettier"
npx prettier --write .

//check rules work or not
add rules in eslintrc json file