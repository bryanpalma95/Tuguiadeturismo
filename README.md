# 🗺️ Guía de Turismo - Chile

Una aplicación web moderna y elegante para descubrir y gestionar servicios turísticos en Chile.

## ✨ Características

### 📋 Gestión Completa de Servicios
- **5 Categorías Principales:**
  - 🏨 **Hoteles** - Alojamientos y hospedajes
  - 🍽️ **Restaurantes** - Locales de comida y gastronomía
  - 🛠️ **Servicios** - Servicios generales para turistas
  - 🎭 **Atractivos Turísticos** - Museos, parques, monumentos
  - ✈️ **Agencias de Viaje** - Agencias y operadores turísticos

### 🎨 Diseño Premium
- **Interfaz Moderna**: Diseño oscuro con gradientes vibrantes
- **Animaciones Suaves**: Transiciones y micro-animaciones para una experiencia premium
- **Glassmorphism**: Efectos de vidrio esmerilado para un look contemporáneo
- **Responsive**: Totalmente adaptable a dispositivos móviles y tablets

### 🔍 Funcionalidades Principales

#### Agregar Servicios
- Formulario completo con todos los campos necesarios
- Categorización automática
- Sistema de calificación (1-5 estrellas)
- Rango de precios ($, $$, $$$, $$$$)
- Etiquetas personalizables

#### Buscar y Filtrar
- Búsqueda en tiempo real
- Filtrado por categoría
- Búsqueda por nombre, descripción, dirección y etiquetas

#### Visualización
- Tarjetas visuales atractivas
- Vista de detalles completa
- Contador de servicios por categoría

#### Editar y Eliminar
- Edición rápida de servicios existentes
- Eliminación con confirmación
- Actualización en tiempo real

### Instalación
1. Descarga los archivos del proyecto
2. Abre `index.html` en tu navegador web
3. ¡Listo! La aplicación está funcionando

### Uso Básico

#### Agregar un Nuevo Servicio
1. Haz clic en el botón **"Agregar Nuevo Servicio"**
2. Completa el formulario con la información:
   - Selecciona la categoría
   - Ingresa el nombre del servicio
   - Completa dirección, teléfono, email
   - Agrega sitio web (opcional)
   - Selecciona calificación y rango de precio
   - Escribe una descripción
   - Agrega etiquetas separadas por comas
3. Haz clic en **"Guardar Servicio"**

#### Ver Detalles
- Haz clic en el ícono del ojo (👁️) en cualquier tarjeta de servicio
- Se abrirá un modal con toda la información detallada

#### Editar un Servicio
- Haz clic en el ícono del lápiz (✏️) en la tarjeta del servicio
- Modifica los campos necesarios
- Guarda los cambios

#### Eliminar un Servicio
- Haz clic en el ícono de la papelera (🗑️)
- Confirma la eliminación

#### Buscar Servicios
- Usa la barra de búsqueda en la parte superior
- La búsqueda filtra por nombre, descripción, dirección y etiquetas
- Los resultados se actualizan en tiempo real

#### Cambiar de Categoría
- Haz clic en cualquiera de las pestañas de categoría
- La vista se actualizará mostrando solo los servicios de esa categoría

## 📁 Estructura del Proyecto

```
Antigravity/
│
├── index.html          # Estructura HTML principal
├── index.css           # Estilos y diseño visual
├── app.js              # Lógica de la aplicación
└── README.md           # Este archivo
```

## 🎨 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Diseño moderno con variables CSS, gradientes y animaciones
- **JavaScript (ES6+)** - Lógica de la aplicación orientada a objetos
- **LocalStorage API** - Persistencia de datos
- **Google Fonts** - Tipografías Inter y Outfit

## 🌟 Características Técnicas

### Sistema de Diseño
- Variables CSS para colores, espaciado y tipografía
- Paleta de colores vibrante con modo oscuro
- Sistema de espaciado consistente
- Animaciones y transiciones suaves

### Arquitectura del Código
- Programación orientada a objetos
- Clase `ServiceManager` para gestionar el estado
- Separación de responsabilidades
- Código limpio y mantenible

