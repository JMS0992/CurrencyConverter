Conversor de Monedas
Este es un proyecto simple de conversor de monedas desarrollado en Java. Utiliza la API de ExchangeRate para obtener tasas de conversión en tiempo real entre diferentes monedas.

Descripción
El conversor permite convertir entre las siguientes monedas:

Dólares estadounidenses (USD) a Euros (EUR)
Euros (EUR) a Dólares estadounidenses (USD)
Dólares estadounidenses (USD) a Pesos Mexicanos (MXN)
El programa ofrece un menú interactivo para que el usuario seleccione el tipo de conversión y continúe realizando operaciones hasta que decida salir.

Requisitos
Antes de ejecutar el proyecto, asegúrate de tener lo siguiente:

Java 8 o superior.
Una clave de API válida de ExchangeRate-API.
Conexión a Internet para acceder a la API y obtener las tasas de conversión.
Instalación y Ejecución
Clona el repositorio en tu máquina local:

git clone https://github.com/tu-usuario/conversor-monedas.git
Abre el proyecto en tu entorno de desarrollo preferido (por ejemplo, IntelliJ IDEA).

Agrega tu clave de API en el archivo fuente. Busca la línea que contiene private static final String API_KEY = "TU_CLAVE_DE_API" y reemplázala con tu clave obtenida de ExchangeRate-API.

Ejecuta el programa en tu entorno de desarrollo o compílalo desde la terminal:

bash
Copiar código
javac CurrencyConverter.java
java CurrencyConverter
El programa te pedirá que ingreses una cantidad y seleccionará el tipo de conversión.

Ejemplo de Uso
Seleccione la opción de conversión:
1. Convertir de dólares (USD) a euros (EUR)
2. Convertir de euros (EUR) a dólares (USD)
3. Convertir de dólares (USD) a pesos mexicanos (MXN)
4. Salir

Ingrese la opción: 1
Ingrese la cantidad en USD que desea convertir a EUR: 100
Resultado: 100.00 USD equivalen a 91.43 EUR
Estructura del Proyecto
CurrencyConverter.java: Archivo principal que contiene la lógica para obtener las tasas de conversión y manejar el menú interactivo.
README.md: Archivo que describe el proyecto, cómo configurarlo y cómo utilizarlo.
API Utilizada
Este proyecto utiliza la ExchangeRate-API para obtener tasas de cambio en tiempo real. Asegúrate de registrarte y obtener tu propia clave API.

Contribuciones
Las contribuciones son bienvenidas. Si tienes sugerencias o mejoras, siéntete libre de abrir un pull request o crear un issue.

Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

