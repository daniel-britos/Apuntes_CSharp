<img src="/img/bucles.jpg">
```
        static void Main(string[] args)
        {
            Console.WriteLine("¿Quieres entrar al bucle?");

            string respuesta = Console.ReadLine();

            while (respuesta != "no")
            {
                Console.WriteLine("Estas dentro del bucle, deseas seguir dentro?");
                respuesta = Console.ReadLine();
            }
            Console.WriteLine("Adios!");
        }

```

```
