### **Java**

```Java
import java.util.Scanner;

class Ejercicio1{
	public static void main(String[] args){
		Scanner sc = new Scanner(System.in);
		int nPizzas = sc.nextInt();
		while(nPizzas != 0){
			int nPersonas = sc.nextInt();
			int division = nPersonas/nPizzas;
			if((nPersonas%nPizzas) == 0){
				System.out.println(division);
			}else{
				System.out.println("PELEA");
			}
			division=0;
			nPizzas = sc.nextInt();
		}

	}
}
```
### **HTML**
```HTML

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Password imput</title>
    <link rel="shortcut icon" href="./img/favicon.ico" type="image/x-icon">
    <img src="./img/burger-svgrepo-com.svg" alt="burger"height="70" width="70">

</head>
<body>
    <hr>
    <h1>Login to start creating a burger</h1>
    <form action="order.html" method="post">
        <label for="username">Username</label>
        <input type="text" name="username" id="username">
        <br>
        <label for="pwd">Password</label>
        <input type="password" name="pwd" id="pwd">
        <input type="submit" value="Submit">
    </form>

</body>
</html>
```
### **C**
```C
#include <stdio.h>
int main() {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   return 0;
}
```

### **Python**

```Python
print('Hello, world!')
```