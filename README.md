# Aprendendo Artimanhas com WSL

## Executando GUI no WSL

Para acessar uma interface gráfica no wsl, precisamos configurar algumas dependências de sistema

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install libgstreamer1.0-0 libgstreamer-plugins-base1.0-0 gstreamer1.0-plugins-base gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-libav
sudo apt install mpv
sudo apt install libmpv2
```
