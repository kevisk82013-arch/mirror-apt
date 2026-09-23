# mirror-apt

Repositorio APT del paquete `mirror-signage` (espejos interactivos Mirror Marketing).

En cada Raspberry Pi:

```
echo "deb [trusted=yes] https://kevisk82013-arch.github.io/mirror-apt ./" | sudo tee /etc/apt/sources.list.d/mirror-signage.list
sudo apt-get update && sudo apt-get install mirror-signage
```
