Esta aplicación tiene diferentes funcionalidades, algunas de las cuales se basan en el acceso a GPT a través de su API. 

CONFIGURACIÓN.
Al abrir la app nos pide que seleccionemos un sector y una región. Al hacerlo, realiza una petición a un motor de búsqueda de Chrome. 
El retorno de esta búsqueda se envía a GPT para que genere un contexto que pueda aprovechar posteriormente GPT en la realización de los escenarios. 
En caso contrario GPT dará respuestas genéricas y no actualizadas. 

CARGA DE HISTÓRICOS.
Hay cuatro modelos distintos de carga de datos:
- Generación datos demo.
  El objetivo de este método es generar una muestra suficientemente grande que nos ayude a la demostración.
- Carga fichero PDF.
  La carga de este fichero envía los datos de texto a GPT para que haga una interpretación de los campos necesarios. Se desplegará un formulario
  con la interpretación para gestionar posibles errores en dicha interpretación por parte de GPT.
- Carga de fichero CSV.
  Carga a través de un 'drag and drop' de un fichero csv.
- Carga manual.
  Se despliega un formulario para añadir manualmente los campos.

GENERACIÓN DE ESCENARIOS.
Se generan tres escenarios (base, optimista y pesimista) en función de la interpretación del contexto generado en la parametrización.

CLUSTERINGS.
Se realiza un análisis de los datos históricos cargados dividiéndolos en tres clusters y dando una interpretación financiera, basada en el análisis por
parte de GPT de dichos datos.

HISTÓRICO.
Es una herramienta para la gestión de la base de datos. Se puede filtrar en los históricos de cobros y pagos, generar nuevos registros en el histórico y exportar en csv.


