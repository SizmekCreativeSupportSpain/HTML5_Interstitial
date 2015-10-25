# <a href="https://platform.mediamind.com"><img src="http://www.sizmek.es/eb/users/javiegido_/__logos/HTML5.png" alt="Sizmek" width="26" height="36" /></a> Interstitial <a href="https://platform.mediamind.com"><img src="http://www.sizmek.es/eb/users/javiegido_/__logos/logo-dark.png" alt="Sizmek" width="57" height="15" /></a>

Plantilla genérica con todo lo necesario para crear formatos tipo interstitial utilizando workspaces de Sizmek.

## Descripción

La plantilla para montar un Interstitial permite, mediante media queries CSS, establecer los tamaños adecuados para landscape y portrait. Se puede utilizar la misma creatividad para dispositivos movil y tablets, simplemente modifica las media query de CSS para que tus elementos se ajusten al tamaño del dispositivo.

## Configuración 

Para cambiar la configuración del tamaño y las versiones para landscape y portrait debes editar el fichero de estilos, donde encontrarás este codigo:

```css

/*Portrait Styles*/
@media (orientation: portrait){
	#ad {
		width: 240px;
		height: 320px; 
	}
}

/*Landscape Styles*/
@media (orientation: landscape){
	#ad {
		width: 320px;
		height: 240px; 
	}
}

```

Una vez configurado esto ya tendrías todo listo para trabajar tu creatividad sobre la plantilla.

Cuando tengas terminada la creatividad, sube la pieza a la plataforma. En este caso, el formato que debes seleccionar en la plataforma es **HTML5 INTERSTITIAL** y la imagen de backup debe ser la que trae la plantilla( *backup.jpg* ). ¿No tienes claro cómo? Puedes seguir esta pequeña guia [Subir Creatividades Sizmek](http://sizmek.es/wiki/doku.php?id=subir_creatividades_html5).

Recuerda que si tienes cualquier duda puedes ponerte en contacto con el equipo de <a href="mailto:creativesupport-spain@sizmek.com">Soporte Creativo de Sizmek</a>

***