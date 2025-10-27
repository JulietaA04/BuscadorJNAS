# BuscadorJNAS
Buscador
Es simple, no se me da bien esto y no tengo para saber si está bien o no, lo que más se usa son los if, ya que son algo medio básico y se me dan mejor el recordarlos y ponerlos a uso que otros comandos.
Tuve que buscar la mayoría de los comandos y de cómo usarlos, y los que no encontraba se los tuve que pedir a ChatGPT.
Como ya dije, es bastante básico y simple, se le dan al usuario las opciones de lo que quiera hacer, y el usuario presiona los números indicados en el menú para avanzar.

Diagramas:

Cuando el usuario presiona el número 1, se le muestra qué páginas ya han sido ingresadas. Si no hay ninguna página ingresada ya, se le muestra un mensaje diciendo que no hay nada.


Cuando el usuario presiona el número 2, se le deja buscar una palabra en específico y se le dice cuántas veces se encuentra esa palabra en el archivo que haya elegido. Si el usuario no ingresa alguna palabra(no se encuentra algo escrito) se le muestra un mensaje diciéndole que no ha puesto algo.

Cuando el usuario ingresa el número 3, se le pregunta qué palabra quiere ver en los resultados, si una palabra fue ingresada se le muestra el resultado de la búsqueda, si el usuario no ingresa una palabra se le muestra un mensaje diciéndole que no ha escrito una palabra.


Si el usuario elige el número 4, se copian los archivos, se limpian y se muestra un mensaje diciendo que se ha limpiado dicho archivo y te dice en qué fecha fue limpiado.



Si el usuario elige el número 5, se le da la opción de ingresar una página.


Si el usuario elige el número 6, se sale del programa.


 

Comandos usados:

echo: Imprime el texto escrito. 
echo “Hola Mundo”
cat: Te permite crear archivos y mirar lo que contiene, tambièn permite combinar pero de eso no estoy segura.
cat “$CASAS” 
touch: Te permite crear un archivo, le pones el nombre de dicho archivo que quieras crear.
touch “$CASAS”
if: Se utiliza para indicar que si algo pasa, entonces se tiene que hacer lo siguiente después del then. Si no pasa eso, se pone un else y otra condición.
if [ “$CASAS” -it 1 ]; then
echo “No hay casas alrededor”
else 
echo “Se pueden ver casas alrededor”
>> : Se pone para que pueda guardar algo en otro archivo aparte, fuera del que estamos usando. Luego de pone el nombre del archivo al que quieras guardar algo
echo “*lo que sea que quieras guardar*” >> *nombre del archivo al que quieras guardar lo deseado.
while: Se utiliza para indicar que mientras algo esté pasando, se hará cierta cosa, pero si algo diferente pasa el while se detiene.
while [ “$CASAS” -ge 1 ]
do
echo “Puedes explorar las casas”
else 
echo “No hay casas para explorar”
cp: Se usa para copiar archivos”
cp “$*nombre del archivo* “$*nombre del archivo”
grep: Se usa para poder buscar lo que uno quiera, ya sea en un programa o en una pagina.
grep “*la palabra a buscar*” “*en donde la quieres buscar*”
curl: Se usa para cambiar datos de un servidor al otro.
curl [opción] [URL].


Bibliografía:

60 essential Linux commands
Common Terminal Commands
while Command in Linux with Example - GeeksforGeeks
wc command in Linux with examples - GeeksforGeeks
curl Command in Linux with Examples - GeeksforGeeks


Reflecciòn:
Siento que esto fue algo necesario para poder aprender, ya que el programar no es algo que se me de bien. Me hizo buscar comandos que no sabía hacer bien.

