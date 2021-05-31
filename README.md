# Informe de laboratorio N°1 - Herramienta Github

**Integrantes:**

Christian Bonifaz, Mateo Calderon, Ariel Guano, Erick Mera, Mario Rosas

**Grupo N°:** 4

**NRC:** 3725

**Docente:** Ing. Cesar Osorio

**Tema:** Control de Versiones

#### OBJETIVOS
1.	Adquirir conocimientos dentro del campo de la programación colectiva para realizar un proyecto grupal mediante repositorios virtuales como github.

2.	Poner en práctica el conocimiento adquirido sobre la aplicación git y github para poder crear nuestros repositorios y posteriormente crear un repositorio virtual para realizar nuestro proyecto.
3.	Aprovechar las funciones que nos brinda las aplicaciones git y github aplicando nuestro conocimiento en programación en lenguaje c/c++ para la creación de un código y que este sea subido a un repositorio virtual en github.

#### MARCO TEÓRICO

**GIT**

Git es una herramienta que realiza una función del control de versiones de código de forma distribuida es el sistema de control de versiones moderno más utilizado del mundo, con un mantenimiento activo que desarrolló originalmente Linus Torvalds, el famoso creador del kernel del sistema operativo Linux, en 2005, Con ella podemos mantener un historial completo de versiones y podemos movernos, como si tuviéramos un puntero en el tiempo, por todas las revisiones de código y desplazarnos una manera muy ágil, Además tiene un sistema de trabajo con ramas que lo hace especialmente potente. En cuanto a la funcionalidad de las ramas, las mismas están destinadas a provocar proyectos divergentes de un proyecto principal, para hacer experimentos o para probar nuevas funcionalidades. Con esto nos damos cuenta que Git es una herramienta muy útil e indispensable en la programación y es importante saber utilizarla de manera correcta para poder ser un buen programador.

**GITHUB**

Github es un portal creado para alojar el código de las aplicaciones de cualquier desarrollador, y que fue comprada por Microsoft en junio del 2018. La plataforma está creada para que los desarrolladores suban el código de sus aplicaciones y herramientas, y que como usuario no sólo puedas descargarte la aplicación, sino también entrar a su perfil para leer sobre ella o colaborar con su desarrollo. Esto se debe a que GitHub es una plataforma de gestión y organización de proyectos basada en la nube que incorpora las funciones de control de versiones de Git. 

Además, la interfaz de usuario de GitHub es más fácil de usar que la de Git, lo que la hace accesible para personas con pocos o ningún conocimiento técnico. Esto significa que se puede incluir a más miembros del equipo en el progreso y la gestión de un proyecto, haciendo que el proceso de desarrollo sea más fluido.
Aunque GitHub es conocido principalmente dentro de la comunidad de ingenieros de software, puede ser utilizado en una variedad de industrias diferentes. Cualquier equipo o empresa que trabaje en diferentes proyectos que requieran desarrollo en forma de archivos puede utilizar este servicio.
Por ejemplo, los equipos de contenido y marketing pueden utilizar GitHub para organizar sus proyectos. Los creativos freelance pueden utilizarlo para gestionar su trabajo cuando trabajan con otras personas.

#### CÓDIGO DESARROLLADO
void abundantes(int n, int cont=1, int div=1, int numIni=2, int suma=0)

{

printf("~~ lista de numeros abundantes ~~\n");

printf("\nLos numeros abundantes son: ");
 
 do{
 
 do {
 
 if (numIni%div==0){
 
 suma=div+suma;
 
 }
 
 div=div+1;

} while(div<numIni);

if (suma>numIni){

printf("%i   ",numIni);

cont=cont+1;

}

div=1;

suma=0;

numIni=numIni+1;

}while(cont<=n);

return;

}

#### CONCLUSIONES

1. Git y GitHub son herramientas fundamentales para el proceso de desarrollo de tu proyecto de programación. Como hemos visto estas herramientas nos permite sincronizar y tener una línea definida para desarrollar nuestro proyecto.  

2. Otras de las conclusiones que llegamos después de usar esta herramienta es que en el caso de que queramos establecer un sistema de control de versiones para otras fases del proyecto como el diseño, tenemos estas herramientas a nuestra disposición sin ninguna complicación y de fácil uso  y acceso.

3. Y como conclusión final Git y GitHub hace que el trabajo en equipo más ágil y sencillo, ayuda a la detección de fallos, a disminuir errores humanos, al seguimiento por etapas del proyecto, al mantenimiento de diferentes entornos, etc. Como conclusión podemos decir que alojar proyectos como repositorios en GitHub, es una decisión profesional inteligente, en caso de los repositorios públicos, porque te beneficiarás de los conocimientos de otros programadores, y en el caso de los privados, dispondrás de un robusto sistema de gestión de proyectos que hará que el trabajo en equipo sea mucho más rápido.  

#### BIBLIOGRAFIA

GitHub: ¿Qué Es GitHub Y Cómo Utilizarlo?. (2021). Recuperado 31 May 2021, de https://www.hostinger.es/tutoriales/que-es-github

Fernández, Y. (2021). Qué es Github y qué es lo que le ofrece a los desarrolladores. Recuperado 31 May 2021, de https://www.xataka.com/basics/que-github-que-que-le-ofrece-a-desarrolladores
