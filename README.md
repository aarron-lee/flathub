# ytmusic flatpak app

```bash
flatpak install org.flatpak.Builder
git clone https://github.com/aarron-lee/flathub.git
cd flathub && git checkout ytmusic
flatpak run org.flatpak.Builder build ./io.github.aarron_lee.ytmusic.yml  --install-deps-from=flathub --force-clean --user --install
```
