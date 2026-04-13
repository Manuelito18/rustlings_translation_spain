# Rustlings (Traducción al Español) 🦀

![Rust](https://img.shields.io/badge/Rust-%23E05D44.svg?style=flat-square&logo=rust&logoColor=white)
![Rust Edition](https://img.shields.io/badge/Edition-2021-blue?style=flat-square&logo=rust)
![Cargo Build](https://img.shields.io/badge/Cargo-Build-success?style=flat-square&logo=rust)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white)
![Español](https://img.shields.io/badge/Idioma-Español-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)
![Fork](https://img.shields.io/badge/Fork-Original_Repo-orange.svg?style=flat-square)
![Mantenido por](https://img.shields.io/badge/Mantenido_por-Manuelito18-FF69B4?style=flat-square&logo=github)

**Rustlings** es una colección de pequeños ejercicios diseñados para que te acostumbres a leer y escribir código en [Rust](https://www.rust-lang.org).

> [!IMPORTANT]
> Este repositorio es un **fork** del proyecto original. Su objetivo es localizar y traducir íntegramente los ejercicios, pistas (_hints_) y la interfaz de usuario al **español** para eliminar la barrera del idioma en el aprendizaje de Rust.

---

## 🚀 ¿Qué incluye esta versión?

- ✅ **Ejercicios localizados:** Enunciados y comentarios traducidos al español.
- ✅ **Pistas (Hints) claras:** Ayuda directa en tu idioma para cuando te quedes atascado.
- ✅ **CLI en español:** Mensajes de error, éxito e instrucciones de la terminal traducidos.
- ✅ **Guía recomendada:** Ideal para usar junto al libro [El Lenguaje de Programación Rust](https://doc.rust-lang.org/book/title-page.html).

---

## 🛠️ Instalación y Configuración

| Método         | Sistema Operativo   | Comando                                                                                                                                        |
| :------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------- |
| **Automático** | 🐧 Linux / 🍎 macOS | `curl -L https://raw.githubusercontent.com/Manuelito18/rustlings_translation_spain/main/install.sh \| bash`                                    |
| **PowerShell** | 🪟 Windows          | `iwr -useb https://raw.githubusercontent.com/Manuelito18/rustlings_translation_spain/main/install.ps1 \| iex`                                  |
| **Manual**     | 🛠️ Todas (Cargo)    | `git clone https://github.com/Manuelito18/rustlings_translation_spain.git && cd rustlings_translation_spain && cargo install --force --path .` |

---

### ⚠️ Importante: Configuración del PATH (Linux)

Si tras la instalación el comando `rustlings` no es reconocido (especialmente común en distribuciones como **Arch Linux**), debes añadir los binarios de Cargo a tu variable de entorno:

1.  Abre tu archivo de configuración (`.bashrc`, `.zshrc` o tu script de inicio en Hyprland).
2.  Añade la siguiente línea:
    ```bash
    export PATH="$HOME/.cargo/bin:$PATH"
    ```
3.  Recarga tu configuración: `source ~/.bashrc` (o el archivo que corresponda).

---

### 🪟 Notas para Windows

- Ejecuta PowerShell como **Administrador**.
- Si el script falla por permisos, ejecuta primero: `set-executionpolicy remotesigned -scope currentuser`.
- Requiere las _Build Tools para Visual Studio_ instaladas.

---

## 🎮 Cómo utilizar Rustlings

El flujo de trabajo está optimizado para una experiencia fluida en la terminal:

1.  **Inicia el modo observación:**
    ```bash
    rustlings watch
    ```
2.  **Resuelve los ejercicios:**
    Ve a la carpeta `exercises/`. Los archivos están numerados; ábrelos con tu editor preferido (como `nano` o `vim`) y corrige el código para que compile.
3.  **Verificación:**
    Al guardar el archivo, la terminal se actualizará automáticamente. Si necesitas una ayuda extra, escribe `hint` en el prompt de Rustlings.

---

## 🤝 Contribuciones

¿Viste una traducción que suena extraña o quieres mejorar una explicación? ¡Tu ayuda es valiosa!

1.  Haz un **Fork** del proyecto.
2.  Crea una rama para tu mejora: `git checkout -b feature/mejorar-traduccion`.
3.  Envía un **Pull Request**.

---

## 🔗 Enlaces de interés

- [Repositorio Original (Inglés)](https://github.com/rust-lang/rustlings)
- [Comunidad Rust en Español](https://rustlang-es.org/)

---

**Mantenido con ❤️ por [Manuelito18](https://github.com/Manuelito18)**
