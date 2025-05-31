# Crunchyroll HTPC (Unofficial)

This app is a Linux port of the Crunchyroll Tizen smart TV app

# Install

run the following in terminal:

```bash
flatpak install -y org.flatpak.Builder
git clone https://github.com/aarron-lee/flathub.git
cd flathub && git checkout crunchyroll-linux
flatpak run org.flatpak.Builder build ./io.github.aarron_lee.crunchyroll-linux.yml  --install-deps-from=flathub --force-clean --user --install
```
