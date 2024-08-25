# Configuration Username & User Email

```bash
git config --global user.name "Your Name"

git config --global user.email "youremail@company.com"
```

# Visual Studio Code for Git & default diff tool

## Default Editor

```bash
git config --global core.editor "code --wait"
```

## Difftool

```bash
git config --global diff.tool "default-difftool"
git config --global difftool.default-difftool.cmd "code --wait --diff" \$LOCAL \$REMOTE
```

# See All Configuration

```bash
git config --list --show-origin
```

press `Q` or `q` to exit
