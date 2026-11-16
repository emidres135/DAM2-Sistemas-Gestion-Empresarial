# Práctica 1: Implementación de Tienda Online con Odoo Cloud

Documentación y registro de configuración para la **Tarea Obligatoria 1 (UT1)** del módulo **Sistemas de Gestión Empresarial** (**2º DAM Virtual**, **IES Juan Bosco**).

---

## 🔗 Enlaces del Proyecto

- **Tienda desplegada:** [https://edu-andrespaisrodriguez1.odoo.com](https://edu-andrespaisrodriguez1.odoo.com)
- **Repositorio general del módulo:** [Repositorio-Modulo-SGE](#)
- **Documento de entrega (PDF):** [Tarea para SGE01.pdf](#)

---

## 🎨 Enfoque Visual y Funcional

- **Estética:** Temática *cyberpunk* con tonos morados oscuros y acentos tecnológicos aplicada a una tienda de camisetas frikis.
- **Menú principal:** `Inicio` | `Tienda` | `Eventos` | `Blog` | `Contacto`.
- **Módulos activos:** `Website`, `eCommerce`, `Blog`, `Eventos` y `Suscripciones`.

---

## 🛒 Configuración de Tienda y Catálogo

- **Categorías:**
  - *Camisetas frikis de programación*
  - *Camisetas de películas*
  - *Camisetas de grupos de música*
- **Atributos y variantes:** *Talla* (`S`, `M`, `L`, `XL`, `2XL`, `3XL`) y *Color*, con regla de sobreprecio en variante seleccionada.
- **Filtros activos en `/shop`:** Categorías, búsqueda, atributos, etiquetas y rango de precio.
- **Pago:** Transferencia bancaria configurada para completar el flujo de compra en modo pendiente de confirmación.

---

## 📄 Páginas, Blog y Eventos

- **Inicio:** Escaparate principal con identidad visual, llamadas a la acción y productos destacados.
- **Blog:** Entradas publicadas sobre la colección y temática de la tienda.
- **Contacto:** Formulario funcional e información de sedes físicas en **Madrid** y **Toledo**.
- **Eventos:** Evento gratuito de presentación de colección con **aforo máximo de 50 personas** e inscripción habilitada.