# Proyecto Final de Python - Configuración de Entorno

## Comandos Ejecutados

A continuación se detallan los comandos utilizados en la terminal para configurar el proyecto:

1.  **Creación y Navegación de Directorio:**
    ```bash
    mkdir python-final
    cd python-final
    ```

2.  **Inicialización de Repositorio Git:**
    ```bash
    git init
    ```

3.  **Creación de Archivo Python:**
    ```bash
    touch finales.py
    ```

4.  **Apertura en Visual Studio Code:**
    ```bash
    code .
    ```

5.  **Verificación de Versión de Python:**
    ```bash
    python -V
    python3 -V
    ```
    *(Nota: Se verificó la versión instalada de Python. En sistemas Windows, el comando `python -V` suele ser el más efectivo dentro del entorno virtual.)*

6.  **Creación de Entorno Virtual:**
    ```bash
    python3 -m venv venv
    ```
    *(Esto crea un entorno virtual aislado para el proyecto.)*

7.  **Activación del Entorno Virtual:**
    * **Linux/macOS (o Git Bash):**
        ```bash
        source venv/bin/activate
        ```
    * **Windows (CMD/PowerShell, y la forma correcta para Git Bash si el entorno se creó con estructura de Windows):**
        ```bash
        source venv/Scripts/activate
        ```
    *(La aparición de `(venv)` en el prompt de la terminal indica que el entorno está activo.)*

8.  **Actualización de Pip:**
    ```bash
    python -m pip install --upgrade pip
    ```
    *(Se actualizó el gestor de paquetes pip a su última versión dentro del entorno virtual.)*

---

## ¿Qué es Pip y por qué lo actualizamos?

### ¿Qué es Pip?
**Pip** es el **gestor de paquetes estándar de Python**. Es una herramienta de línea de comandos que permite instalar, desinstalar y gestionar librerías y módulos de Python que no vienen preinstalados con el lenguaje. Estos paquetes se obtienen generalmente del Python Package Index (PyPI), un vasto repositorio de software Python. La sigla PIP se asocia comúnmente con "Pip Installs Packages".

### ¿Por qué lo actualizamos?
Actualizamos `pip` regularmente por las siguientes razones:
* **Acceso a Nuevas Funcionalidades:** Las versiones más recientes de `pip` pueden incluir mejoras en la forma en que gestiona las dependencias o en su interfaz de usuario.
* **Corrección de Errores y Seguridad:** Las actualizaciones resuelven bugs y parches de seguridad que pueden afectar la estabilidad o la protección de tus instalaciones de paquetes.
* **Mejor Compatibilidad:** Nuevas librerías y versiones de Python a menudo requieren versiones más recientes de `pip` para una instalación sin problemas. Mantenerlo actualizado asegura que `pip` pueda manejar las últimas especificaciones de paquetes.
* **Mejoras de Rendimiento:** Las actualizaciones pueden optimizar el proceso de instalación, haciéndolo más rápido y eficiente.

---

## Historial de Commits

* **Primer Commit:** Se documenta la configuración inicial del entorno de desarrollo y la creación del archivo `finales.py`.
    * Mensaje: `Primer commit: Configuración inicial del proyecto y entorno virtual`

---

Autor: [Tapia Ximena]
Fecha: 30 de junio de 2025
