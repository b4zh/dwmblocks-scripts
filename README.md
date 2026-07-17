# dwmblocks-async - Mis scripts

Estos son mis scrtips que utilizo en la barra de estado de [dwmblocks-async.](https://github.com/UtkarshVerma/dwmblocks-async)

- `config.h`: fichero de configuración de **dwmblocks-async**.

- `colors`: fichero que contiene las **variables de entorno** que utilice para los **colores** de la barra.

- `scripts/`: **directorio** donde se encuentran **mis scripts**.

- `otros-scripts/`: **directorio** donde se encuentran **otros scripts** necesarios para el funcionamiento de los siguientes scripts:
    - `vpn`: Script que ejecuta `openvpn` y manda señales de actualización al script `sb-vpn`.
    - `target`: Script para establecer datos (ip y nombre) de una máquina objetivo y mandar señales de actualización al script `sb-tar`. **Para CTF**.

## Configuración

Los `scripts/` deben estar en el directorio `~/.config/dwmblocks`.

Los `otros-scripts/` deben estar en algún directorio del **$PATH**.

Las **variables de entorno** para los **colores** deben ir en el fichero de configuración del shell que uses, si usas bash o zsh, copia y pega el contenido de `colors` en tu `~/.bashrc` o `~/.zshrc`, según corresponda.

Tu **dwm** debe estar parcheado con:

- `status2d`: para los colores de la barra.
- `statuscmd`: para tener una barra clickable.

Puedes echarle un ojo a [mi compilación de dwm](https://github.com/b4zh/dwm-6.8), que está parcheado con esos 2 parches y otros más.

## Recursos

Los recursos que me sirvieron de **guía** fueron los siguientes:

[Gerry Studios - Vídeo sobre dwmblocks](https://www.youtube.com/watch?v=NNwcCPVwr2A)

[Gerry Studios - Scripts dwmblocks](https://git.ricebes.cat/dotfiles/tree/.config/dwmblocks.html)

[Luke Smith - Vídeo sobre dwmblocks](https://www.youtube.com/watch?v=UP2QpHmcgyk)
