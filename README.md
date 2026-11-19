# 🍧 Granizados NeMar

Sitio oficial de **Granizados NeMar**. Versión actual: landing de una sola página,
estática (HTML + CSS + JavaScript), sin frameworks ni backend.

🔗 **Sitio en vivo:** https://alejandrogonzalez-23.github.io/Granizados-NeMar/

---

## ✨ Versión publicada (noviembre 2026)

- **7 sabores definitivos:** Fresa Salvaje, Mango Biche, Maracuyá Eléctrico,
  Frambuesa Explosiva, Blue Galáctico, Nube de Coco y Chamoy Boom.
- **Precios:** 8 oz $9.000 · 12 oz $11.000 · 16 oz $13.000. Toppings +$2.000.
- **Círculos del inicio:** Blue Galáctico (grande), Nube de Coco,
  Maracuyá Eléctrico y Chamoy Boom, con el vaso completo dentro de cada círculo.
- **Pedidos:** botones de tamaño y configurador que abren WhatsApp con el pedido.
- **Filtros** por categoría de sabor y galería actualizada.
- **Logo:** Granizados NeMar (reemplaza al anterior "Sweet Splash").

## 📁 Estructura usada por la página actual

```
Granizados-NeMar/
├── index.html          # landing completa
├── styles.css          # diseño y responsive
├── script.js           # filtros, precios y WhatsApp
├── assets/
│   ├── img/            # fotos de sabores, círculos del hero y logos
│   └── fonts/          # tipografías
├── .nojekyll           # permite publicar tal cual en GitHub Pages
└── README.md
```

Los archivos `cocteles.html`, `granizados.html`, `malteadas.html`, `style.css`,
`img/`, `img2/` y `fonts/` en la raíz son de la **versión anterior** y ya no son
usados por `index.html`. Se conservan como historial del proyecto.

## 🚀 Publicación

GitHub Pages publica la rama `main` de este repositorio. Para actualizar:

```bash
git add .
git commit -m "Actualiza sitio de Granizados NeMar"
git push
```

## 💻 Verlo localmente

```bash
python -m http.server 8000
```

Luego abrir `http://localhost:8000`.

## ⏳ Datos pendientes de confirmar con el negocio

- Número real de WhatsApp (actualmente hay uno de ejemplo en `script.js`).
- Dirección, horarios y enlaces de redes sociales.
- Medios de pago y condiciones de domicilio.
- Promociones y fotografías propias del negocio.
