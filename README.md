# gkeep flatpak app

```bash
flatpak install org.flatpak.Builder
git clone https://github.com/aarron-lee/flathub.git
cd flathub && git checkout gkeep
flatpak run org.flatpak.Builder build ./io.github.aarron_lee.gkeep.yml  --install-deps-from=flathub --force-clean --user --install
```
