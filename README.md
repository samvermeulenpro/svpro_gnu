# svpro_gnu

Système d'exploitation x64 - 100% GNU basé sur Debian

## Build live via live-build
Cloner le dépôt puis :
```
apt install live-build
lb config
lb build
```

## Création clef USB persistante
```
./build_svprognu -d /dev/sdX # Création de la clef
./build_svprognu # Création de l'iso seule
```

** N.B : Inutile de créer l'ISO, il sera téléchargé et installé sur la clef

### ToDo

- [x] Installeur
- [x] Live Persistence
- [ ] Integration Yunohost
