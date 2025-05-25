# 🐾 Hidden Cat Cowfile for cowsay

A minimal and compact cat-themed cowfile for [cowsay](https://github.com/tnalpgge/rank-amateur-cowsay).  
Perfect for terminal lovers who want to add a bit of feline charm without taking up too much screen space.

> “Blood for the blood god, skulls for the skull throne”  
> — With a little cat under it 🐱

![example](https://github.com/user-attachments/assets/29ae41ff-61dd-4ccb-97cd-1730fc3bf4d5)

---

## 📦 Installation

1. Clone or download this repository:

```bash
git clone https://github.com/DennisNeu/hidden-cat-cowfile.git
cd hidden-cat-cowfile
```

2. Copy the cowfile to your cowsay directory:

```bash
sudo cp hidden-cat.cow /usr/share/cowsay/cows/
```

3. Use it with cowsay:

```bash
cowsay -f hidden-cat "Stay pawsitive!"
```

4. (Optional) Combine with [lolcat](https://github.com/busyloop/lolcat) for color:

```bash
cowsay -f hidden-cat "Colors!" | lolcat
```

---

## 🎯 Why Hidden Cat?

Most cat cowfiles are:

- Too big
- Too busy
- Too distracting

`hidden-cat` is different:

- ✅ **Compact** — takes up minimal vertical space
- ✅ **Clean** — simple lines, no bloat
- ✅ **Cute** — still full of personality
- ✅ **Terminal-friendly** — great for minimalist setups or small screens

---

## 🐚 Show Hidden Cat at Every Terminal Start

To greet yourself with a wise whisker of wisdom every time you open the terminal, add the following line to your shell's configuration file:

### Bash (`~/.bashrc`)
```bash
cowsay -f hidden-cat "Welcome back, human." | lolcat
```

### Zsh (`~/.zshrc`)
```bash
cowsay -f hidden-cat "Welcome back, human." | lolcat
```

### Fish (`~/.config/fish/config.fish`)
```fish
cowsay -f hidden-cat "Welcome back, human." | lolcat
```

> 📝 You can change the message to anything you like, or remove `| lolcat` if you prefer plain output. For randomness, you can pipe the output of [fortune](https://github.com/shlomif/fortune-mod) into cowsay.

After editing the file, either restart your terminal or reload the config:

```bash
source ~/.bashrc   # or ~/.zshrc, etc.
```

Now, your terminal will be blessed by a miniature cat philosopher each time you open it. 🐱✨
