# Audios de los instrumentos (zona "Propuesta")

Poner acá las frases cortas grabadas, por ejemplo:

- `bateria.mp3` — Maurel
- `bajo.mp3` — Medrano
- `guitarra.mp3` — Nieva

Después, en `index.html`, completar `AUDIO_FILES` (buscar ese nombre):

```js
const AUDIO_FILES = { drums: 'assets/audio/bateria.mp3', bass: 'assets/audio/bajo.mp3', guitar: 'assets/audio/guitarra.mp3' };
```

Mientras un valor sea `null`, el instrumento suena con un sonido sintetizado de prueba.

## Audios largos de cada integrante (zona "La banda")
Al tocar a un integrante suena su audio en loop. En `index.html` buscar `MEMBER_AUDIO`:

```js
const MEMBER_AUDIO = { 0: 'assets/audio/medrano-bajo.mp3', 1: 'assets/audio/nieva-guitarra.mp3', 2: 'assets/audio/maurel-bateria.mp3' };
```
(0 = Medrano, 1 = Nieva, 2 = Maurel). Con `null` suena un sonido sintetizado de prueba.
