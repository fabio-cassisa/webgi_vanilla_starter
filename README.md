# webgi vanilla starter

3D product showcasing on the web — built with the WebGi SDK, TypeScript, and Vite.

## context

A boilerplate I built for experimenting with 3D product visualization on the web. The idea: take a 3D model and present it in a browser with realistic rendering, camera controls, and interaction — no heavy frameworks, no React overhead. Just HTML, CSS, TypeScript, and a powerful rendering engine.

This sits at the intersection of my industrial design background (Politecnico di Torino) and frontend development — bringing physical products into digital experiences.

## stack

`typescript` · `webgi sdk` · `vite` · `html` · `css`

## structure

```
src/
├── index.ts      # main entry — scene setup, camera, interactions
└── styles.css    # layout and presentation
assets/           # 3d models and textures
index.html        # entry point
```

## run locally

```bash
npm install
npm run dev
```

## what's webgi?

[WebGi](https://webgi.xyz/) is a high-quality 3D rendering SDK for the web. It handles PBR materials, environment lighting, post-processing, and camera animation out of the box — think product configurators, jewelry showcases, furniture previews.

## status

🟡 starter/experiment — built as a learning tool and base for future 3D web projects. Could evolve into a product configurator template.

---

<sub>built by [fabio cassisa](https://github.com/fabio-cassisa)</sub>
