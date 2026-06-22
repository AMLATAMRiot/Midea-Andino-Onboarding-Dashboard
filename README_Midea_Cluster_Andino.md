# Midea Cluster Andino — Onboarding Guide

Guía viva de onboarding para centralizar procesos, accesos, flujos de trabajo y puntos de validación del nuevo Cluster Andino de Midea.

Este repositorio debe funcionar como una fuente única de consulta para equipos nuevos o existentes que necesiten entender cómo opera la cuenta, qué procesos están documentados y qué información sigue pendiente de validar.

## Objetivo

- Facilitar el onboarding del equipo del Cluster Andino.
- Documentar workflows clave por área: Producción, Redes Sociales, Paid Media, Ecommerce, Contactos y Transferencia Digital.
- Mantener visibilidad sobre pendientes de validación.
- Evitar pérdida de conocimiento cuando cambien responsables, mercados o procesos.
- Reducir dependencia de información informal en correos, chats o archivos sueltos.

## Mercados contemplados

| Mercado | Estado | Notas |
|---|---|---|
| Colombia | Activo | Base inicial del documento. |
| Ecuador | Próximo | Se debe documentar al iniciar operación. |
| Venezuela | Próximo | Se debe documentar al iniciar operación. |
| Centroamérica | Referencia operativa | Puede servir como benchmark según procesos existentes. |

## Estructura sugerida del repositorio

```text
midea-cluster-andino-onboarding/
├── README.md
├── onboarding/
│   └── Midea_Cluster_Andino_Onboarding_v1.3.html
├── docs/
│   ├── production.md
│   ├── social-media.md
│   ├── paid-media.md
│   ├── ecommerce.md
│   └── digital-transfer.md
├── templates/
│   ├── brief-template.md
│   ├── approval-tracker.md
│   └── reporting-checklist.md
├── assets/
│   └── brand-guidelines/
└── changelog.md
```

## Estado de las secciones

| Sección | Estado | Acción recomendada |
|---|---|---|
| Producción | Completo | Revisar trimestralmente o cuando cambie el flujo de producción. |
| Redes Sociales | Validar | Confirmar proceso de parrilla, aprobación, publicación, CM y crisis. |
| Paid Media | Borrador — Validar | Confirmar accesos, SLAs, tiempos de setup y modelo de reportes. |
| Ecommerce | Borrador — Validar | Confirmar gestión de sitio, fichas, banners, retailers y responsables. |
| Contactos | Completo | Mantener actualizado por rol y evitar datos personales innecesarios. |
| Transferencia Digital | Validar | Confirmar ownership, permisos, credenciales, país, moneda y escalamiento. |

## Reglas de documentación

1. Usar roles antes que nombres personales cuando el proceso no dependa de una persona específica.
2. No guardar contraseñas, tokens, códigos 2FA ni credenciales en el repositorio.
3. No publicar correos personales ni información sensible.
4. Marcar cada sección con uno de estos estados: `Completo`, `Validar`, `Pendiente` o `Deprecated`.
5. Registrar cambios relevantes en `changelog.md`.
6. Cada proceso debe incluir: objetivo, responsable por rol, inputs requeridos, pasos, herramientas, SLA esperado y ruta de escalamiento.

## Cómo actualizar la guía HTML

1. Editar el archivo ubicado en `onboarding/`.
2. Actualizar versión y fecha en la portada.
3. Cambiar el estado de la sección si aplica.
4. Validar que los links internos, botones y tabs funcionen correctamente.
5. Subir cambios mediante Pull Request.
6. Agregar una nota corta en `changelog.md`.

## Checklist para nuevas incorporaciones

- [ ] Leer la guía completa de onboarding.
- [ ] Revisar el estado de cada sección.
- [ ] Confirmar qué procesos están validados y cuáles siguen pendientes.
- [ ] Solicitar accesos a plataformas necesarias.
- [ ] Revisar flujos de aprobación y tiempos esperados.
- [ ] Identificar rutas de escalamiento por área.
- [ ] Consultar el changelog para entender cambios recientes.

## Transferencia digital — puntos críticos

Antes de ejecutar cualquier transferencia de activos digitales, validar:

- Business Manager correcto.
- País y moneda de cuentas publicitarias.
- Método de pago.
- Administrador principal.
- Permisos de agencia como partner.
- Credenciales en gestor seguro.
- Propiedad de Meta, Instagram, TikTok y YouTube.
- Ruta de escalamiento con Midea Colombia, México y China.

## Buenas prácticas de seguridad

- Usar un gestor de contraseñas corporativo.
- Activar 2FA donde aplique.
- Evitar compartir accesos por WhatsApp o correos abiertos.
- Revocar accesos de usuarios que ya no participan en la operación.
- Revisar permisos al menos una vez por trimestre.

## Changelog recomendado

Ejemplo de formato:

```md
## v1.3 — Junio 2026
- Se actualizó el documento para posicionarlo como guía viva del Cluster Andino.
- Se eliminó owner nominal y correo de la pestaña de Redes Sociales.
- Se cambió Transferencia Digital a estado Validar.
- Se agregó bloque de reglas de mantenimiento del documento.
```

## Mantenimiento

Este documento debe revisarse cada vez que:

- Ingrese un nuevo mercado al cluster.
- Cambie un responsable operativo.
- Cambie el flujo de aprobación.
- Se cree o migre una cuenta digital.
- Se actualicen SLAs, herramientas o formatos de reporte.

