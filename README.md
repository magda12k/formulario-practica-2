<html>
    <head>       
        
        <title>practica2 - Formularios</title>
    </head>
<body>
           <h1>Formulario de inscripcion</h1>
<p>
<label for="nombre">Nombre: </label>
<br/> <input type="text" name="nombre" id="nombre">
<br/> <br/>
<label for="apellido">Apellido paterno: </label>
<br/> <input type="text" name="apellido" id="apellido">
<br/> <br/>
<br/> <label for="apellido materno">Apellido materno: </label>
<br/> <input type="text" name="apellido materno" id="apellido materno">
<br/>
                  <ul>Edad</ul>         <select name="edad">
<option value="1">20</option>
<option value="2">21</option>
<option value="3">22</option>
<option value="4">23</option>
<option value="5">24</option>
<option value="6">25</option>
<option value="7">26</option>
<option value="8">27</option>
<option value="9">28</option>
<option value="10">29</option>
<option value="11">30</option></select>
<br/> 

                              <ul>Sexo</ul>  
 <input type="radio" name="sexo" id="Hombre" value="Hombre">
<label for="Hombre">Hombre: </label>

<br/> <input type="radio" name="sexo" id="mujer" value="Mujer">
 <label for="mujer">Mujer: </label>
 
 <ul>Nacionalidad</ul>         <select name="Nacionalidad">
<option value="1">austriaco</option>
<option value="2">británico</option>
<option value="3">búlgaro</option>
<option value="4">holandés</option>
<option value="5">francés</option>
<option value="6">alemán</option>
<option value="7">griego</option>
<option value="8">suizo</option>
<option value="9">mexicano</option>
<option value="10">italiano</option>
<option value="11">irlandés</option></select>
<br/>  
<label for="telefono">Telefono: </label>
 <br/> <input type="text" name="tel" id="tel">
  <br/> <label for="domicilio">Domicilio: </label>
 <br/> <input type="text" name="dom" id="dom">
 <br/>  <label for="email">Email: </label>
 <br/> <input type="text" name="email" id="email">
<br/> <br/>


<ul>INTERESES</ul>
<input type="checkbox" name="interes" value="1">Musica
<br>
<input type="checkbox" name="interes" value="2" >Tv
<br>
<input type="checkbox" name="interes" value="3">Libros
<br>
<input type="checkbox" name="interes" value="4">Deportes
<br>
<input type="checkbox" name="interes" value="5" >Tegnologia
<br>
<ul>ULTIMO GRADO DE ESTUDIOS</ul>
<input name="GRADO" type="radio" value="1" />Ninguno
<br />
<input name="GRADO" type="radio" value="2" />Primaria
<br />
<input name="GRADO" type="radio" value="3" />Secundaria
<br />
<input name="GRADO" type="radio" value="4" />Bachillerato
<br />
<input name="GRADO" type="radio" value="5" />Licenciatura
<br />
<input name="GRADO" type="radio" value="6" />Maestria
<br />
<input name="GRADO" type="radio" value="7" checked="checked" />Doctorado

<ul>OBSERVACIONES PERSONALES</ul>
<textarea name="comentarios" rows="10" cols="40">Escribe aquí tus comentarios</textarea>

<ul>DUDAS</ul>
<textarea name="comentarios" rows="10" cols="40">Escribe aquí tus comentarios</textarea>
<br/> <br/>

<input type="reset" value="Cancelar">
<input type="submit" value="Enviar">

</p>
</form>
</body>
</html>
