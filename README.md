## Poly light GRUB theme

Supported languages: Chinese (simplified), Chinese (traditional), English, French, German, Hungarian, Italian, Korean, Latvian, Norwegian, Polish, Portuguese, Russian, Rusyn, Spanish, Turkish, Ukrainian

![](https://i.imgur.com/9VBf1Nl.gif)

Screenshot is intentionally low res to fit GitHub UI. See also: [1280×720](https://i.imgur.com/HT4ivRY.png), [1920×1080](https://i.imgur.com/n8jBLsj.png)

---

### Installation / update

1. **Secure way:**
    - Download install script:  
    `wget -P /tmp https://github.com/shvchk/poly-light/raw/master/install.sh`
    - Review install script at `/tmp/install.sh`
    - Run it: `bash /tmp/install.sh`

2. **Easier, less secure way** — just download and run install script:  
    `wget -O - https://github.com/shvchk/poly-light/raw/master/install.sh | bash`


You can use `--lang` option to select language and disable interactive language selection, e.g.:

```sh
bash /tmp/install.sh --lang German
```

or

```sh
wget -O- https://github.com/shvchk/poly-light/raw/master/install.sh | bash -s -- --lang Korean
```

Full list of languages see in `INSTALLER_LANGS` variable in [install.sh](install.sh)

---

### See also

- [Poly dark GRUB theme](https://github.com/shvchk/poly-dark)
- [Fallout GRUB theme](https://github.com/shvchk/fallout-grub-theme)
