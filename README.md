# Jorge Luis Piña Florencio akka 0s4k4

<h2 align="center">Sobre mi</h2>

```golang
package main
import (
	"fmt"
)
type Bio map[string]string
func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}
func GetBio() Bio {
	return Bio{
		"- 📖  Breve biografia:":              "Ingeniero en TI, tengo 24 años, fan del anime, manga, tecnologia, y videojuegos",
                "- ⚡  Skills :":                      "Programacion, Electronica, Redes, Soporte IT, Hacking",
		"- 🔭 Actualmente trabajo en":          "Programador web en copizza",
		"- 🌱 Actualmente estoy aprendiendo":   "Javascript a nivel fullstack, php con laravel y mongoDB)",
}
```

