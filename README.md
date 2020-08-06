# svpro_gnu

Système d'exploitation x64 - 100% GNU basé sur Debian

## Installation (root)
### Generer iso seule
```
curl https://git.weblib.re/svpro/svpro_gnu/raw/branch/develop/build_svprognu | bash
```
### Créer clef usb + persistence
**Attention ! La clef ne doit pas être montée par un autre processus (explorateur de fichiers, utilitaire d'auto-mount...)
```
curl https://git.weblib.re/svpro/svpro_gnu/raw/branch/develop/build_svprognu | bash -s -- -d /dev/sdX
```
**La persistence sera configurée lors du 1er boot. Le démarrage peut prendre quelques minutes.

## Installation physique
Depuis le menu du live, choisir "Installation Graphique ou Experts"

### ToDo

- [x] Installeur
- [x] Live Persistence
- [ ] Integration Yunohost
