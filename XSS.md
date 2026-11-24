# Cross-Site Scripting

Es un problema de seguridad web que permite a los cibercriminales ejecutar scripts maliciosos en sitios web legítimos o confiables, normalmente ocurren por resultados de fallas comunes dentro de una aplicacion web y permiten que el actor malicioso pueda tomar la identidad del usuario, llevar a cabo cualquier accion que el usuario pueda realizar y acceder a todos sus datos

Como se utiliza un script en una pagina confiable el usuario no puede identificar que proviene realmente de una fuente no confiable, ocurre normalmente con javascript ya que es el lenguaje de programacion mas comun para los navegadores

Generalmente estan compuestos de dos etapas, el primero es un metodo que utilizan para inyectar codigo malicioso, conocido como carga, en la pagina web que visita la victima. Esto solo es posible si el sitio web objetivo permite directamente la entrada del usuario en sus paginas, entonces al inyectar este codigo malicioso se trata como codigo fuente cuando el usuario visita el sitio del cliente

La segunda etapa es que la victima visite el sitio web al que se le inyecto la carga util, utilizando normalmente estrategias de ingenieria social o con un ataque de suplantacion de identidad para que las victimas accedan al sitio web malicioso

## Tipos de ataques XSS

- **Xss reflejado:** es una solicitud enviada al servidor web que luego se incluye en la respuesta HTTP
- **XSS almacenado:** inyecta la carga util en la aplicacion objetivo y si no se tiene validacion de entrada la aplicacion almacenara o persistira permanentemente el codigo malicioso por ejemplo en la base de datos
- **XSS Basado en DOM:** Una forma mas avanzada de ataque XSS que solo es posible si la app web escribe los datos que el usuario proporciona al DOM y luego se leen y se los envia al navegador del usuario, si no se manejan correctamente los datos la carga util se almacena desde el DOM