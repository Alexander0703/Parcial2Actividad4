💳 Tarjeta Personal — Alexander Ivanov
HTML5
CSS3
Responsive
Una elegante tarjeta personal con diseño moderno en tema oscuro y acentos rojos, perfecta para presentación profesional en línea.
Descripción y características
- Tema oscuro elegante con acentos rojo/carmesí, gradientes y efectos de glow.
- Diseño responsive Mobile‑First, optimizado para móviles y escritorio.
- Efectos interactivos: hover, sombras, transiciones suaves y elevación.
- Tarjeta informativa: foto de perfil, nombre, descripción corta y botones de contacto.
- Formulario/Acciones (opcional): enlaces a redes o descarga de vCard si se añade JS.
Comenzar (instalación y uso)
Clona el repositorio y abre localmente:
git clone https://github.com/Alexander0703/Parcial2Actividad2.git
cd Parcial2Actividad2


Opciones para ver el proyecto:
- Abrir directamente (rápido):
- Abre index.html con tu navegador.
- Servir con un servidor local (recomendado si usas fetch o rutas relativas):
- Con Python 3:
python -m http.server 8000
# luego visita http://localhost:8000
- Con Node (http-server):
npx http-server
- Con PHP:
php -S localhost:8000


Estructura del proyecto:
Parcial2Actividad4/
- index.html          # Página principal con la tarjeta
- style.css           # Estilos CSS (tema oscuro/rojo)
- foto.jpg            # Foto de perfil (reemplazar)
- README.md           # Este archivo


Diseño y personalización
- Colores principales
- Fondo: #000000 → #1a1a1a (gradiente sutil)
- Acento: #dc3545 / #b91c1c (rojo carmesí)
- Texto: #ffffff / #cccccc
- Variables CSS recomendadas
:root{
  --bg: #0a0a0a;
  --card: #1a1a1a;
  --accent: #dc3545;
  --text: #ffffff;
  --muted: #cccccc;
}


- Sugerencias de personalización
- Reemplaza foto.jpg por tu imagen (ideal 1:1).
- Cambia nombre y frase en index.html.
- Ajusta .card { max-width: 320px; padding: 1.5rem; } para tamaños.
- Añade animaciones con @keyframes fadeInUp o transform: translateZ(0) para mejorar rendimiento.
- Ejemplo de efecto hover (botón)
.button{
  background: linear-gradient(90deg, var(--accent), #b91c1c);
  transition: transform .18s ease, box-shadow .18s ease;
}
.button:hover{
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(220,53,69,.18);
}


Tecnologías y compatibilidad
- HTML5 — marcado semántico.
- CSS3 — Variables, Flexbox, Media Queries, transiciones.
- Compatibilidad: Chrome, Firefox, Safari, Edge y dispositivos iOS/Android recientes.
- Opcional: JavaScript para validación, interactividad o vCard.
Contribuciones, licencia y contacto
- Contribuciones
- Haz Fork del repositorio.
- Crea una rama: git checkout -b feature/nombre-feature.
- Haz commits claros: git commit -m "feat: descripción corta".
- Push y abre Pull Request.
- Licencia
- MIT — revisa el archivo LICENSE del repositorio para detalles.
- Repositorio y contacto
- Repo: https://github.com/Alexander0703/Parcial2Actividad2.git
- Autor: Alexander Ivanov Ruiz Clemente
