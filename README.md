# jquery-validation-venezuela
Plugins basado en jQuery Validation Plugin v1.14.0
se agrega la opcion para validar documentos de identidad usando el formato
V|E|P|G|J + - + 8 a 10 digitos

e.g V-12345678 - para venezolano
e.g E-1234567890 - para extranjero
e.g G-123456789 - para RIF

la forma de usarlo es muy simple

$("#idform").validate({
	rules: {
	    id_input: {
	      documentacion: true
	    }
  }

});
