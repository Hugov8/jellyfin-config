Installer wireguard et openresolv

Copier le fichier de conf dans /etc/wireguard (sudo)
```sh
sudo cp peer.conf /etc/wireguard/wg0.conf
```

Lancer la commande 
```sh
sudo wg-quick up wg0
```

Pour arreter le vpn faire 
```sh
sudo wg-quick down wg0
```