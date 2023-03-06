# web-app-ig-v1.0

-> Clone Instagram WebApp

# Dependencies & Plugins

-> Vite (React, TS) ### npm create vite@latest
|
-> npm i
======
-> Eslint ### npm i -D eslint
|
-> npx eslint --init
-> Air bnb plugin ### npx install-peerdeps --dev eslint-config-airbnb
-> Fix extend ### "extends": ["airbnb", "airbnb/hooks"]
-> Plugin for TS
|
-> npm i -D eslint-config-airbnb-typescript
-> "extends" : ["airbnb-typescript"]
-> Add parserObtion : project: './tsconfig.json'
-> Fix tsconfig.json : "include": [".eslintrc.cjs"]

-> Eslint Plugin Prettier
|
-> npm i -D prettier eslint-config-prettier eslint-plugin-prettier
-> Add .perttierrc.cjs file ### and Add config
-> Add plugin in eslintrc file : plugins: ['prettier']
-> Add "extends" : ["plugin:prettier/recommended"]
======
-> Testing with Vitest ### npm install -D vitest
-> fix vite.config
-> fix tsconfig to include vite.config
