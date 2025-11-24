```markdown
# 🌱 Wotoch – Donaciones con Propósito  
> Plataforma web que conecta a quienes ya no necesitan algo con quienes aún lo necesitan, impulsando los Objetivos de Desarrollo Sostenible (ODS) 11, 12 y 13.

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-en%20desarrollo-yellow.svg)](https://github.com/tu-usuario/wotoch/tree/front-end)

---

## 📌 ¿Qué es Wotoch?
Wotoch es un **marketplace de donaciones** sin fines de lucro que facilita:
- Publicar objetos en buen estado.
- Buscar y solicitar artículos cercanos geográficamente.
- Acordar puntos de entrega seguros y horarios compatibles.
- Generar **métricas de impacto ambiental** (kg de CO₂ evitado, residuos desviados, etc.).

---

## 🎯 Objetivos de Desarrollo Sostenible
| ODS | Color brand | Enfoque |
|-----|-------------|---------|
| **11** ‑ Ciudades sostenibles | `#E66A27` | Fomentar economía circular local |
| **12** ‑ Producción responsable | `#C99933` | Extender vida útil de productos |
| **13** ‑ Acción por el clima | `#408246` | Reducir emisiones vía reutilización |

---

## 🗺️ Diagrama de flujo general
Accede al mapa completo de procesos y casos de uso:  
🔗 [Lucidchart – Wotoch Flow](https://lucid.app/lucidchart/d254030a-4693-4ec3-8a98-662c5f355852/edit?view_items=IAwLaaGdBQIP&page=0_0&invitationId=inv_f0496778-b23d-48ff-af34-8d1640841b2a)

---

## 📊 Backlog & Roadmap
Plan de tareas, responsables y fechas (Google Sheets público):  
🔗 [Wotoch Backlog](https://docs.google.com/spreadsheets/d/18nbPCQ-pjm2xrMYsJirmiHzWuVViae6b/edit?gid=1535348654#gid=1535348654)

---

## 🧪 Tecnologías
| Capa | Stack |
|------|-------|
| **Front-end** | HTML5, Tailwind CSS 3, JavaScript vanilla |
| **Back-end** | Java 17, Servlet API, MySQL 8 |
| **Entorno local** | XAMPP (Apache + MySQL) |
| **Repo** | GitHub Flow – rama `front-end` protegida vía PR |

---

## 🚀 Instalación local (XAMPP)
1. Clona el repo dentro de `htdocs`:
   ```bash
   git clone https://github.com/tu-usuario/wotoch.git C:/xampp/htdocs/wotoch
   ```
2. Inicia **Apache** y **MySQL** desde el panel de XAMPP.
3. Importa la base de datos:
   ```sql
   mysql -u root < database/wotoch.sql
   ```
4. Accede a:
   ```
   http://localhost/wotoch/index.html
   ```

---

## 📂 Estructura del proyecto
```
wotoch/
├─ database/          # Scripts SQL
├─ src/               # Código Java (DAO, Servlets)
├─ web/               # Assets del front
│  ├─ css/            # styles.css, styleInicio.css
│  ├─ js/             # main.js, mobile-*.js
│  ├─ img/            # Imágenes públicas
│  └─ *.html          # Vistas (index, como-funciona, quienes-somos)
├─ README.md
└─ LICENSE
```

---

## 🔧 Funcionalidades clave implementadas
### Frontend
- **Navbar universal responsivo** con menú hamburguesa sin solapamiento
- **Modales login/registro** accesibles desde cualquier vista
- **Tooltips informativos** con posicionamiento manual mobile-first
- **Optimización móvil** para pantallas ≤ 375px
- **Animaciones suaves** con CSS transitions

### Backend (en desarrollo)
- **Servlet de autenticación** con validación en tiempo real
- **DAO pattern** para acceso a datos
- **Métricas de impacto ambiental** calculadas automáticamente

---

## 🧪 Cómo contribuir
1. Crea un fork y una rama desde `front-end`.
2. Nombra tu rama: `feat/login-modal` o `fix/navbar-z-index`.
3. Asegura **Lighthouse ≥ 95** en Performance y Accesibilidad.
4. Abre **Pull Request** con capturas de móvil y desktop.

---

## 📄 Licencia
MIT – ver archivo [LICENSE](LICENSE).

---

## 📬 Contacto
¿Dudas o sugerencias?  
Abre un **Issue** o escríbenos a: **wotoch@tudominio.com**

---
**¡Juntos hacemos del planeta un lugar mejor, una donación a la vez!** 🌍💚
```
