#Front End











# OJO ESTO ES CSS PARA EL FORMULARIO
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

# Esto es Html de prueba
    <b>Negrita</b>
    <br /><br />
    <strong>Negrita</strong>
    <hr>
    
    <!--Dentro del div pongo la clase titulo-->
    <div class="titulo">
        <a href="http://https://github.com/Valentina-Assef/myportfolio-FrontEnd.git" target="_blank">Esto es un enlace. CLICK</a>
        <br/><br/>
        <img src="https://images.pexels.com/photos/13265635/pexels-photo-13265635.jpeg?auto=compress&cs=tinysrgb&w=400&lazy=load"
        <br/><br/>
        <h3>Lo que sigue es un audio</h3>
      <!-- Fijarse que esta mal del audio-->
        <audio controls>
            <source src="D:\Programacion\#YoPogramo\PORTFOLIO\Multimedia" type="audio/mpeg">
        </audio>
        <br/><br/>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d13087.055476520032!2d-57.927651749999995!3d-34.91237485!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x95a2e5e32b344bbb%3A0x650b1322c5b780d1!2sEl%20Rinconcito%20Chalaco%20cevicher%C3%ADa!5e0!3m2!1ses-419!2sar!4v1662080342747!5m2!1ses-419!2sar" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
