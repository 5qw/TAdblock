<center>
    <h1 align="center">🔰 AdBlock Spotify 🔰</h1>
    <h4 align="center">:warning: Este bloqueador es para la versión de <a href="https://www.spotify.com/download/windows/"> 𝑬𝑺𝑪𝑹𝑰𝑻𝑶𝑹𝑰𝑶 de Spotify en Windows y 𝗡𝗢 𝗽𝗮𝗿𝗮 𝗹𝗮 𝘃𝗲𝗿𝘀𝗶ó𝗻 𝗱𝗲 𝗺𝗶𝗰𝗿𝗼𝘀𝗼𝗳𝘁 𝘀𝘁𝗼𝗿𝗲. </a> </h4>
    <h5 align="center"> <a href="https://www.spotify.com/premium/">💲 Apoya a Spotify comprando premium 💲</a> </h5>
</center>

🧱 » <b> Antes de instalar (opcional): </b>
1. Actualice Windows, actualice Spotify y actualice este instalador
2. Vaya a "Seguridad de Windows" ➞ "Protección contra virus y amenazas"
3. Haga clic en "Amenazas permitidas" ➞ "Eliminar todas las amenazas permitidas"

🧩 » <b> Características: </b>
* Bloquea todos los anuncios de banner/video/audio dentro de la aplicación
* Conserva la funcionalidad de amigo, video vertical y radio
* Desbloquea la función de saltar cualquier canción

⚙️ » <b> Instalación recomendada:</b>
* Simplemente descarga y ejecuta [AdBlock Spotify.bat](https://raw.githack.com/5qw/5p0t1fy/master/AdBlock%20Spotify.bat)  

<hr>

🔩 » <b> Instalación manual (comandos):</b>

```powershell
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; Invoke-Expression "& { $(Invoke-WebRequest -UseBasicParsing 'https://raw.githubusercontent.com/5qw/5p0t1fy/master/install.ps1') } -UninstallSpotifyStoreEdition -UpdateSpotify -RemoveAdPlaceholder"
```

<hr>

⛏ » <b> Instalación manual (archivos): </b>

1. Vaya a su carpeta de instalación de Spotify `%APPDATA%\Spotify`
2. Renombra `chrome_elf.dll` to `chrome_elf_bak.dll`. El nombre es importante.
3. Descarga `chrome_elf.zip` de [releases](https://github.com/5qw/5p0t1fy/releases)
4. Descomprime `chrome_elf.dll` y `config.ini` a la carpeta de Spotify. 

📦 » <b> Desinstalación: </b>
* Ejecutar [uninstall.bat](https://raw.githack.com/5qw/5p0t1fy/master/uninstall.bat)
* Desinstalar e instalar Spotify
