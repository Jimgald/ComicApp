# app-web comics

<aside>
🚀

**Nombre del Proyecto: ComicApp**

</aside>

---

<aside>
🚀

**Resumen:**

Muestra un listado de comics guardados (CRUD).

- Filtros de busquedas (tags)
- Extra: Api precios
- Extra: Otra db con comics como lista de favoritos whist list
- Extra: Ver historial de transacciones y cuanto hemos ganado/perdido
</aside>

---

<aside>
🚀

**Plataforma:**

- Web
- App + Electron
</aside>

---

<aside>
🚀

**Requisitos:**

- **Lenguajes/Frameworks:**
    - NodeJs
    - Express
    - MongoDB
    - React
    
- **Dependencias:** (Ej.: Librerías, APIs externas)
    - Express
    - Electron
    - Mongoose
</aside>

---

<aside>
🚀

**Funcionalidades Principales:**

1. Visualizar los comics que se tienen
2. Añadir mas comics
3. Modificar comics
4. Eliminar comics
5. Ver el precio actual en el mercado
6. Ver la lista de deseos
7. Ver las transacciones y nuestro cashflow
8. Cambiar tema claro-oscuro
9. Si añades un comic sin foto que coga la primera inicial del titulo y tengamos una especie de template
    1. Que comprube si empieza por articulo, para continuar con la siguiente palabra (ejemplo, The Hulk, The Captain Am..)
    2. Lectura API portadas comics
</aside>

---

<aside>
🚀

**Interfaz Básica:**

- **Número de pantallas o vistas:**
    - landing principal limitado a 10 comics con boton para ver todos menu
    - Menus para ir a modificar, eliminar, ver historico de transacciones
- **Diseño UI simple:** Descripción básica de cómo se verá la aplicación (colores, botones, flujo).
    - CSS Grid - responsive
    - Cards
        - Imagen a tamaño completo
        - Un separador con blur donde poner el titulo, subtitulo, precio
    - Background: oscuro-claro
- UI EXTRA
    - Estanteria con los comics en el que puedas ordenarlos y tenerlos a la vista
    - Posible zoom y vista carrusel
- Inpo:
    - https://www.mi.com/es/
    - https://www.amazon.es/
    - https://www.apple.com/ipad/
    - https://www.behance.net/gallery/136856577/2-UI-Design-Checkout-Credit-Card?tracking_source=search_projects%7Cdise%C3%B1o+ui+ux+cards&l=7
    - https://leagueofcomicgeeks.com/comics
    - https://www.uxarchive.com/
    - https://www.behance.net/gallery/228836621/Build-Comic-Shop-with-Comic-Book-Store-WordPress-Theme?tracking_source=search_projects%7Clanding+page+comics&l=6
    - 

</aside>

## Wireframe

[https://www.figma.com/design/mzQado0IPnh48PjwhASQZs/Untitled?node-id=0-1&p=f&t=S0hWoJxIk2DjcnWt-0](https://www.figma.com/design/mzQado0IPnh48PjwhASQZs/Untitled?node-id=0-1&p=f&t=S0hWoJxIk2DjcnWt-0)

---

<aside>
🚀

**Esquema de Datos:**

- **Base de Datos:** (Si aplica, indicar tablas o estructuras clave)
    - Tabla Comics
        - id
        - nombre comic
        - fecha publicación
        - autor
        - editorial
        - género
        - precio compra
        - precio venta
        - valor actual
        - nº páginas
        - leido
        - wishlist
        - tomo
        - etiquetas
    - Tabla transacciones
        - id
        - nombre comic
        - precio compra
        - precio venta
        - valor actual
        - si_vendido
</aside>

---

<aside>
🚀

**Flujo Básico:**

1. **Inicio:** (Qué ve el usuario primero)
    1. Landing page para añadir un nuevo comic de forma rapida (formulario titulo y boton en grande para add) ~ te redirige a pagina comics para gestionar y seguir añadiendo
        1. Posible: desplegar con el resto de datos obligatorios 
        2. Añadido rápido
    2. Abajo lista comics
2. **Navegación:** (Pasos principales dentro de la aplicación)
    1. Home
    2. Comics (ver todos) + añadir nuevos + borrar + modificar (GESTIONAR CRUD)
    3. Ventas
    4. Contacto (formulario) > GitHub issue
    5. FAQ’s
3. **Resultado:** (Acciones finales o producto final)
</aside>

---

<aside>
🚀

**MVP (Producto Mínimo Viable):**

¿Qué funcionalidades mínimas se necesitan para un lanzamiento básico?

- Ver listado comics
- Añadir nuevos comics
</aside>

---

<aside>
🚀

**Próximos Pasos:**

[Sin título](app-web%20comics%2022a3b73fe34380ada23fe73650462337/Sin%20ti%CC%81tulo%2022b3b73fe343809b8603d48e774548f4.csv)

</aside>