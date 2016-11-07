
# [La Tasa](https://latasa.mx/ "La Tasa")
![](https://lh3.googleusercontent.com/-a8Z2RgiAREs/WCDalztrM4I/AAAAAAAABDE/WgCh1Fqyp8Q1S1pch21ClJ-O1SsCqWITgCLcB/s0/logo.jpg "logo.jpg")

 [La Tasa](https://latasa.mx/ "La Tasa") es un modelo de préstamo entre particulares (peer to peer), el cual consiste en invertir en préstamos directamente a personas seleccionadas por [La Tasa](https://latasa.mx/ "La Tasa") por su buen perfil crediticio, evitando los altos costos de intermediación de los bancos y obteniendo las mejores tasas tanto para el inversionista como para quien solicita el crédito.

---
## Descripción del proyecto
Bajo el modelo de   [La Tasa](https://latasa.mx/ "La Tasa") contactamos a personas que buscan crédito (acreditados) con Inversionistas que buscan invertir. Gracias a nuestro análisis de riesgo y herramientas de diversificación, [La Tasa](https://latasa.mx/ "La Tasa") ofrece volatilidad baja; y debido a la eliminación de intermediarios con altos costos ofrecemos un rendimiento proyectado de hasta 15%.
>**Inversionistas**: son las personas físicas o morales que se registran en la Tasa con el objetivo de generar un rendimiento a través de los intereses generados de los créditos otorgados a través de [La Tasa](https://latasa.mx/ "La Tasa").

>**Acreditados**: son las personas físicas que solicitan un crédito en [La Tasa](https://latasa.mx/ "La Tasa").

---
## Inicio rápido

Instalar [Nodejs]( https://nodejs.org/en/ "Nodejs"):
```
sudo apt-get update  
sudo apt-get install nodejs
```

Instalar [Ruby on Rails](http://rubyonrails.org/ "Ruby on Rails"):
```
sudo apt-get install ruby-full
```

Descarga el repositorio:
```s
git clone git@bitbucket.org:resuelve/latasarails.git
```

Crear rama y cambiarse a ella:
```s
git checkout -b [development]
```

Descargar rama *development:*
```s
git pull origin development
```

Instalar npm:
```s
cd front
npm install
```

Instalar gemas del proyecto:
```s
bundle install
```


En **Windows**
> Agregar las siguientes *variables de entorno:*
>   
>  Nombre de la variable: **PATH** 
>  
>  Valor: **C:\RailsInstaller\Ruby2.2.0\bin**
>  
>  ---
>  
> Nombre de la variable: **SSL_CERT_FILE**
> 
> Valor: **C:\RailsInstaller\cacert.pem** (1)
>
> Si se encuentra el error "*Could not find a valid gem in any repository*" se debe ejecutar en consola:
> 
> `$ -gem sources --add http://rubygems.org/
`

Código para reemplazar archivos *Tasa/latasarails/front/node_modules/ng2-charts* por los archivos contenidos en *Tasa/latasarails/front/ng2-charts*.
###### (1) El archivo se localiza en el directorio *\LaTasa\latasarails del proyecto.*
Inicia npm
```s
cd front
npm start
```

Inicia el servidor de rails
```s
rails s
```

Accede al proyecto desde el servidor local
```s
http://localhost:3000
```
---

## Principales módulos
### Prestatario
Módulo dirigido a las personas que buscan obtener un préstamo, en el cual se tiene un cotizador de crédito  y los formularios necesarios para dar de alta al usuario en el sistema.
### Inversionista  
Éste módulo brinda información referente a las utilidades que podrán obtener las personas interesadas en invertir. En éste módulo se incluyen también los formularios necesarios para dar de alta a una persona como inversionista.

---
## Como contribuir al proyecto
* Descargar rama development  
`git pull origin development  
`  


* Crea una rama local   
`git branch -b [myBranchName]
`  
`git checkout [myBranchName]
`



* Integra development a tu rama local
`git merge development
`  


* Trabaja los cambios y guárdalos en el repositorio local  
`git add [myFile1]`  
`.`  
`.`  
`.`  
`git add [myFilen]`  
`git commit -m "commit message"` 



* Integra tus cambios a development  
`git checkout development
`  
`git merge myBranchName
`


* Guarda los cambios  
`git push -origin development
`  

---
## Equipo de desarrollo
Departamento de tecnologías de la información de [La Tasa](https://latasa.mx/ "La Tasa").

---
## Licencia
 [Licencia](https://opensource.org/licenses/MIT "Licencia") Ruby on Rails.
