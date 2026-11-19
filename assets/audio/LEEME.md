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
