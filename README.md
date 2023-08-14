# Saludos en Go

Este paquete proporciona una forma simple de obtener saludos personalizados

## Instalacion
Ejecuta el siguiente comando para instalar el paquete:
````bash
go get -u github.com/asanchezg96/greetings
````

## Uso
Aqui tienes un ejemplo de como utilizar el paquete en tu codigo:
````go
import (
	"fmt"
	"github.com/alexroel/greetings"
)

func main() {
	messages, err := greetings.Hellos("Tony")

	if err != nil {
		fmt.Println("Ocurrio un error:", err)
	}
	fmt.Println(messages)
}

````
Este ejemplo importa el paquete github.com/alexroel/greetings y llama a la funcion Hello, con un saludo personalizado.
Si ocurre un error, se imprime un mensaje de error.