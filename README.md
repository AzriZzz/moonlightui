# MoonbladeUI

A simple React component library to help you developing apps faster and more productive. Build with TSDX that
helps to develop React component libraries more realiable and faster without thinking other stuff to setup 
such as Rollup, PostCSS, and ...etc

### Run the project with Storybook
```bash
yarn storybook
```
This loads the stories from `./stories`.

You can visit this <a href='' target='_blank'>Link</a> to open the storybook.

### Unit test
```bash
yarn test

```
This will run unit test inside the folder test


#### Setup Files

Folder structure :

```txt
/example
  index.html
  index.tsx       # test the component here in a demo app
  package.json
  tsconfig.json
/src
  index.tsx       # To import our component to be used during library deployment and the places we develop our component
/test
  blah.test.tsx   # Unit test folder 
/stories
  Thing.stories.tsx # Stories for the component
/.storybook
  main.js
  preview.js
.gitignore
package.json
README.md         # README OBVIOUSLY
tsconfig.json
```
