# Sistema de Registro de Visitantes (CRUD con Tkinter)

##  Descripción

Este proyecto consiste en una aplicación de escritorio desarrollada en Python utilizando la librería Tkinter.
El sistema permite gestionar el registro de visitantes en una oficina mediante operaciones CRUD (Crear, Leer, Actualizar y Eliminar), aplicando una arquitectura modular por capas.

---

##  Objetivo

Desarrollar una aplicación que demuestre el uso de:

* Programación Orientada a Objetos (POO)
* Arquitectura modular (Modelo, Servicio, UI, Main)
* Separación entre lógica de negocio e interfaz gráfica

---

## Estructura del Proyecto

```
visitas_app/
│
├── main.py                # Punto de entrada de la aplicación
├── modelos/
│   └── visitante.py       # Clase Visitante (Modelo)
├── servicios/
│   └── visita_servicio.py # Lógica CRUD
└── ui/
    └── app_tkinter.py     # Interfaz gráfica
```

---

## Funcionalidades

El sistema permite:

* Registrar un nuevo visitante
* Visualizar visitantes en una tabla (Treeview)
* Eliminar un visitante seleccionado
* Actualizar los datos de un visitante
* Limpiar los campos del formulario

---

## Funcionamiento del Programa

1. Al ejecutar el programa, se abre una ventana con un formulario de entrada.
2. El usuario ingresa:

   * Cédula
   * Nombre
   * Motivo de la visita
3. Al presionar **Registrar**, el visitante se guarda en memoria y se muestra en la tabla.
4. Al seleccionar un registro en la tabla:

   * Los datos se cargan automáticamente en el formulario.
5. El usuario puede:

   * Modificar los datos y presionar **Actualizar**
   * O eliminar el registro con el botón **Eliminar**
6. El botón **Limpiar** borra los campos del formulario.

---

## Notas

* Los datos se almacenan en memoria, por lo que se eliminan al cerrar el programa.
* No se utilizan librerías externas, solo módulos estándar de Python.

---

## Autor

Leiber Correa
Proyecto académico - Programación Orientada a Objetos
