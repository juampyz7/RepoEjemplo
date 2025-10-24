# RepoEjemplo
# Aprendiendo Markdown

Mis primeros pasos en **Markdown** que es un formato de marcado de ***archivos de texto***

A continuacion una ___lista___

* item 1
* item 2
    * item 2.1
    * item 2.2
* item 3

A continuacion una ___tabla___

| Codigo | Nombre | Precio |
| :-: | :-: | :-: |
| 1 | TV | 553.99 |
| 2 | Computador | 1687.23 |
| 3 | Celular | 791.51 |

A continuacion un _enlace_ o "Link":

[Diario El Comercio de Ecuador](https://www.elcomercio.com/actualidad/politica/investigan-intento-de-envenenamiento-presidente-daniel-noboa-babahoyo/)

A continuacion una ___Imagen___

![Cristiano Ronaldo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQns-JHntvTpHKdCkOgcL7vviPQ5lnQNZiTvA&s)

# Titulo nivel 1
## Titulo nivel 2
### Titulo nivel 3

A continuacion el **codigo de un programa**:
```
import java.util.Scanner;
public class Saludo2 {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		String nombre;
		System.out.print("Dime tu nombre: ");
		nombre = sc.nextLine();
		System.out.print("Hola " + nombre);
		System.out.println(", encantado de conocerte!");
	}
}