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

_Que cosas necesitas para instalar el software y como instalarlas_

```
Da un ejemplo
```

### Recursos 📝

* [Introduction](https://github.com/desarollotiautocom/wifilead/wiki)
* [MaterialDashboard](https://github.com/desarollotiautocom/cumplimiento-riesgos/blob/master/MaterialDashboard.md)
* [Releases](https://github.com/desarollotiautocom/wifilead/wiki)
* [Examples](https://github.com/desarollotiautocom/wifilead/wiki)
* [Wiki](https://github.com/desarollotiautocom/wifilead/wiki)

### Instalación 🔧

_Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para tener un entorno de desarrollo ejecutandose_

_Dí cómo será ese paso_

```
Da un ejemplo
```

_Y repite_

```
hasta finalizar
```

_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_

## Convenciones de código ⏩

Una serie de ejemplos paso a paso que te dice lo que como estructurar el código para el desarrollo de tu aplicativo, API o interfaz

_Dí cómo será ese paso_

```
Da un ejemplo
```

## Ejecutando las pruebas ⚙️

_Explica como ejecutar las pruebas automatizadas para este sistema_

### Analice las pruebas end-to-end 🔩

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificación ⌨️

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

## Despliegue 📦

_Agrega notas adicionales sobre como hacer deploy_

## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/tu/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Fulanito Principal** - *Trabajo Inicial* - [fulanitoprincipal](https://github.com/tu)
* **Fulanito Detail** - *Documentación* - [fulanitodetail](#fulanito-de-tal)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
* etc.
