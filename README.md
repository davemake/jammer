# JAMMER!

Create heavy metal fast enough to jam!

# Termius..........

## Build JAMMER

$ cd jammer

$ git clone https://github.com/davemake/jammer.git .

$ git checkout -b <branch-name>

(BUILD!)

$ git add --all && git commit -m "memo...."

$ nvm install 7

$ npm i koa

$ node index.js

# Dial VISUAL STUDIO CODE

$ mkdir .jscode && cd .jscode

$ git clone https://github.com/davemake/jscode_launch.git .

$ git clone https://github.com/davemake/jscode_settings.git .

.jscode

launch.json

  {
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [{
      "type": "node",
      "request": "launch",
      "name": "Launch Program",
      "skipFiles": [
        "<node_internals>/**"
      ],
      "program": "${workspaceFolder}/index.js"
    }]
  }

settings.json

  {
    "editor.tabSize": 2,
    "editor.parameterHints.enabled": false,
    "[json]": {

      "editor.quickSuggestions": {
        "strings": true
      },
      "editor.suggest.insertMode": "replace"
    },
    "editor.quickSuggestionsDelay": 3000,
    "editor.hover.enabled": false,
    "editor.hover.sticky": false,
    "window.zoomLevel": -1,
    "editor.mouseWheelZoom": true
  }
