# settings-script

## fixed error 0308010C:digital envelope routines::unsupported

add this script in package.json
"dev": "NODE_OPTIONS=--openssl-legacy-provider nuxt" // if using nuxt js
"dev": "NODE_OPTIONS=--openssl-legacy-provider next" // if using next js

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
