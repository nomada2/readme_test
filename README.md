
# [La Tasa](https://latasa.mx/ "La Tasa")
[![N|Solid](https://latasa.mx/images/logo.svg)](https://latasa.mx/images/logo.svg)

 [La Tasa](https://latasa.mx/ "La Tasa") es un modelo de préstamo entre particulares (peer to peer), el cual consiste en invertir en préstamos directamente a personas seleccionadas por la Tasa por su buen perfil crediticio, evitando los altos costos de intermediación de los bancos y obteniendo las mejores tasas tanto para el inversionista como para quien solicita el crédito.

---
## Descripción del proyecto
Bajo el modelo de   [La Tasa](https://latasa.mx/ "La Tasa") contactamos a personas que buscan crédito (acreditados) con Inversionistas que buscan invertir. Gracias a nuestro análisis de riesgo y herramientas de diversificación, La Tasa ofrece volatilidad baja; y debido a la eliminación de intermediarios con altos costos ofrecemos un rendimiento proyectado de hasta 15%.
>**Inversionistas**: son las personas físicas o morales que se registran en la Tasa con el objetivo de generar un rendimiento a través de los intereses generados de los créditos otorgados a través de la Tasa.

>**Acreditados**: son las personas físicas que solicitan un crédito en la Tasa.

---
## Inicio rápido

Instalar
[Nodejs]( https://nodejs.org/en/ "Nodejs")

Instalar
[Ruby on Rails](http://rubyonrails.org/ "Ruby on Rails")

Descarga el repositorio:
```s
git@bitbucket.org:resuelve/latasarails.git
```

Crear rama y cambiarse a ella:
```s
$ git checkout -b [development]
```

Descargar rama *development:*
```s
$ git pull origin development
```

Instalar npm:
```s
LaTasa\latasarails\front
$ npm install
```

Instalar gemas del proyecto:
```s
LaTasa\latasarails
$ bundle install
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


Reemplazar el contenido del directorio *Tasa/latasarails/front/node_modules/ng2-charts* por los archivos contenidos en *Tasa/latasarails/front/ng2-charts*.

![enter image description here](https://lh3.googleusercontent.com/-7vi5-oqAj-4/WBz8OdJC9-I/AAAAAAAABBw/PGxvqojEcFA1-SGbu4Pxn15kTvAIN89IgCLcB/s0/replace_files2.png "replace_files2.png")

###### (1) El archivo se localiza en el directorio *\LaTasa\latasarails del proyecto.*



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
* Descargar rama development  
`$ git pull origin development  
`  


* Crea una rama local   
`$ git branch -b [myBranchName]
`  
`$ git checkout [myBranchName]
`



* Integra development a tu rama local
`$ git merge development
`  


* Trabaja los cambios y guárdalos en el repositorio local  
`$ git add [myFile1]`  
`.`  
`.`  
`.`  
`$ git add [myFilen]`  
`$ git commit -m "commit message"` 



* Integra tus cambios a development  
`$ git checkout development
`  
`$ git merge myBranchName
`


* Guarda los cambios  
`$ git push -origin development
`  

---
## Equipo de desarrollo
Departamento de tecnologías de la información de [La Tasa](https://latasa.mx/ "La Tasa").

---
## Licencia
 [Licencia](https://opensource.org/licenses/MIT "Licencia") Ruby on Rails.
