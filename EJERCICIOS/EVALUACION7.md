# 7. PROGRAMACIÓN ORIENTADA A OBJETOS (POO)
Objetivo: Verificar el dominio teórico y técnico del paradigma programación orientada a
objetos, mediante ejercicios para desarrollar su código y preguntas de respuesta
múltiple.

Indicaciones: Pedir responder cada una de las preguntas de manera acertada, breve y
clara, según sea el caso.

1. La Programación Orientada a Objetos es: (Valor 1 punto)
.
        c. Un paradigma que se basa en el uso de objetos.
      
2. Se refieren a características principalmente físicas y de estado de un objeto: (Valor 1 punto)

        b. Atributos
       

3. Sirve para derivar de una clase ya existente a otra clase: (Valor 1 punto)

      
        b. Polimorfismo
       
        
4. De las siguientes opciones, selecciona las ventajas de la Programación Orientada a Objetos: (Valor 1 punto)

        b. Simplicidad
        d. Reutilización de código
        
5. Las clases normalmente cuentan con: (Valor 1 punto)

        c. Nombre de clase, atributos y métodos.
        
6. En programación, se utiliza para modelar un conjunto de objetos: (Valor 1 punto)

       
        b. Clase
       
        
7. ¿Qué son los métodos?

        
        b. Las operaciones realizables de un objeto.
        
        
8. Identifica las partes de una clase:

![image](https://user-images.githubusercontent.com/105729934/180623408-15d25576-125c-47ea-a4ee-a0f63301b64.png)

9. Deberás crear un programa que forme parte de un módulo para el sistema de una
estética de perros. El programa deberá de contener lo siguiente: (Valor 2 puntos)

a. Una clase RecibeMascota.

b. Los atributos: nombre de perro, edad, raza, tamaño y nombre de dueño.

c. Crear el método main en donde contendrá el código para realizar el
siguiente procedimiento:

  i. Crear un arreglo dinámico de tipo de la clase.
  
  ii. Hacer una instancia para crear un objeto de tipo de la clase.
  
  iii. Asignar valores a los atributos de la clase con datos que tú prefieras.
  
  iv. Agregar el objeto creado al arreglo.
  
  v. Imprimir la cantidad de perros que se encuentran en la estética con el
  siguiente mensaje: Perros actuales en la estética: “Número de
  perros”.

            TU CODIGO AQUI
                import java.util.ArrayList;
                public class RecibeMascota {
                        String nombre;
                        int edad;
                        String raza;
                        String dueno;
                        public static void main(String args[]) {
                                ArrayList<RecibeMascota> perrosActuales=newArrayList();

                                RecibeMascota miGrupo=new RecibeMascota();
                                miGrupo.nombre="pluto";
                                miGrupo.edad=8;
                                miGrupo.raza="pitbull";
                                miGrupo.dueno="monserrat lopez";
                                perrosActuales.add(miGrupo);
                                System.out.pintln("Perros actuales en la estetica: "+ perrosActuales.size());
                        }
                }        
