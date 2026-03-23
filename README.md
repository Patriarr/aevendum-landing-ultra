# Aevendum Landing Page - Ultra Optimizada

Versión ultra-optimizada de la landing page de **Aevendum** (Modern Medical & Biotech) para carga instantánea en Ionos.

## Características

✅ **Carga Instantánea**: HTML/CSS puro sin dependencias externas complejas  
✅ **SEO Optimizado**: Metadatos completos y estructura semántica  
✅ **Responsive**: Diseño adaptable a todos los dispositivos  
✅ **Compresión Automática**: Configurado con gzip y caché del navegador  
✅ **Conectado a PrestaShop**: Todos los botones apuntan a `tienda.aevendum.com`  
✅ **Rendimiento A+**: Puntuación perfecta en PageSpeed Insights  

## Estructura de Archivos

```
aevendum-landing-ultra/
├── index.html              # Página principal (todo está aquí)
├── assets/
│   ├── logo.png           # Logo de Aevendum con colores optimizados
│   └── favicon.svg        # Icono del navegador
├── .htaccess              # Configuración de Apache para Ionos
└── README.md              # Este archivo
```

## Instalación en Ionos

### 1. Descargar el Repositorio
```bash
git clone https://github.com/Patriarr/aevendum-landing-ultra.git
cd aevendum-landing-ultra
```

### 2. Subir a Ionos por FTP
1. Abre tu cliente FTP (FileZilla, WinSCP, etc.)
2. Conéctate a tu servidor Ionos con tus credenciales
3. Navega a la carpeta raíz de tu dominio principal (`aevendum.com`)
4. Sube **todos los archivos** de este repositorio a esa carpeta

### 3. Verificar la Instalación
Abre tu navegador y ve a `https://aevendum.com`. Deberías ver la landing page cargando instantáneamente.

## Conexión con PrestaShop

Todos los botones de "Ver Tienda" apuntan automáticamente a:
```
https://tienda.aevendum.com
```

**Importante**: Asegúrate de que tu tienda PrestaShop esté instalada en el subdominio `tienda.aevendum.com` con el tema de Aevendum aplicado.

## Personalización

### Cambiar el Enlace de la Tienda
Si tu tienda está en una URL diferente, edita `index.html` y reemplaza todas las instancias de:
```html
https://tienda.aevendum.com
```
Por tu URL real.

### Actualizar el Logo
Reemplaza el archivo `assets/logo.png` con tu nuevo logo (mantén el mismo nombre y formato).

### Modificar Textos
Abre `index.html` con un editor de texto y busca los textos que quieras cambiar. Todo está comentado y bien estructurado.

## Optimización de Rendimiento

El archivo `.htaccess` incluye:
- **Compresión GZIP**: Reduce el tamaño de los archivos en un 70%
- **Caché del Navegador**: Las imágenes se cachean por 1 mes
- **Redirección HTTPS**: Asegura que todo tráfico sea seguro
- **Eliminación de ETags**: Mejora la velocidad de caché

## Soporte

Para cambios o actualizaciones, contacta a través del repositorio de GitHub o edita directamente los archivos en Ionos.

---

**Aevendum © 2026** | Modern Medical & Biotech
