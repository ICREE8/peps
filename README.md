# 100% Peps

Sitio web y catálogo interactivo para péptidos de grado de investigación en Venezuela.

## Características

- **Catálogo de Reactivos**: Compuestos bioactivos con pureza analítica comprobada (>99% HPLC/MS).
- **Cotizador & Pedido Rápido**: Carrito con cálculo de subtotal en USD y tasa BCV, con integración de checkout vía WhatsApp.
- **Certificados COA**: Modal interactivo para inspeccionar cromatogramas y reportes por lote.
- **Diseño Moderno & Responsivo**: Construido con HTML5, Tailwind CSS y Lucide Icons.

## Estructura del Proyecto

```text
peps/
├── assets/          # Fotografías de productos y recursos estáticos
├── index.html       # Aplicación web y lógica de la tienda
├── .gitignore       # Archivos ignorados por Git
└── README.md        # Documentación básica
```

## Uso Local

Abre `index.html` directamente en el navegador, o inicia un servidor web local:

```bash
# Usando Python 3
python3 -m http.server 3000

# O usando Node.js
npx serve .
```

Luego abre `http://localhost:3000` en tu navegador.
