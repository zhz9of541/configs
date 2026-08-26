# Linux Setup Notes

## Initial packages

- `git`
- `curl`
- `vim`
- `tmux`
- `fzf`
- `ripgrep`
- `htop`

## Symlinks

Create symlinks from this repo to home directory:

```bash
ln -sf ~/configs/.bashrc ~/.bashrc
ln -sf ~/configs/.tmux.conf ~/.tmux.conf
ln -sf ~/configs/.vimrc ~/.vimrc
```

## Git config

Set global user:

```bash
git config --global user.name "Ethan Nakamura"
git config --global user.email "ethan@example.com"
```

## Locale

Set timezone to Seoul:

```bash
sudo timedatectl set-timezone Asia/Seoul
```