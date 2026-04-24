# 🚗 BMW Classic Parts Catalog

Premium parts catalog for classic BMW models with detailed diagrams and bilingual support (EN/ES).

## 🎯 Features

- **8 BMW Models**: E28, E36, E46 series
- **Detailed Diagrams**: Thousands of exploded view diagrams with part numbers
- **Bilingual**: Full EN/ES translation with 425+ automotive terms
- **Premium Design**: Modern, minimalist interface inspired by MyBMW app
- **Responsive**: Works on desktop, tablet, and mobile
- **Single Page App**: Fast navigation with hash-based routing
- **Search Integration**: Direct links to Autodoc for parts availability

## 📊 Catalog Stats

- 8 BMW Models
- 3,000+ Part Diagrams
- 50,000+ Individual Parts
- Complete price information

## 🚀 Live Demo

**[View Catalog](https://danielmanzanares.github.io/bmw-parts-catalog)**

## 🛠️ Technology

- **Frontend**: Pure vanilla JavaScript (no frameworks)
- **Styling**: Custom CSS with Inter font
- **Data**: JSON export from SQLite database
- **Hosting**: GitHub Pages
- **Translation**: Word-by-word dynamic replacement system

## 📚 Models Included

### E28 Series
- 524td (Daniel)

### E36 Series
- 316i/318i Compact (Victor)
- 318is Coupe (Marcos)
- 328i Coupe (Juanan)

### E46 Series
- 318Ci Coupe (Luis)
- 320d Sedan (Fer)
- 330Ci Coupe (Marcos)
- 330d Sedan (Daniel)

## 🎨 Design Philosophy

Premium, minimalist design inspired by official BMW applications:
- Dark gradients and glass morphism effects
- Clean typography with Inter font family
- Hover animations and smooth transitions
- Focus on content and usability
- BMW brand colors (blacks and grays)

## 📖 Educational Purpose

This catalog is created for educational and reference purposes only. All data is sourced from publicly available BMW parts catalogs. Part numbers and prices are for reference only.

## 🔧 Local Development

The project is a static website that can be served from any HTTP server:

```bash
# Using Python
cd github_pages
python -m http.server 8000

# Using Node.js
npx http-server github_pages -p 8000
```

Then open http://localhost:8000

## 📁 Project Structure

```
bmw-parts-catalog/
├── index.html          # SPA entry point
├── data/               # JSON data files
│   ├── models.json
│   ├── model_*_categories.json
│   ├── model_*_category_*_diagrams.json
│   └── diagram_*.json
└── images/             # Part diagram images
    └── *.gif
```

## 🌐 Translation System

Dynamic word-by-word translation that:
- Preserves alphanumeric codes and part numbers
- Translates 425+ automotive technical terms
- Maintains context-specific terminology
- Works across all pages and components

## 🤝 Contributing

This is a personal educational project. Data updates are welcome via issues.

## 📄 License

Content for educational reference only. BMW trademarks and part data belong to their respective owners.

---

**Built with 🧡 by Daniel Manzanares**

*Part of the NorthRoads Media educational projects*
