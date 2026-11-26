# AED-1026 Estructura de Datos — Unidad 6: Métodos de Búsqueda

**Institución:** Instituto Tecnológico Superior de Xalapa (ITSX)  
**Carrera:** Ingeniería en Sistemas Computacionales  
**Materia:** AED-1026 Estructura de Datos  
**Docente:** Víctor Hugo Vásquez Herrera  

---

## Descripción del Proyecto

Este repositorio contiene la implementación en Java de las prácticas correspondientes a la **Unidad 6: Métodos de Búsqueda**, enfocadas en comprender la lógica de funcionamiento, requisitos previos y eficiencia de los algoritmos fundamentales de búsqueda sobre arreglos unidimensionales:

1. **Práctica 1 (`PracticaBusquedaSecuencial.java`):** Implementación de la búsqueda lineal/secuencial recorriendo elemento por elemento hasta localizar la clave solicitada o alcanzar el final del arreglo.
2. **Práctica 2 (`PracticaBusquedaBinaria.java`):** Implementación de la búsqueda binaria sobre un arreglo previamente ordenado de menor a mayor, dividiendo el espacio de búsqueda a la mitad en cada iteración.

---

## Estructura del Repositorio

```text
├── PracticaBusquedaSecuencial.java   # Código fuente de la Práctica 1
├── PracticaBusquedaBinaria.java       # Código fuente de la Práctica 2
└── README.md                          # Documentación e instrucciones de ejecución


## Requisitos Previos

* Tener instalado el **Java Development Kit (JDK)** (versión 8 o superior).
* Verificar que el compilador y el entorno de ejecución funcionen correctamente abriendo una terminal y ejecutando:

```bash
java -version
javac -version
```

---

## Instrucciones Paso a Paso para Compilar y Ejecutar

1. **Clonar o descargar el repositorio:**
   Descarga los archivos `.java` en una misma carpeta o clona el repositorio desde la terminal:

```bash
git clone <URL-DE-TU-REPOSITORIO>
cd <NOMBRE-DE-LA-CARPETA>
```

2. **Compilar los archivos fuente (`.java` a `.class`):**
   Ubícate en la carpeta donde se encuentran los archivos y ejecuta el compilador `javac` para cada práctica:

```bash
javac PracticaBusquedaSecuencial.java
javac PracticaBusquedaBinaria.java
```

*(Nota: Si no aparecen errores en la terminal, se generarán automáticamente los archivos `PracticaBusquedaSecuencial.class` y `PracticaBusquedaBinaria.class`).*

3. **Ejecutar los programas:**

### Práctica 1: Búsqueda Secuencial
```bash
java PracticaBusquedaSecuencial
```

**Salida esperada en consola:**
```text
Posicion de 88: 3
Posicion de 100: -1
```

### Práctica 2: Búsqueda Binaria
```bash
java PracticaBusquedaBinaria
```

**Salida esperada en consola:**
```text
Indice de 173: 5
Indice de 130: -1
```
