# America Off-Road · Demo landing

Demo de landing page con animaciones scroll-driven (GSAP + ScrollTrigger) y modelos 3D (Three.js) para America Off-Road, Luján de Cuyo, Mendoza.

Ver en vivo: https://romanmarti2112.github.io/america-offroad/

## Correr local

```bash
python -m http.server 8766
```

## Créditos 3D (CC BY 4.0)

- "Offroad Truck Wheel" de Anderson Fogaça — https://sketchfab.com/3d-models/6ebc61a1e30a4472ae456e8153d0fc82
- "Ford Ranger Offroad" de UltraPatcher — https://sketchfab.com/3d-models/7c94a52bf2f14060bd054f51f7b06d19

## CSS

Tailwind se compila a `tw.css` (no se usa el CDN en runtime). Si cambiás clases en `index.html`:

```bash
npx tailwindcss@3.4.17 -i tw.src.css -o tw.css --minify
```
