# 🐾 Vet Care - Sistema para la veterinaria "Huellitas"

Sistema web de gestión de citas, pacientes, propietarios, servicios y atención clínica para la clínica veterinaria **"Huellitas"**.

---

## 🌐 Enlace a GitHub Pages

> 🔗 **Demo en vivo:** `[Enlace pendiente — agregar URL de GitHub Pages aquí]`

---

## 📋 Descripción del Proyecto

**Vet Care** es una aplicación web estática multipágina diseñada para digitalizar y organizar los flujos de trabajo diarios de la clínica veterinaria **"Huellitas"**. La interfaz está estructurada por roles de usuario para cubrir las necesidades operativas de cada área de la clínica:

- **Recepcionista:** Gestión integral (CRUD) de propietarios y mascotas, así como programación, reprogramación, cancelación y consulta de citas.
- **Veterinario:** Consulta de agenda de citas, registro de atención médica y búsqueda/visualización detallada del historial clínico de los pacientes.
- **Administrador:** Panel de control administrativo y gestión integral (CRUD) de veterinarios y servicios ofrecidos por la clínica.

---

## 🗂️ Estructura del Repositorio

```text
VetCare/
├── index.html                          # Página principal / punto de entrada
├── css/
│   └── styles.css                      # Hoja de estilos unificada del sistema
├── docs/                               # Documentación del proyecto
└── pages/
    ├── administrador/                  # Módulo de administración
    │   ├── admin-dashboard.html
    │   ├── servicios/                  # Gestión de servicios (listado, nuevo, editar, eliminar)
    │   └── veterinarios/               # Gestión de veterinarios (listado, nuevo, editar, eliminar)
    ├── recepcionista/                  # Módulo de recepción
    │   ├── recepcionista-dashboard.html
    │   ├── citas/                      # Gestión de citas (listado, agendar, reprogramar, cancelar)
    │   ├── mascotas/                   # Gestión de mascotas (listado, nuevo, editar, eliminar)
    │   └── propietarios/               # Gestión de propietarios (listado, nuevos, editar, eliminar)
    └── veterinario/                    # Módulo de atención veterinaria
        ├── citas/                      # Agenda y registro de atención médica
        └── historial/                  # Búsqueda y detalle de historiales clínicos
```

---

## 🤝 Metodología de Trabajo

El desarrollo del sistema se planificó de manera colaborativa mediante reuniones de equipo para:
1. **Definir el diagrama de casos de uso** general del sistema.
2. **Priorizar los casos de uso** asignados de forma individual por cada integrante.
3. **Debatir y validar en consenso** la priorización final, asegurando coherencia en el alcance, la navegación y la experiencia de usuario.

---

## 👥 Integrantes y Reparto del Trabajo

| Integrante | Rol y Responsabilidades | Vistas / Pestañas Desarrolladas |
| :--- | :--- | :--- |
| **Erick Bajaña** | • Gestor del grupo.<br>• Definición de los estilos CSS generales.<br>• Redacción de la visión del proyecto.<br>• Descripción de **3 casos de uso**.<br>• Revisión de entregables y documentación. | **7 pestañas:**<br>• `index.html`<br>• `recepcionista-dashboard.html`<br>• `propietarios-listado.html`<br>• `mascotas-listado.html`<br>• `citas-listado.html` (Recepción)<br>• `citas-listado.html` (Veterinario)<br>• `buscar-historial.html` |
| **Andrés Veas** | • Unificación de los estilos de cada integrante en un único archivo `css/styles.css`.<br>• Descripción de **3 casos de uso**.<br>• Elaboración de los mocks de la aplicación.<br>• Diseño del mapa navegacional. | **6 pestañas (operaciones CRUD):**<br>• `propietarios-nuevos.html`<br>• `propietarios-editar.html`<br>• `propietarios-eliminar.html`<br>• `mascotas-nuevo.html`<br>• `mascotas-editar.html`<br>• `mascotas-eliminar.html` |
| **Franciel Tipantuña** | • Descripción de **2 casos de uso**.<br>• Revisión final del mapa navegacional. | **7 pestañas (Módulo Administrador, excepto dashboard y listado de veterinarios):**<br>• `servicios-listado.html`<br>• `servicios-nuevo.html`<br>• `servicios-editar.html`<br>• `servicios-eliminar.html`<br>• `veterinarios-nuevo.html`<br>• `veterinarios-editar.html`<br>• `veterinarios-eliminar.html` |
| **Sabina Zabala** | • Descripción de **2 casos de uso**.<br>• Validación de todas las páginas con los validadores oficiales de **W3C**. | **7 pestañas (vistas restantes):**<br>• `admin-dashboard.html`<br>• `veterinarios-listado.html`<br>• `citas-agendar.html`<br>• `citas-reprogramar.html`<br>• `citas-cancelar.html`<br>• `atencion-registrar.html`<br>• `historial-detalle.html` |

---

## 🛠️ Tecnologías y Estándares

- **HTML5:** Maquetación semántica validada bajo estándares **W3C**.
- **CSS3:** Diseño unificado y centralizado en [`css/styles.css`](css/styles.css).
