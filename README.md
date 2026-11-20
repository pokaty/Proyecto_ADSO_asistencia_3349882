# Proyecto ADSO — Sistema de control de asistencias

Aplicación para el control de asistencias de los aprendices del programa ADSO (SENA – CDITI).

## Integrantes

| Nombre | Rol |
|---|---|
| _Valeria Galindo Hernandez_ | Frontend |
| _Yeison Valencia Zapata_ | Backend |
| _Emmanuel Grajales Molina_ | Base de datos |

La documentación está repartida entre los tres integrantes. Todos pueden apoyar en cualquier área.

## Tecnologías

_Por definir._

## Estructura del repositorio

```
proyecto-adso/
├── documentacion/
│   ├── 01-analisis/        requisitos, historias de usuario, casos de uso
│   ├── 02-diseno/          informe de diseño, mockups y diagramas
│   ├── 03-pruebas/         plan de pruebas, casos y evidencias
│   ├── 04-manuales/        manual de usuario y manual técnico
│   ├── 05-gestion/         cronograma, actas de reunión, roles
│   └── 06-entrega-final/   informe final y presentación de la sustentación
├── desarrollo/
│   ├── frontend/
│   ├── backend/
│   └── base-de-datos/      scripts SQL (esquema y datos de prueba)
└── recursos/               logos, imágenes compartidas, bibliografía
```

## Cómo ejecutar el proyecto

_Se completa cuando exista la primera versión._

## Flujo de trabajo con Git

- La rama `main` siempre debe funcionar; nadie sube cambios directamente a ella.
- Cada tarea va en su propia rama, por ejemplo `front/login`, `back/api-asistencias`, `bd/script-inicial` o `docs/manual-usuario`.
- Los cambios se unen a `main` mediante un Pull Request revisado por otro integrante.
- Los commits son cortos y describen qué se hizo.
- Nunca se suben contraseñas ni claves: se usa un archivo `.env` local y se comparte un `.env.example`.
