# Kodi-Linux

1. Primeiro, pressione Ctrl+Alt+T no teclado para abrir o terminal. Em seguida, use o comando abaixo para instalar o Kodi.
```python
flatpak install flathub tv.kodi.Kodi
```
2. Se você deseja conceder ao aplicativo Flatpak acesso às pastas Downloads e Documentos, basta digitar os comandos abaixo:
```python
flatpak override --user --filesystem=~/Downloads tv.kodi.Kodi
```
```python
flatpak override --user --filesystem=~/Documentos tv.kodi.Kodi
```
3. Se você quiser liberar acesso a todo o sistema de arquivos (o que deve ser feito com cuidado), pode usar:
```python
flatpak override --user --filesystem=host tv.kodi.Kodi
```
add-ons F4mtester
[[plugin.video.f4mTester-4.1.4.zip]](https://github.com/gloriosotv/Kodi-Linux/raw/refs/heads/main/plugin.video.f4mTester-4.1.4.zip)
