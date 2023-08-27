# Dev Container Configurations for VS Code

## Local Extensions

| Name                          | ID                                           |
|-------------------------------|----------------------------------------------|
| Remote Development            | ms-vscode-remote.vscode-remote-extensionpack |
| Better Comments               | aaron-bond.better-comments                   |
| Bookmarks                     | alefragnani.bookmarks                        |
| Docker                        | ms-azuretools.vscode-docker                  |
| EditorConfig for VS Code      | editorconfig.editorconfig                    |
| GitLens - Git supercharged    | eamodio.gitlens                              |
| Indent-rainbow                | oderwat.indent-rainbow                       |
| Todo Tree                     | aaron-bond.better-comments                   |
| Catppuccin for VSCode         | catppuccin.catppuccin-vsc                    |
| ---                           | ---                                          |
| advanced-new-file             | patbenatar.advanced-new-file                 |
| Code Spell Checker            | streetsidesoftware.code-spell-checker        |
| Error Lens                    | usernamehw.errorlens                         |
| File Utils                    | sleistner.vscode-fileutils                   |
| Inline Bookmarks              | tintinweb.vscode-inline-bookmarks            |
| Paste JSON as Code            | quicktype.quicktype                          |
| Project Manager               | alefragnani.project-manager                  |

## Podman

When using _podman_ instead of _docker_, change the following settings:

```json
{
    "dev.containers.dockerComposePath": "podman-compose",
    "dev.containers.dockerPath": "podman"
}
```

## My Settings

```json
{
    "diffEditor.ignoreTrimWhitespace": false,

    "editor.bracketPairColorization.enabled": true,
    "editor.defaultFormatter": "ms-python.black-formatter",
    "editor.fontFamily": "'JetBrains Mono', 'monospace', monospace",
    "editor.fontLigatures": true,
    "editor.formatOnSave": true,
    "editor.renderWhitespace": "boundary",
    "editor.rulers": [80, 120],
    "editor.stickyScroll.enabled": true,

    "files.trimTrailingWhitespace": true,

    "python.analysis.autoImportCompletions": true,
    "python.analysis.diagnosticMode": "workspace",
    "python.analysis.fixAll": ["source.unusedImports"],
    "python.analysis.typeCheckingMode": "basic",

    "redhat.telemetry.enabled": false,
    "workbench.colorTheme": "Catppuccin Mocha",
    "window.zoomLevel": 1,
}
```

## References

* <https://containers.dev/implementors/json_reference/>
