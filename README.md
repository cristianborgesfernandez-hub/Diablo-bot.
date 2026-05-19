### Instalaciónes Básicas

<details>
<summary><strong>🍒 Cloud</strong> — Shell</summary>

```bash
git clone https://github.com/cristianborgesfernandez-hub/Diablo-bot.
```

```bash
cd Diablo-bot.
```

```bash
yarn install
```

```bash
npm install
```

```bash
npm start
```

</details>

<details>
<summary><strong>🍒 Termux</strong> — Manualmente</summary>

```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install -y git nodejs ffmpeg imagemagick yarn
```

```bash
git clone https://github.com/cristianborgesfernandez-hub/Diablo-bot.
```

```bash
cd Diablo-bot.
```

```bash
yarn install
```

```bash
npm install
```

```bash
npm start
```

> *Si aparece **(Y/I/N/O/D/Z) [default=N] ?** use la letra **"y"** y luego **"ENTER"** para continuar con la instalación.*

</details>

<details>
<summary><strong>🍒 Comandos para tener mas tiempo activo</strong> — el Bot</summary>

> *Ejecutar estos comandos dentro de la carpeta Diablo-bot.*
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
``` 

#### Opciones Disponibles
> *Esto eliminará todo el historial que hayas establecido con PM2:*
```bash 
pm2 delete index
``` 

> *Si tienes cerrado Termux y quiere ver de nuevo la ejecución use:*
```bash 
pm2 logs 
``` 

> *Si desea detener la ejecución de Termux use:*
```bash 
pm2 stop index
``` 

> *Si desea iniciar de nuevo la ejecución de Termux use:*
```bash 
pm2 start index
```

--- 

### En caso de detenerse
> _Si despues que ya instalastes tu bot y termux te salta en blanco, se fue tu internet o reiniciaste tu celular, solo realizaras estos pasos:_
```bash
cd && cd Diablo-bot. && npm start
```
---

### Obtener nuevo inicio de Sessión 
> *Detén el bot, haz click en el símbolo (ctrl) [default=z] usar la letra "z" + "ENTER" hasta que salga algo verdes similar a: `Diablo-bot. $`*
 
```bash 
cd && cd Diablo-bot. && rm -rf Sessions/Owner && npm start
```