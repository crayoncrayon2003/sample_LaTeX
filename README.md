# 1. Install LaTeX
## 1.1. For ubuntu on WSL
```bash
sudo apt update && sudo apt upgrade -y

# TeX Live フルインストール（日本語・図対応）
sudo apt install texlive-full

# 日本語フォント追加
sudo apt install fonts-noto-cjk

# 便利ツール追加（自動コンパイル・PDF変換）
sudo apt install latexmk ghostscript
```

## 1.2. Confirm version
```bash
latex --version
pdflatex --version
lualatex --version
```
## 1.3. VSCode Extension
* LaTeX Workshop