### Optimizaciones
- Renderizado eficiente
- Búsqueda optimizada
- Animaciones con CSS para mejor rendimiento
- Carga instantánea (no requiere servidor)

## 📊 Datos Reales Incluidos

La aplicación viene precargada con **73 servicios turísticos y de emergencia reales de Chile**, distribuidos en las 5 categorías, con **énfasis en Villarrica y la Región de La Araucanía**:

### 🏨 Hoteles (11 hoteles)
- **The Ritz-Carlton Santiago** - Lujo 5 estrellas en Las Condes
- **Mandarin Oriental Santiago** - Elegancia y spa de clase mundial
- **W Santiago** - Diseño vanguardista y rooftop bar
- **NH Collection Plaza Santiago** - Ideal para negocios
- **Hotel Plaza San Francisco** - Céntrico y accesible
- **Hotel Enjoy Viña del Mar** - Resort con casino frente al mar
- **Pullman Viña del Mar** - Moderno con vista al Pacífico
- **Hotel Diego de Almagro Valparaíso** - Acceso a cerros patrimoniales
- **Hotel Da Vinci Valparaíso** - Boutique en Cerro Alegre
- **Hotel Concepción** - Centro de Concepción
- **Hotel Villamar** - Familiar y económico en Viña

### 🍽️ Restaurantes (11 restaurantes)
- **Boragó** - Mejor restaurante de Chile, cocina experimental
- **Ambrosia Bistró** - Fusión francesa-chilena
- **Portofino Restaurant** - Mediterráneo en Valparaíso
- **Poesía de Sabor** - Cocina casera tradicional
- **La Cocina del Mar** - Mariscos frescos en Viña del Mar
- **Rincón Marino** - Mariscos en Concepción
- **Terralomas Restaurant** - Gourmet contemporáneo
- **Battir Restaurante** - Cocina mediterránea y árabe
- **Donde Willy** - Tradicional chileno en Viña
- **Divino Pecado** - Alta cocina en Viña del Mar
- **Faro Belén** - Mariscos con vista panorámica

### 🛠️ Servicios Turísticos (10 servicios)
- **Turistik Chile** - Tours y autobús Hop-On Hop-Off
- **Lucero Travel Chile** - City tours y viñedos
- **CHIRAK Chile** - Patagonia, Atacama, Isla de Pascua
- **GoChile** - Paquetes completos por todo Chile
- **Destino Chile** - Operador mayorista con 25 años
- **Hertz Rent a Car** - Arriendo de autos premium
- **Budget Rent a Car** - Vehículos económicos
- **Avis Rent a Car** - Cobertura internacional
- **Europcar Chile** - Servicio premium
- **Chilean Rent a Car** - Empresa local con tarifas competitivas

### 🎭 Atractivos Turísticos (10 atractivos)
- **Museo Nacional de Bellas Artes** - Principal museo de arte
- **Parque Nacional Torres del Paine** - Glaciares y Patagonia
- **Museo de la Memoria y DDHH** - Historia y cultura
- **Monumento Natural La Portada** - Icono de Antofagasta
- **Parque Nacional Conguillío** - Volcán Llaima y araucarias
- **Museo de Historia Natural Valparaíso** - Paleontología y biodiversidad
- **Museo Palacio Baburizza** - Bellas Artes en palacio histórico
- **Museo de Historia Natural Concepción** - Fauna y flora regional
- **Galería de la Historia Concepción** - Museo interactivo
- **Parque Museo Pedro del Río Zañartu** - Jardines y arqueología

### ✈️ Agencias de Viaje (10 agencias)
- **Cocha** - 70 años de trayectoria, atención 24/7
- **Turavion** - 90 años de experiencia
- **My Horizon** - Agencia boutique personalizada
- **Viajes El Corte Inglés** - Asesoría de calidad
- **Travel Security** - Respaldo Banco Security
- **Blanco Viajes** - Especialistas en corporativo e incentivos
- **Altotravel** - Mayorista enfocado en turismo emisivo
- **Party Travel** - Paquetes y tickets aéreos
- **TAC Turismo** - Tours en Santiago y alrededores
- **Andina del Sud** - 60 años en turismo receptivo

