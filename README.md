# My personal VS Code settings and installed extensions

Get installed extensions and save to list in file:
```console
$ code --list-extensions | tee extensions.txt
adamhartford.vscode-base64
eriklynd.json-tools
flesler.url-encode
jacobx1.code-email-pocketknife
jamiewoodio.junos
mrmlnc.vscode-apache
redhat.vscode-yaml
slevesque.vscode-hexdump
yzhang.markdown-all-in-one
```

Install extensions from list in file:
```console
$ while read ext; do code --install-extension "$ext"; done < extensions.txt
```
