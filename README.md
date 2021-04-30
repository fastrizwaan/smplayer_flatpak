# smplayer_flatpak
smplayer in flatpak

#### build and install
```
flatpak install -y --user org.kde.Platform/x86_64/5.15 org.kde.Sdk/x86_64/5.15 
flatpak-builder --force-clean --install --user build-dir/ info.smplayer.SMplayer.yml
```

