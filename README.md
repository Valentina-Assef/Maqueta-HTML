#Front End

Dia 1: 
Navbar de Bootstrap
Al ponerle class navbar, pude ponerle, en la hoja css, un background color.
Dentro de esta nav, Bootstrap pone un link con una imagen. En esta imagen coloque el logo de Argentina Programa.
A continuacion se abre una lista desordenda
con items de los logos de la redes sociales. 
Al agregarle a la lista list-group-horizontal lo iconos se ordenan de manera horizontal.
A cada item se le agrego la clase list-group-item por lo que en la hoja css se edito el color de fondo, el borde y el hover de cada logo.
Se le agrego un boton de login con una ventana modal

Dia 2:
Cambio de color del la navbar.
Eleccion imagen banner
Titulo centrado en el banner con formato extraido de Google font.

Dia 3:
Creación seccion Acerca de mi con columnas de Bootstrap.
Creacion archivo de dashboard









# Esto es Css para el formulario
body{
  height: 100%; 
  font-family: 'Noto Sans', sans-serif;
  background-color: #ab4493; 
}


.contact_form{  
  width: 460px; 
  height: auto;
  margin: 80px auto;
  border-radius: 10px;  
  padding-top: 30px;
  padding-bottom: 20px;  
  background-color: #fbfbfb; 
  padding-left: 30px; 
}


input{
  background-color: #fbfbfb; 
  width: 408px; 
  height: 40px; 
  border-radius: 5px;  
  border-style: solid; 
  border-width: 1px; 
  border-color: #ab4493; 
  margin-top: 10px;  
  padding-left: 10px;
  margin-bottom: 20px; 
}


textarea{
  background-color: #fbfbfb; 
  width: 405px; 
  height: 150px; 
  border-radius: 5px;  
  border-style: solid; 
  border-width: 1px; 
  border-color: #ab4493; 
  margin-top: 10px;  
  padding-left: 10px;
  margin-bottom: 20px; 
  padding-top: 15px; 
}


label{
  display: block; 
  float: center;  
}


button{
  height: 45px; 
  padding-left: 5px;
  padding-right: 5px;   
  margin-bottom: 20px; 
  margin-top: 10px;   
  text-transform: uppercase;
  background-color: #ab4493; 
  border-color: #ab4493; 
  border-style: solid; 
  border-radius: 10px;  
  width: 420px;   
  cursor: pointer;
}


button p{
  color: #fff; 
}


span{
  color: #ab4493; 
}


.aviso{
  font-size: 13px;  
  color: #0e0e0e;  
}


h1{
  font-size: 39px;  
  text-align: letf; 
  padding-bottom: 20px; 
  color: #ab4493;
}


h3{
  font-size: 16px; 
  padding-bottom: 30px;
  color: #0e0e0e;   
}


p{
  font-size: 14px; 
  color: #0e0e0e; 
}


::-webkit-input-placeholder {
 color: #a8a8a8;
}


::-webkit-textarea-placeholder {
 color: #a8a8a8;
}


.formulario input:focus{
  outline:0;
  border: 1px solid #97d848;
}


.formulario textarea:focus{
  outline:0;
  border: 1px solid #97d848;
}