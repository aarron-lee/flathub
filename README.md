# Original Source

https://github.com/sharko789/Euro-Office-DesktopEditors-Flatpak


# Build / Install

```
flatpak install -y org.flatpak.Builder
git clone --depth=1 https://github.com/aarron-lee/flathub.git
cd flathub && git checkout EuroOffice
flatpak run org.flatpak.Builder build ./com.github.EuroOffice.DesktopEditors.yml --install-deps-from=flathub --force-clean --user --install
```
