# Oh My VSCode Snippets

1. Go to VSCode user config dir.
2. Backup previous snippets.
3. Clone the repo and rename it.

```bash
cd ~/Library/Application\ Support/Code/User/
mv snippets snippets-bak

git clone git@github.com:shrekuu/oh-my-vscode-snippets.git snippets
```

4. Optional. Let's put this somewhere else so I can modify them easily. Go to my projects directory and create a symlink.

```bash
cd ~/code
~/Library/Application\ Support/Code/User/snippets vscode-snippets
```
