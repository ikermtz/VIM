# VIM
Como moverte por el editor vim
		
vim  --> abre el editor vim
vim gato.txt  --> crea un archivo llamado gato.txt en el directorio actual


Comandos para salir de vim(Normal):
	:q  -->  salir/quit
	:wq  -->  write and quit/guardar y salir
	:x  -->  write and quit/guardar y salir
	:q!  -->  forzar salida/salir sin guardar
	

Movernos por vim(Normal):
	w  -->  comienzo siguiente palabra
	b  -->  comienzo palabra anterior
	e  -->  final de la palabra
	0  -->  comienzo de linea
	$  --> final de linea
	gg  -->  primera linea del fichero
	shift+g  -->  ultima linea del fichero
	4  -->  ir a la linea 4
	
	
Introducir ordenes(Linea de comando):
	q  -->  salir(y las variantes que tiene)
	%a/A/B/g  -->  buscar en el fichero para reemplazar A por B en todas las apariciones
	

Selecion de texto(Visual): //UNA VEZ SELECCIONADO EL TEXTO//
	d  -->  cortar/delete
	y  -->  copiar/yank
	p  -->  pegar/paste
	
	
Deshacer, rehacer y buscar(Normal):
	u  --> undo
	Ctrl+r  --> rehacer ultima accion
	/gato  -->  buscar gato en el fichero
		n  -->  siguiente ocurrencia
		N  -->  anterior ocurrencia
