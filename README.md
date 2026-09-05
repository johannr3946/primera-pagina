# primera-pagina

<section id="verificacion">

  <h3>Caso A - Imagen</h3>
  <img href="multimedia/imagen 1.png" alt="Fotografia del estudiante - Caso A con error">
  <p>Tuve problemas porque use el atributo href en vez de src La etiqueta img siempre necesita src para poder cargar la imagen href no aplica aqui por eso no se ve nada</p>

  <h3>Caso B - Enlace</h3>
  <a src="https://developer.mozilla.org/">Consultar MDN - Caso B con error</a>
  <p>El link estaba bien escrito pero use el atributo src en vez de href La etiqueta a necesita href para saber a donde debe llevar el enlace</p>

  <h3>Caso D - Formulario</h3>
  <form>
    <label for="correo-prueba">Correo (Caso D con error):</label>
    <input type="correo" id="correo-prueba" name="correo-prueba">
  </form>
  <p>No era un error de ortografia de las etiquetas, sino que correo no es un valor valido para el atributo type Al no reconocer correo el navegador lo trata como texto normal, sin la validacion especial de correo electronico</p>

</section>