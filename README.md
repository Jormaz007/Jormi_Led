	Jormi_Led.h		
	Librería de manejo de leds
	v0.3	20210129	Multitask	


	Jormi_Led(byte pin)
		Constructor, inicio con led apagado
	

	void enciende()
		Enciende el led (valor = HIGH)
	
	
	void apaga()
		Apaga el led (valor = LOW)
	

	byte conectado()
		Devuelve el numero de pin donde esta el led (objeto)
		return
			byte pin
	
	void parpadeo( unsigned long periodo )
		Parpadeo
		periodo = 0, el led deja de parpadear
		periodo != 0, periodo en milisegundos


	void update()
		Update del loop


	void informacion()
		Muestra en ventana de depuración (puerto serie) info de las variables
	
