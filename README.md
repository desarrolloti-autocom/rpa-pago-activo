# Pago Activo

El Bot “AUT.001” se encarga de leer y extraer datos de un archivo en Excel de Google Drive, ingresa a Quiter con 
el usuario y contraseña almacenados en el archivo la hoja “Settings“ del archivo config, una vez obtenidos los 
datos de Drive ingresa a “Contabilidad>Gestión de caja”, posteriormente toma el dato del número de cajero y 
número de caja a la que se va a ingresar , el Bot verifica si la caja está abierta o cerrada, si está abierta continua 
con el proceso, de lo contrario envía un correo notificando que la caja está cerrada. 
Una vez que el Bot identifico que la caja está abierta, selecciona “Crear nuevo apunte de caja” , ingresa el “Tipo y 
número de cuenta”, elige las referencias que se van a procesar y valida que los montos obtenidos de drive 
coincidan con los que tiene Quiter, si no coinciden, los guarda en el reporte de pagos y pasa a la siguiente 
transacción, caso contrario ingresa el método de pago y accede a datos adicionales, coloca el método de pago y 
graba la información, después , guarda los datos para imprimir el recibo de pago, extrae del recibo el nuevo 
número de referencia que se asoció al pago y lo guarda en el reporte de pagos. 

## Comenzando 🚀


Mira **Deployment** para conocer como desplegar el proyecto.


### Pre-requisitos 📋

Los pre-requisitos son los siguientes:
Conexión a internet
Credenciales y Conexión a VPN 
Credenciales a sistema Quiter Web
Tener acceso a G-suite de google para acceder al insumo sheet con las referencias de pago
Equipo con windows 10
Contar con licencia comunity edition de Automation Anywhere
Tener privilegios de Bot creator
Instalar Bot Agente en el equipo cliente

```
Para instalar el bot Agente solo se necesita tener pribilegios de administrador para ligar el despositivo con el runner y control room.
```

### Recursos 📝

* [Link de desarrollo Automation anywhere](https://community2.cloud-2.automationanywhere.digital/#/login?)

### Instalación 🔧
Al ingresar al link de https://community2.cloud-2.automationanywhere.digital/#/login?
El sistema pide descargar el bot agente, se descarga en automático

Una vez descargado se da clic en el .exe y se da next hasta finalizar (Ejecutar como administrador)


## Convenciones de código ⏩

Al ser una robotización no existen convenciones de código si no instrucciones dentro de cada componente

```
Por ejemplo una bifurcación o IF se maneja a nivel componente no a nivel código usando ragg & drop
```

## Ejecutando las pruebas ⚙️

https://autocom.atlassian.net/wiki/spaces/AYF/pages/78905345/C+mo+ejecutar+la+tarea+programada+de+Automation+Anywhere+con+UIPATH+desde+linea+de+comandos.


### Analice las pruebas end-to-end 🔩

Las pruebas end-to-end fueron realizadas junto con el usuario y el equipo de QA para su validación, así como el seguimiento y feedback del dueño del proceso.

se adjunta la liga
https://docs.google.com/spreadsheets/d/1rEdNDkMeJdm84XabAObeush0LAREHXIv/edit#gid=1128209445


### Y las pruebas de estilo de codificación ⌨️

En la RPA no existen pruebas de codificación si no de buenas prácticas.

```
Un ejemplo es el evitar el manejo de delays en procesos de cambios de pantallas usando bucles y bifurcaciones
```

## Despliegue 📦

Cómo tal el despliegue se realiza como el siguiente ejemplo

https://autocom.atlassian.net/wiki/spaces/AYF/pages/78905345/C+mo+ejecutar+la+tarea+programada+de+Automation+Anywhere+con+UIPATH+desde+linea+de+comandos.

## Construido con Automation Anywhere🛠️

Los bots de automatización robótica de procesos tienen el mismo conjunto de habilidades que las personas… y algunas más. Piense en los bots de RPA como una fuerza de trabajo digital que puede interactuar con cualquier sistema o aplicación. Por ejemplo, los bots pueden copiar y pegar, extraer datos web, hacer cálculos, abrir y mover archivos, analizar correos electrónicos, iniciar sesión en programas, conectarse a API y extraer datos no estructurados. Y dado que los bots se pueden adaptar a cualquier interfaz o flujo de trabajo, no es necesario cambiar los sistemas, aplicaciones o procesos empresariales existentes a fin de realizar la automatización.

* [Automation anywhere](https://www.automationanywhere.com/) - El framework web usado


## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/tu/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores ✒️

Bryan Gracia, Octavio Flores, Adrían Rojas.


## Licencia 📄

Este proyecto está bajo la Licencia (Comunity) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

