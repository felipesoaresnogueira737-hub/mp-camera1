# MP Camera — TV virtual + Pintura 3D

App Android (Kotlin) com CameraX + MediaPipe Hand Landmarker.

## Modos
**📺 TV virtual** — uma TV flutuando sobre a câmera.
- *Importar vídeo*: escolhe um vídeo da galeria/arquivos do celular.
- Pinça (polegar + indicador) sobre a TV: **segura e arrasta**.
- Pinça com as **duas mãos**: **aumenta/diminui**.
- Pinça nos botões ⏪ ▶/⏸ ⏩ 🔊: **clica**. Pinça na barra de tempo: **pula/arrasta** no vídeo.

**🎨 Pintura 3D**
- Pinça = pinta. Aproximar/afastar a mão da câmera muda a profundidade.
- Arraste o dedo na tela para **girar** a cena (ou ative "Girar" e gire com a pinça).
- Cores, espessura, desfazer, limpar, fundo preto, "Vista 0°".

## Gerar o APK pelo GitHub
1. Suba todos os arquivos para um repositório (branch `main`).
2. **Actions → Build APK** → baixe o artefato **app-debug-apk**.
3. Instale o `.apk` (permita fontes desconhecidas).

O workflow baixa o modelo `hand_landmarker.task` automaticamente.
