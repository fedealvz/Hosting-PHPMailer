<h2>Introducci&oacute;n</h2>
<p>El siguiente documento explica c&oacute;mo enviar mails desde PHP en todas las plataformas (tanto Windows como Linux).</p>
<p>La conocida funci&oacute;n "mail()" de PHP por lo general se encuentra deshabilitada por cuestiones de seguridad: la peligrosidad de la misma radica en que con ella, se puede enviar correos de forma an&oacute;nima. Esto da a lugar el env&iacute;o de SPAM.</p>
<p>Si un sitio web es comprometido, lo primero que el perpetrador intentar&aacute; hacer es usar esta funci&oacute;n para enviar correo masivo. Esto bajar&aacute; la reputaci&oacute;n del servidor, pudiendo caer en listas negras y con la consecuente degradaci&oacute;n de la calidad del servicio (sus correos llegar&aacute;n como "correo no deseado" o rebotar&aacute;n con mensajes de bloqueo).</p>
<p>Esto aplica tanto para servicios compartidos como a dedicados.</p>
<h2>PHPMailer</h2>
<p>El m&eacute;todo preferido para el env&iacute;o de correos autenticados (con usuario y contrase&ntilde;a) sobre PHP es PHPMailer.</p>
<p>El c&oacute;digo fuente actualizado y ejemplo de implementaci&oacute;n puede ser encontrado en su sitio de Github:&nbsp;<a class="external-link" href="https://github.com/PHPMailer/PHPMailer" rel="nofollow">https://github.com/PHPMailer/PHPMailer</a></p>
<h3 id="EnviodemaildesdePHPconPHPMailer-Ejemplodeenv&iacute;odirecto">Uso</h3>
<ol>
<li>Clon&aacute; este repositorio en tu PC (usando Git o descargando como ZIP directo desde este link:&nbsp;<a href="https://github.com/PHPMailer/PHPMailer/archive/master.zip">https://github.com/PHPMailer/PHPMailer/archive/master.zip</a>)</li>
<li>
<p>Modific&aacute; o tom&aacute; de ejemplo el archivo "ejemplo.php" para implementarlo en tu aplicaci&oacute;n</p>
</li>
</ol>
