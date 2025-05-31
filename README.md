# Streaming Service Launcher flatpak

```bash
flatpak install org.flatpak.Builder
git clone https://github.com/aarron-lee/flathub.git
cd flathub && git checkout streaming-service-launcher
flatpak run org.flatpak.Builder build ./io.github.aarron_lee.StreamingServiceLauncher.yml  --install-deps-from=flathub --force-clean --user --install
```
