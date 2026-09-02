# User Settings Manager

A simple Python project for managing user configuration settings stored in a dictionary.

## Features

* Add new settings
* Update existing settings
* Delete settings
* Display current settings
* Validate existing keys
* Normalize keys and values to lowercase

## Example

```python
settings = {
    "theme": "light",
    "notifications": "enabled",
    "volume": "low"
}

add_setting(settings, ("language", "English"))
update_setting(settings, ("theme", "Dark"))
delete_setting(settings, "volume")

print(view_settings(settings))
```

## Concepts Practiced

* Functions and parameters
* Dictionaries and tuples
* Loops and conditionals
* String methods
* f-strings
* Dictionary manipulation
* Return values

## Requirements

* Python 3.x

## Run

```bash
python settings.py
```
---

# Administrador de Configuración de Usuario

Un proyecto sencillo en Python para gestionar configuraciones de usuario almacenadas en un diccionario.

## Funciones

* Agregar nuevas configuraciones
* Actualizar configuraciones existentes
* Eliminar configuraciones
* Mostrar las configuraciones actuales
* Verificar si una clave ya existe
* Convertir claves y valores a minúsculas

## Ejemplo

```python
settings = {
    "theme": "light",
    "notifications": "enabled",
    "volume": "low"
}

add_setting(settings, ("language", "English"))
update_setting(settings, ("theme", "Dark"))
delete_setting(settings, "volume")

print(view_settings(settings))
```

## Conceptos Practicados

* Funciones y parámetros
* Diccionarios y tuplas
* Bucles y condicionales
* Métodos de strings
* f-strings
* Manipulación de diccionarios
* Valores de retorno

## Requisitos

* Python 3.x

## Ejecución

```bash
python settings.py
```
