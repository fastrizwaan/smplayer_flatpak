# smplayer_flatpak
smplayer in flatpak
copied the manifest from https://github.com/flathub/com.georgefb.haruna/blob/master/com.georgefb.haruna.yml
#### build and install
```
flatpak --user remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install -y --user org.kde.Platform/x86_64/5.15 org.kde.Sdk/x86_64/5.15 
git clone https://github.com/fastrizwaan/smplayer_flatpak.git
cd smplayer_flatpak
flatpak-builder --force-clean --install --user build-dir/ info.smplayer.SMplayer.yml
```

