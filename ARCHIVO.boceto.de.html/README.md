<!DOCTYPE html>
<html>
<head>
    <title>mi primera web</title>
    <style>
      table, tr, td {
      border: 1px solid black;
      }
    </style>
<head>
<body>
<table>
<tr>
   <th>producto</th>
   <th>precio</th>
</tr>
<tr>
   <td>pollo</td>
   <td>12$</td>
</tr>
<tr>
   <td>chancho</td>
   <td>15$</td>
</tr>
<tr>
   <td>cocodrilo</td>
   <td>356$</td>
</tr>
<tr>
   <td>carachama</td>
   <td>57$</td>
</tr>
<tr>
   <td>erizo de mar</td>
   <td>467$</td>
</tr>
<tr>
   <td>perro lagarto v:</td>
   <td>570$</td>
</tr>
<tr>
   <td>tiburón</td>
   <td>853$</td>
</tr>
<tr>
   <td>gargola</td>
   <td>1668$</td>
</tr>
<tr>
   <td>pegazo</td>
   <td>5788$</td>
</tr>
</table>
<br>
<table>
<tr>
   <th>producto</th>
   <th>precio</th>
</tr>
<tr>
   <td>pollo</td>
   <td>12$</td>
</tr>
<tr>
   <td>chancho</td>
   <td>15$</td>
</tr>
<tr>
   <td>cocodrilo</td>
   <td>356$</td>
</tr>
<tr>
   <td>carachama</td>
   <td>57$</td>
</tr>
</table>
<!--ul es lista no ordenada-->
  <ul>
    <li>elemento 1</li>
    <li>elemento 2</li>
    <li>elemento 3</li>
    <li>elemento 4</li>
    <li>elemento 5</li>
  </ul>
<!--ul es lista ordenada-->
  <ol>
    <li value="50">elemento 1</li>
    <li>elemento 2</li>
    <li>elemento 3</li>
    <li>elemento 4</li>
    <li>elemento 5</li>
    <li>
     <ol>
       <li>elemento 1</li>
       <li style="list-style-type: lower-alpha;">elemento 1</li>
       <li style="list-style-type: lower-greek;">elemento 1</li>
       <li style="list-style-type: lower-latin;">elemento 1</li>
       <li style="list-style-type: lower-roman;">elemento 1</li><br>
       <li style="list-style-type: lower-alpha;">elemento 1</li>
       <li style="list-style-type: lower-alpha;">elemento 1</li>       
       <li style="list-style-type: lower-alpha;">elemento 1</li>
       <li style="list-style-type: lower-alpha;">elemento 1</li>
       <li style="list-style-type: lower-alpha;">elemento 1</li>       
       <li style="list-style-type: lower-alpha;">elemento 1</li>
       <li style="list-style-type: lower-alpha;">elemento 1</li>
       <li style="list-style-type: lower-alpha;">elemento 1</li>
       <li style="list-style-type: lower-alpha;">elemento 1</li>
       <li style="list-style-type: lower-alpha;">elemento 1</li>
       <li style="list-style-type: lower-alpha;">elemento 1</li>
     </ol>
    </li>
  </ol>
    <form action="/formulario.php" method="POST">
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