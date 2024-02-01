<!DOCTYPE html>
<html>
<head>
    <title>mi primera web</title>
<head>
<body>
    <form action="/formulario" method="GET">
    <label for="Nombre">Nombre</label>
    <input value="luana" type="text" id="Nombre" name="nombre" placeholder="Nombre"/>
      <br>
    <label for="Apellido">Apellido</label>
    <input value="torres" type="text" id="apellido" name="apellido" placeholder="Apellido"/>
    <br>
    <label for="comentario">COMENTARIO</label><br>
    <textarea cols="50" rows="10" id="comentario" placeholder="comentario" name="comentario">este es un valor por defecto</textarea>
    <br>
    <button type="button">tipo botón</button>
    <button type="reset">tipo reset</button>
    <button type="submit">tipo submit</button>
    </form>
    <hr>
    <h1>Primer encabezado o titulo</h1>
    <h2>Segundo encabezado o subtitulo</h2>
    <h3>Tercer encabezado</h3>
    <h4>Cuarto encabezado</h4>
    <h5>Quinto encabezado</h5>
    <h6>Sexto encabezado</h6>
    <p>EL MOMENTO ES AHORA (párrafo)</p>
    <p>EL MOMENTO ES AHORA(párrafo)</p>
    <hr>
    <h1>Alien A</h1>
    <hr>
    <p>
    Este texto es<span style="color: red"> mucho mas largo</span> y es para la<br><br> etiqueta de span!
    </p>
    <!--Este texto es un COMENTARIO y nova aparecer en el explorador-->
    <hr>
     <h4>
    <a href="https://www.google.com.pe">Ir a Google</a>
    <br>
    <hr>
    <br>
    <a target="_blank" href="https://www.facebook.com">Ir a Facebook</a>
     </h4>
    <hr>
    <img src="img/zoro.jpg" alt="zoro roronoa" height="1300">
    <br>
    <br>
   <h3> Extensiones de (input; type) para formularios; (form; action= y method=) obligatorio que vaya con form; acciones de type (text, submit, radio, checkbox, email, password, file) </h3>
    <form>
    <label for="radio">Aceptar</label>
    <input type="radio"/>
      <br>
    <label for="checkbox">Verdadero<label/>
    <input type="checkbox"/><br>
    <label for="checkbox">Falso<label/>
    <input type="checkbox">
   <br>
    <label for="Email">Correo</label>
    <input type="email" id="email" name="Email" placeholder="Email"/>
      <br>
    <label for="Password">Contraseña</label>
    <input type="password" id="password" name="password" placeholder="Password"/>
      <br>
    <label for="file">Archivo</label>
    <input type="file">
    <input type="submit"/> 
    <br>
    </form>
</body>
</html