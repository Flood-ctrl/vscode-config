{
    "workbench.activityBar.visible": true,
    "editor.renderWhitespace": "boundary",
    "editor.cursorStyle": "block",
    "editor.mouseWheelZoom": true,
    "window.newWindowDimensions": "maximized",
    "terminal.integrated.fontFamily": "Meslo LG S for Powerline",
    "editor.rulers": [
        79
    ],
    "files.autoSave": "afterDelay",
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
              "name": "Comment",
              "scope": [
                "comment",
                "comment.block",
                "comment.block.documentation",
                "comment.line",
                "comment.line.double-slash",
                "punctuation.definition.comment",
              ],
              "settings": {
                "fontStyle": "italic",
                "foreground": "#005c00",
                // "fontStyle": "italic",
                // "fontStyle": "italic underline",
                // "fontStyle": "italic bold underline",
              }
            },
          ]
    },
    "editor.minimap.enabled": false,
    "[bat]": {},
    "[yaml]": {},
    "workbench.startupEditor": "newUntitledFile",
    "editor.fontSize": 14,
    "files.associations": {
      "*.yml": "ansible",
      "playbook.yml": "ansible",
      "**/defaults/**/*": "ansible",
      "**/tasks/**/*.yml": "ansible",
      "**/handler/*.yml": "ansible",
      "**/*_vars/**/*.yml": "ansible",
      "**/roles/**/*.yml": "ansible",
      "**/playbooks/**/*.yml": "ansible",
      "**/*ansible*/**/*.yml": "ansible",
      "**/vars/**/*.yml": "ansible",
      "**/inventory/*/*": "ansible",
      "*.j2": "jinja"
    },
    "[ansible]": {},
    "workbench.iconTheme": "easy-icons",
    "atlascode.jira.workingSite": {
      "baseUrlSuffix": "atlassian.net"
    },
    "atlascode.showWelcomeOnInstall": false,
    "window.restoreFullscreen": true,
    "workbench.editor.tabCloseButton": "left",
    "extensions.ignoreRecommendations": false,
    "[python]": {
      "editor.defaultFormatter": "ms-python.python"
    },
    "ansible.autocompletion": false,
    "python.autoComplete.addBrackets": true,
    "python.pythonPath": "/usr/local/bin/python3",
    "editor.renderControlCharacters": false,
}
