#### Extensões utilizadas / Used extensions:

* Auto Import
* Bracket Pair Color DLW
* Code Time
* Color Highlight
* Color Picker
* DotENV
* EditorConfig for VSCode
* Error Lens
* ES7+ React/Redux/React-Native snippets
* ESLint
* Live Server
* Live Share
* Material Icon Theme
* Material-UI Snippets
* Prettier
* Pretty TypeScript Errors
* Python
* Reload
* SVG
* Tabnine AI
* Tailwind CSS IntelliSense
* Tailwind Shades
* vscode-styled-components

#### Tema / Theme:
* Omni Black


#### Settings.json (VSCode)
```json
{
  // Emmet settings
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  
  // Workbench settings
  "workbench.startupEditor": "newUntitledFile",
  "workbench.colorTheme": "Omni Black",
  "workbench.editor.labelFormat": "short",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.editor.untitled.hint": "hidden",

  // Editor settings
  "editor.fontSize": 18,
  "editor.parameterHints.enabled": false,
  "editor.renderLineHighlight": "gutter",
  "editor.lineHeight": 34,
  "editor.fontLigatures": true,
  "editor.suggestSelection": "first",
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.semanticHighlighting.enabled": false,
  "editor.tabSize": 2,
  "editor.accessibilitySupport": "off",
  "editor.fontFamily": "Cascadia Code",
  "editor.fontWeight": "normal",
  "editor.language.colorizedBracketPairs": [
    ["[", "]"],
    ["(", ")"],
    ["{", "}"],
    ["<", "</"],
    ["<", "/>"]
  ],

  // File associations
  "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    "*.tsx": "typescriptreact",
    ".env.*": "dotenv",
    ".prettierrc": "json"
  },
  "material-icon-theme.languages.associations": {
    "dotenv": "tune"
  },
  "material-icon-theme.files.associations": {
    "tsconfig.json": "tune",
    "*.webpack.js": "webpack",
    "*.proto": "3d",
    "ormconfig.json": "database"
  },
  "files.exclude": {
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/.hg": true,
    "**/.svn": true,
    "**/.git": true
  },

  // Git settings
  "git.enableSmartCommit": true,
  "git.openRepositoryInParentFolders": "always",
  "git.autofetch": true,
  "git.confirmSync": false,

  // Terminal settings
  "terminal.integrated.showExitAlert": false,
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.env.osx": {
    "FIG_NEW_SESSION": "1"
  },

  // Extensions settings
  "extensions.ignoreRecommendations": true,
  "cSpell.userWords": [
    "chakra",
    "IUGU",
    "middlewares",
    "mixpanel",
    "Onboarded",
    "prefetch",
    "rocketseat",
    "upsert"
  ],
  "cSpell.enableFiletypes": [
    "!asciidoc",
    "!c",
    "!cpp",
    "!csharp",
    "!go",
    "!handlebars",
    "!haskell",
    "!jade",
    "!java",
    "!latex",
    "!php",
    "!pug",
    "!python",
    "!restructuredtext",
    "!rust",
    "!scala",
    "!scss"
  ],

  // Other settings
  "screencastMode.onlyKeyboardShortcuts": true,
  "liveshare.featureSet": "insiders",
  "CodeGPT.query.language": "Portuguese",
  "css.hover.documentation": false,
  "vscord.status.buttons.button1.enabled": false,
  "vscord.status.buttons.button1.git.active.enabled": false,
  "vscord.app.name": "Visual Studio Code",
  "prettier.semi": false,
  "prettier.singleQuote": true,
  "tabnine.experimentalAutoImports": true,
  "material-ui-snippets.showNotesOnStartup": false,
  "security.workspace.trust.untrustedFiles": "newWindow",
  
  // Language-specific settings for TypeScript, JavaScript, HTML, and JSON files
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // Settings specific to [prisma]
  "[prisma]": {
    "editor.formatOnSave": true
  },

  // JavaScript and TypeScript settings
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.tsserver.log": "off",
  "typescript.suggest.autoImports": true,
  "typescript.updateImportsOnFileMove.enabled": "never"
}

```
