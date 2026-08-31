# Calculadora KDIGO IRA

Calculadora web gratuita para clasificar Insuficiencia Renal Aguda (IRA) según la guía **KDIGO 2012** con rigor científico 100%.

**URL:** https://calculadorakdigoira.github.io/

## Características

- ✅ Fórmula real KDIGO: `diuresis / peso / horas = mL/kg/h` (corregida)
- ✅ Anuria validada: 0 mL + ≥12h = Etapa 3
- ✅ RRT (Terapia de Reemplazo Renal) = Etapa 3 directo
- ✅ Diseño responsive: móvil (1 columna) y PC (2 columnas, 1120px)
- ✅ SEO preservado: title, description, keywords originales
- ✅ Open Graph 1200x630 para WhatsApp / Twitter / Facebook
- ✅ Favicon .ico + PNG 32x32 + Apple Touch 180x180 + 512x512
- ✅ JSON-LD MedicalWebPage + SoftwareApplication
- ✅ robots.txt + sitemap.xml + manifest.json

## Fórmula

```
Ratio creatinina = actual / basal
Δ creatinina = actual - basal
Diuresis = diuresis_total(mL) / peso(kg) / horas(h)
```

## Criterios KDIGO 2012

| Etapa | Creatinina | Diuresis |
|-------|------------|----------|
| 1 | ≥0.3 mg/dL o 1.5-1.9x basal | <0.5 mL/kg/h por 6-12h |
| 2 | 2-2.9x basal | <0.5 mL/kg/h por ≥12h |
| 3 | ≥4.0 mg/dL o ≥3x basal o RRT | <0.3 mL/kg/h ≥24h o anuria ≥12h |

Fuente: KDIGO Clinical Practice Guideline for Acute Kidney Injury, Kidney Int Suppl 2012.

- Δ ≥0.3 debe ocurrir en 48h
- Ratio ≥1.5x debe ocurrir en 7 días

## Archivos incluidos

- `index.html` - Web completa (17KB)
- `og-image.jpg` - Imagen OG 1200x630 para redes
- `favicon.ico` / `favicon-32x32.png` / `apple-touch-icon.png` / `icon-512.png`
- `robots.txt`, `sitemap.xml`, `manifest.json`

## Instalación en GitHub Pages

1. Sube todo el contenido a la raíz del repo `calculadorakdigoira.github.io`
2. Verifica `https://calculadorakdigoira.github.io/og-image.jpg`
3. Refresca preview de WhatsApp en https://developers.facebook.com/tools/debug/

## Tecnología

- HTML5 puro, sin frameworks
- Tailwind CDN + Inter font
- Cálculo local, no almacena datos
- gtag G-PKSMFNHX4D incluido

## Disclaimer

Herramienta educativa. No sustituye juicio clínico. Basado en KDIGO 2012.

## Licencia

MIT License - ver archivo LICENSE
