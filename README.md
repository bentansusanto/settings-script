# settings-script

## fixed error 0308010C:digital envelope routines::unsupported

add this script in package.json
"dev": "NODE_OPTIONS=--openssl-legacy-provider nuxt" // if using nuxt js
"dev": "NODE_OPTIONS=--openssl-legacy-provider next" // if using next js

https://codesandbox.io/s/custom-vuejs-select-component-8nqgd?file=/components/CustomSelect.vue

## setting tidy code 
add into settings.json
},
  "beautify.config": "",
  // "eslint.codeActionsOnSave.rules": null
  "eslint.workingDirectories": [{ "mode": "auto" }],
  // auto rapi
  "workbench.colorTheme": "Dracula Soft",
  "json.schemas": [],
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.wordWrap": "on",
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.organizeImports": true,
    "source.fixAll": true
  },
  
  // settingan nvm for node js
  1. Install nvm
  2. setting install node js versi 14.21.1 => nvm install 14.21.1
  3. use node js versi 14.21.1 => nvm use 14
  
 ##theme vs code 
 1. One Monokai Theme
 2. Material Icon Theme
 3. Eslint
 4. Quokka
 5. Vue Snippet
 6. Tailwindcss
 7. Prettier
 8. Beauify
 9. Auto Rename Tag
 10.EditorConfig VS Code
