# GRASP - General responsibility assignment software patterns (or principles)

Es un conjunto de los "Nueve fundamentos principales en el diseño orientado a objetos y asignacion de responsabilidades", todos estos patrones son soluciones comunes en muchos proyectos de desarrollos de software.

- Information expert: Es un principio utilizado para determinar a donde delegar responsabilidades como metodos, campos etc, utilizando el principio de information expert una aproximacion general para asignar responsabilidades es mirar una responsabilidad especifica, mirar la informacion que se necesita para completarla y de ahi determinar donde se guardara
- Creator: Cual clase es responsable de crear objetos es una propiedad fundamental para la relacion entre objetos de clases particulares 
- Controller: Asigna la responsabilidad de tratar con los eventos del sistema a una clase sin UI que representa todo el sistema o un caso de uso. Entonces un objeto controlador es un objeto sin interfaz responsable de recibir o manejar un evento del sistema
- Indirection: Soporta bajo acoplamiento y reuso potencial entre dos elementos asignando responsabilidades de mediacion entre ellos por un objeto intermediario, entonces este intermediario crea una "Indireccion" entre los otros componentes
- Low coupling: Es una medida para conocer que tan fuertemente conectado esta un elemento con otro, ya sea porque sabe de su existencia o depende de este
- High Cohesion: Es un patron de evaluacion que procura mantener los objetos con su enfoque apropiado, manejable y entendible, lo que busca es que sus responsabilidades esten fuertemente relacionadas con un tema o con lo que buscan solucionar
- Polymorphism: Permite variaciones de comportamiento basada en el tipo en el cual esta variacion puede ocurrir, lo ideal es definir funcionalidades por medio de polimorfismo en vez de la implementacion especifica
- Protected variations: Es un patron que protege elementos de variaciones de otro elementos envolviendo el enfoque de inestabilidad con una interfaz y permitiendo varias implementaciones de esta interfaz
- Pure fabrication: Es una clase que no representa el concept en el problema de dominio, especialmente para lograr bajo acoplamiento y alta cohesion, se llama un "servicio" en el domain driven design