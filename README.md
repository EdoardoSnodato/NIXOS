# NIXOS
Link ricerca pacchetti: https://search.nixos.org/packages?query=

Il file di configurazione della distro è: /etc/nixos/configuration.nix

A seguito di modifiche riavviare distro con il comando:
sudo nixos-rebuild swith (in caso di errori scritti su file di configurazione, la shell restituisce messaggi di errore)

Per aggiornare distro:
sudo nixos-rebuild switch --upgrade
