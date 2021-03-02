	Jormi_Led.h		Librería de manejo de leds
		v0.3	20210129	Multitask	


	Constructor, inicio con led apagado
	Jormi_Led(byte pin);


	Enciende - Enciende el led (valor = HIGH)
	void enciende();


	Apaga - Apaga el led (valor = LOW)
	void apaga();


	Conectado - Devuelve el numero de pin donde esta el led (objeto)
	return
		byte pin
	byte conectado();


	Parpadeo
		_parpadeo = 0, el led deja de parpadear
		_parpadeo != 0, periodo en milisegundos
	void parpadeo( unsigned long periodo );


	Update
	void update();


	Información - Muestra en ventana de depuración info de las variables
	void informacion();
