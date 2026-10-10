**El entendimiento de la actividad propuesto por el instructor se encuenta en la ruta ./docs/README.md**

Todo debe ser construido a base de arquitectura hexagonal, la que esta planteada en los spec iniciales, se debe seguir la regla del desarrollo hexagonal.

Construir el aplicativo: El aplicativo debe ser desarrollado usando react + laravel (php), siguiendo como referencia los 2 spec iniciales en la carpeta ./docs.

Regla estricta de Commits (Docs primero): Esta es vital. Cada vez que hagan un commit de estructura o código, siempre debe ir primero la documentación (docs) y después el resto del proyecto.

Modelo de documentacion: La base para el desarrollo de la actividad es que se debe seguir la regla del SDD, que es documentar antes de empezar con el codigo.

Ejecucion: La unica manera de ejecutar el proyecto debe ser mediante docker, se deben usar contenedores, docker ya se encuentra descargado en este equipo

--------------------------------------------------------------

2. Que nos dicen los spec que se deba tener en cuenta:

api-contract.md: Este nos dice que el contrato HTTP es independiente del lenguaje a usar. por lo que se debe respetar lo que hay esta planteado. Lo que hace cada operacion esta indicado en ./spec.md

architecture.md / arquitectura-panoramica.md: Nos indica como esta planteada la arquitectura hexagonal del proyecto, dejando explicitamente cuales son los puertos/adaptadore, nos indica el flujo para registrar un prestamo. Ademas se debe tener en cuenta la arquitectura panoramcia ya que en esta nos indica que debe ir en cada carpeta.

constitution.md: Principios innegociables del proyecto. No son estilo ni preferencia: cada artículo trae cómo se verifica, porque un principio que nadie puede comprobar es una intención. Un cambio que viole un artículo se rechaza sin discutir el resto. Nos indica los principios de su arquitectura y valores innegociables para realizar el desarrollo en react + laravel, independientemente de que sea otro lenguaje.

data-model.md: Nos indica el modelo de datos (almacenamiento)

plan.md: Como se construye lo que vive en spec.md. Esqueleto y salud → migración inicial con semilla → dominio → casos de uso con fakes → adaptadores → API → pruebas de contrato y concurrencia.

spec.md: En spec nos indica que es lo que se construye, porque se esta construyendo y toda las reglas de negocio del aplicativo, el core del negocio (aplicativo)

task.md: Esta definida la lista de tareas para desarrollar el aplicativo, seguido de su dependencia y por ultimo su evidencia.

