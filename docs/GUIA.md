# Guía del Proyecto: Laboratorio 03

Documentación del trabajo de colaboración en Git y GitHub.

## Requisitos Previos

- Tener instalado Git en el sistema.
- Cuenta activa en GitHub.
- Editor de código Visual Studio Code.

### Pasos de Configuración y Uso

1. Clonar el repositorio a la computadora local.
2. Crear una rama de trabajo para los cambios.
3. Subir las modificaciones mediante commits y push.

## Lista de Tareas

- [x] Configuración del entorno local
- [x] Creación e integración de ramas
- [ ] Publicación final de la documentación

## Archivos y Comandos

| Nombre       | Tipo    | Descripción                       |
| ------------ | ------- | --------------------------------- |
| `index.html` | Archivo | Estructura del proyecto           |
| `git status` | Comando | Muestra el estado del repositorio |
| `git push`   | Comando | Sube los cambios al remoto        |

## Comandos Utilizados

Para verificar la rama actual ejecuta el comando `git branch`.

```bash
git checkout -b nueva-rama
```

---

### Paso 3: Enlazar la guía en el `README.md` principal

1. Abre el archivo `README.md` ubicado en la raíz de tu proyecto.
2. Agrega la siguiente sección al final de todo el archivo:

```markdown
## Documentación Adicional

- [Guía del proyecto](docs/GUIA.md)
```
