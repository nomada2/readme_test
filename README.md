
# [La Tasa](https://latasa.mx/ "La Tasa")
[![N|Solid](https://latasa.mx/images/logo.svg)](https://latasa.mx/images/logo.svg)

 [La Tasa](https://latasa.mx/ "La Tasa") es un modelo de préstamo entre particulares (peer to peer), el cual consiste en invertir en préstamos directamente a personas seleccionadas por la Tasa por su buen perfil crediticio, evitando los altos costos de intermediación de los bancos y obteniendo las mejores tasas tanto para el inversionista como para quien solicita el crédito.

---
## Descripción del proyecto
Bajo el modelo de   [La Tasa](https://latasa.mx/ "La Tasa") contactamos a personas que buscan crédito (prestatarios) con Inversionistas que buscan invertir. Gracias a nuestro análisis de riesgo y herramientas de diversificación, La Tasa ofrece volatilidad baja; y debido a la eliminación de intermediarios con altos costos ofrecemos un rendimiento proyectado de hasta 15%.
>**Inversionistas**: Son aquellas personas físicas o morales que colocan o aportan recursos financieros en otra empresa para tener acceso sobre su información contable, percepción de intereses y distribución de utilidades o el control de esta.

>**Prestatarios**: Personas (físicas o morales) que reciben una cantidad de dinero, con la obligación de devolverlo junto con los intereses y en un determinado tiempo.

---
## Inicio rápido
```s
npm install
```
Instalar
[Nodejs]( https://nodejs.org/en/ "Nodejs")

Instalar
[Ruby on Rails](http://rubyonrails.org/ "Ruby on Rails")

Descarga el repositorio
```s
git@bitbucket.org:resuelve/latasarails.git
```
En **Windows**
> Se deben agregar las siguientes *variables de entorno:*
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
> Se debe reemplazar el contenido del directorio *Tasa/latasarails/front/node_modules/ng2-charts* (2)
>
> Si se encuentra el error "*Could not find a valid gem in any repository*" se debe ejecutar en consola:
> 
> `$ -gem sources --add http://rubygems.org/
`

Inicia npm
```s
$ cd LaTasa\latasarails\front\
$ npm start
```

Inicia el servidor de rails
```s
$ cd LaTasa\latasarails
$ rails s
```

Accede al proyecto desde el servidor local
```s
http://localhost/3000
```
---

## Principales módulos
### Login
Módulo del sitio que permite autentificarse proporcionando su nombre de usuario o email y contraseña.
![enter image description here](https://lh3.googleusercontent.com/-evyoh_NEmrg/WBu5ZugZqTI/AAAAAAAABAk/UtCTOu_KyBsS-LUk7q287dKyFGM4MbGyACLcB/s0/latasa_login.jpg "La Tasa | Login")
### Prestatario
Módulo dirigido a las personas que buscan obtener un préstamo, en el cual se tiene un cotizador de crédito  y los formularios necesarios para dar de alta al usuario en el sistema.
![enter image description here](https://lh3.googleusercontent.com/-Ed_MaG4uu14/WBu5eoLc3dI/AAAAAAAABAs/lZeVfzof5tkCiVI7eghms0UEh-d_J6KtQCLcB/s0/latasa_prestatario.jpg "La Tasa | Prestatario")
### Inversionista  
Éste módulo brinda información referente a las utilidades que podrán obtener las personas interesadas en invertir. En éste módulo se incluyen también los formularios necesarios para dar de alta a una persona como inversionista.
![enter image description here](https://lh3.googleusercontent.com/-wi9E0lvlSlk/WBu52g54IWI/AAAAAAAABA0/U2xsi98_3OwoPM2BwnIUw76oRQzii2xOgCLcB/s0/latasa_inversionista.png "La Tasa | Inversionista")

---
## Como contribuir al proyecto
* Descarga el repositorio  
`git@bitbucket.org:resuelve/latasarails.git
`


* Crea una rama local y trabaja los cambios en ella  
`$ git branch -b [myBranch_name]
`  
`$ git checkout [myBranch_name]
`


* Guarda tus cambios en el repositorio  
`$ git add [myFile1]`  
`.`  
`.`  
`.`  
`$ git add [myFilen]`  
`$ git commit -m "commit message"`  
`$ git push -u origin [myBranch_name]`


* *Pull request* desde la cuenta de github del proyecto

---
## Equipo de desarrollo
Departamento de tecnologías de la información de [La Tasa](https://latasa.mx/ "La Tasa")

---
## Licencia
 [Licencia](https://opensource.org/licenses/MIT "Licencia") Ruby on Rails

---
##### (1) El archivo se localiza en el directorio *\LaTasa\latasarails* del proyecto.
##### (2) Los archivos para reemplazar se encuentran en *Tasa/latasarails/front/node_modules/ng2-charts-for-windows*.
