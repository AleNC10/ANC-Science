## Bienvenido a ANC-Science 

En este espacio podrás interactuar con herramientras de programación basadas en python que tienen aplicaiones académicas como por ejemplo: calcular el volumen
de un comprimido biconvexo usando solamente tres parámetros.

También podrás visualizar todo el  código y marco de ejecución en [google colaboratory](https://colab.research.google.com/) en caso de que conozcas más sobre programación.

A continuación podrás conocer los conceptos de las herramientas que usamos para hacer del aprendizaje una experiencia amena...

Recuerda "LA CIENCIA ES DE QUIEN LA TRABAJA" A. Einstein

¡A DIVERTIRNOS!

### Lenguaje de programación
Todo lo que es digital o "por computadora" funciona mediante uno o más códigos de instrucciones llamado lenguaje de programación. Estos códigos le dicen a una computadora o a un dispositivo (hardware) lo que debe hacer. "seguramente te estás imaginando un robot" y efectivamente, si nos vamos a niveles más elevados de tecnología, las naves espaciales, los robots, los satélites, etc., funcionan gracias a los lenguajes de programación.
Existen alrededor de 700 diferentes lenguajes de programación pero los más importantes solamente son tres: Java, C++ y Python. "Posiblemente hayas escuchado nombrar alguno de ellos"
En el siguiente recuadro te mostraré un ejmeplo de código que realiza la misma tarea pero en los tres lenguajes de programación más importantes que se mencionó en el párrafo anterior.


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Supongamos que queremos obtener el promedio de calificaciones de un alumno:

Java

ArrayList Notes = new ArrayList();
 Notes.add(7);
 Notes.add(9);
 Notes.add(8);
 Notes.add(10);
 Notes.add(8);
double n = 0;
 for (int i = 0; i < Notes.size(); i++) {
 n += Double.parseDouble(Notes.get(i).toString());
 }
 System.out.println("El promedio de los valores del ArrayList es: "+n/Notes.size());

C++
double promedioDeArreglo(int arreglo[], int cantidadDeElementos){
    double suma = 0;
    for (int x = 0; x < cantidadDeElementos; x++){
        suma = suma + arreglo[x];
    }
    return suma / cantidadDeElementos;
}


Python

Name = Jake
Notes = (7, 9, 8, 10, 8)
Promedio = (sum(Notes))/(float(len(Notes)))
print("La calificación promedio de %s es: %f" %(Name,promedio))

```

Para más detalles visite los cursos gratuitos de [omegaUp](https://omegaup.com/).

### Volumen de un comprimido biconvexo
La morfología peculiar de las formas farmacéuticas sólidas biconvexas conlleva un reto importante en el cálculo manual de su volumen ya que la parte media del comprimido es cilíndrica y los bordes superior e inferior son convexos. Ante ese desafío nos dimos a la tarea de desarrollar una ecuación matemática basada en el teorema de “volumen de un sólido de revolución usando discos” para obtener la expresión global que permita llegar al resultado deseado con elevada precisión y usando solamente tres parámetros (díametro, altura total y altura de la corona convexa).

 [repository settings](https://github.com/AleNC10/Volumen-comprimido/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Contáctanos

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
