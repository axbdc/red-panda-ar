# Panda Vermelho em AR

Viewer 3D com botão para abrir o modelo em realidade aumentada.

- iPhone / iPad: AR Quick Look (`red_panda.usdz`)
- Android: Google Scene Viewer (`red_panda.glb`)
- Desktop: preview 3D + aviso para ler o QR no telemóvel

## Ficheiros

| Ficheiro | Para quê |
| --- | --- |
| `index.html` | Viewer (model-viewer 3.4.0) |
| `red_panda.glb` | Modelo para Android e preview 3D |
| `red_panda.usdz` | Modelo para iOS |
| `vercel.json` | Content-Type correto para `.usdz` e `.glb` no Vercel |

Os nomes dos modelos têm de ser exatamente estes. Para usar outros nomes, altera `src` / `ios-src` no `<model-viewer>` e as constantes `GLB` / `USDZ` no script.

## Deploy

Cada push para `main` faz deploy automático no Vercel.

Baseado no projeto `ar-models`.
