# Landing Page MANACO

## Descripción
Landing page de la marca MANACO con estructura HTML5 semántica, incluyendo header, nav, main, section, article y footer.

## Accesibilidad (a11y)

- Se implementó un **skip link** para permitir saltos directamente al contenido principal usando teclado.
- Se aseguró un **foco visible** en todos los enlaces y botones para mejorar la navegación con teclado.
- Todos los elementos interactivos (`<a>` y `<button>`) son accesibles mediante **tabulador**.
- Se planificaron **alt descriptivos** para imágenes, describiendo su contenido para usuarios de lectores de pantalla (comentados en HTML ya que actualmente no hay imágenes reales).
- Se evitó el uso innecesario de **`aria-*`**, dado que los elementos semánticos (`header`, `nav`, `main`, `section`, `article`, `footer`) ya proporcionan información suficiente.
- Se probó la navegación usando **teclado**, asegurando que el skip link, los enlaces y los botones funcionen correctamente.