### 🌋 Servicios de Villarrica y Pucón (15 servicios)

La aplicación incluye servicios específicos de la zona de Villarrica:

**Hoteles (5)**:
- Hotel Terraza Suite - Moderno en centro de Villarrica
- Hotel Villarrica - Tradicional con cabañas
- Hotel Lago Villarrica - Económico y familiar
- Park Lake Luxury Hotel - Lujo frente al lago
- Hotel Licanray - Boutique con playa privada

**Restaurantes (5)**:
- Fuego Patagón - Parrilla y carnes premium
- Café 2001 - Tradicional para desayunos
- La Mesa del Sur - Comida casera chilena
- El Rey del Marisco - Mariscos frescos
- Albertina Pizza - Pizzería artesanal

**Atractivos Turísticos (5)**:
- Parque Nacional Villarrica - Volcán activo y trekking
- Termas Geométricas - 18 piscinas termales únicas
- Ojos del Caburgua - Cascadas turquesa
- Parque Nacional Huerquehue - Araucarias milenarias
- Centro de Ski Pucón - Esquí en el volcán

### 🚨 Servicios de Emergencia Villarrica (6 servicios)

**Números de Emergencia Nacional**:
- 🚑 **131** - SAMU (Ambulancia)
- 🚒 **132** - Bomberos
- 🚓 **133** - Carabineros (Policía)
- 🔍 **134** - PDI (Policía de Investigaciones)

**Servicios Locales**:
1. **Hospital de Villarrica** - San Martín 460, Urgencias 24h (131)
2. **Carabineros 7ma Comisaría** - Manuel Antonio Matta 230 (133)
3. **Bomberos de Villarrica** - Valentín Letelier 630 (132)
4. **PDI Villarrica** - José Miguel Carrera 825 (134)
5. **SAMU** - Ambulancias y atención pre-hospitalaria (131)
6. **Emergencias Municipales** - +56 9 5802 6520 (24 horas)

Todos los servicios incluyen información real: direcciones, teléfonos, emails y sitios web verificados.



## 🔒 Privacidad

- Todos los datos se almacenan localmente en tu navegador
- No se envía información a ningún servidor
- Tus datos permanecen privados en tu dispositivo

## 🛠️ Personalización

### Cambiar Colores
Edita las variables CSS en `index.css`:
```css
:root {
    --color-primary: hsl(260, 85%, 60%);
    --color-secondary: hsl(320, 85%, 60%);
    --color-accent: hsl(180, 85%, 55%);
}
```

### Agregar Nuevas Categorías
1. Agrega un nuevo botón de pestaña en `index.html`
2. Actualiza el array de categorías en `app.js`
3. Agrega el ícono correspondiente en `getCategoryIcon()`

### Modificar Campos del Formulario
Edita el formulario en `index.html` y actualiza la función `handleFormSubmit()` en `app.js`

## 📱 Compatibilidad

- ✅ Chrome (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Dispositivos móviles

## 💡 Consejos de Uso

1. **Usa etiquetas descriptivas** - Facilitan la búsqueda
2. **Completa todos los campos** - Mejor información para los usuarios
3. **Actualiza regularmente** - Mantén la información al día
4. **Haz respaldos** - Exporta tus datos periódicamente (función futura)

## 🚀 Mejoras Futuras

- [ ] Exportar/Importar datos (JSON, CSV)
- [ ] Modo claro/oscuro toggle
- [ ] Mapas integrados para ubicaciones
- [ ] Galería de imágenes por servicio
- [ ] Sistema de comentarios y reseñas
- [ ] Compartir servicios por enlace
- [ ] Estadísticas y reportes
- [ ] Modo offline completo (PWA)

## 📄 Licencia

Este proyecto es de código abierto y está disponible para uso personal y comercial.

## 👨‍💻 Desarrollo

Desarrollado con ❤️ usando tecnologías web modernas.

---

**¿Preguntas o sugerencias?** ¡Abre un issue o contribuye al proyecto!

🌟 Si te gusta este proyecto, ¡dale una estrella!
