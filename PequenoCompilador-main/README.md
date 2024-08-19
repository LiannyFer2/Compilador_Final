# Pequeño Compilador
Creación de un pequeño compilador


# Tarea Semana 7
Leer Capítulo 7 del Libro Compiladores, Principios, Técnicas.

Tarea de investigación sobre el entorno de ejecución en los compiladores. Esta tarea debe ser subida en formato PDF a la plataforma antes del Domingo a las 12:00 am.  

Recordar que todo debe ser con sus palabras. Tarea con Plagio tendra 0 de calificación automáticamente

# Investigar
- Entorno de Ejecución
- Organización de la memoria en tiempo de ejecución.
- Estrategias de asignación de memoria.
- Acceso a variables locales, no locales y globales.
- Paso de parámetros.



# Ejercicios y Presentación con los demás compañeros:
1)    Crear un pequeño Compilador con las siguientes características:

      a.    Analizador Léxico.

      b.    Analizador Sintáctico.

      c.    Analizador Semántico. (Opcional)

      d.    Generar Tabla de Símbolos.

      e.    Generador de Código Intermedio.

      f.     Lenguaje de programación a traducir el código del compilador.

      (Utilizar cualquier herramienta) en el Lenguaje de programación de su preferencia.

2)    Documentar su Compilador y lenguaje de programación para realizar las pruebas.

3)    Subir el código a Github, enviar el código fuente y el ejecutable del proyecto.


# Código para prueba
int main() {  
  int a = 0;  
  int i = 0.5; // debe dar error porque es entero  
  float p = 0.5;  
  int d = 0;  
  int d=0; //debe dar error porque ya fue declarada  
  
  for (a = 0; a < 3; a++) {  
    i++;  
    d = i;  
  }  
  d=0.5; // debe dar error porque es entera  
  
}  
