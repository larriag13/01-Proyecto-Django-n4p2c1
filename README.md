# 01-Proyecto-Django-n4p2c1

**Autor:** Luis Arriagada

A continuación se detallan los comandos iniciales de Git necesarios para configurar y descargar el proyecto:

### 1. Clonar el repositorio

```bash
git clone <url_del_repositorio>
```

**Explicación:** Este comando descarga una copia exacta de un repositorio remoto y la guarda en tu directorio local para que puedas trabajar en los archivos de tu proyecto.

### 2. Revisar la configuración actual

```bash
git config --global --list
```

**Explicación:** Muestra un listado con todas las configuraciones globales que tienes actualmente en Git. Es muy útil para verificar rápidamente qué nombre de usuario y correo electrónico están activos en tu equipo.

### 3. Configurar el nombre de usuario

```bash
git config --global user.name "nombre_usuario"
```

**Explicación:** Establece el nombre que quedará registrado como autor cada vez que guardes cambios (hagas un *commit*) en el control de versiones.

### 4. Configurar el correo electrónico

```bash
git config --global user.email "luis.arriagada13@inacapmail.cl"
```

**Explicación:** Asocia esta dirección de correo electrónico a tus *commits*. Es importante que este correo coincida con el que utilizas en tu plataforma de repositorios (como GitHub o GitLab) para que tus aportes se enlacen correctamente a tu cuenta.

---
**Nota:** Si necesitas aplicar el nombre o el correo solo para este proyecto en particular (y no en todo tu equipo de forma general), puedes omitir la opción `--global` en los comandos de configuración.