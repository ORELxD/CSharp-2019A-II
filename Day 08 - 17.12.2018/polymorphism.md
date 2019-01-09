

# polymorphism
```csharp
namespace _05_ovveride
{

    class A
    {

    }


    class B:A
    {

    }
    class Program
    {
        static void Main(string[] args)
        {
            A myA1 = new A();


            // a base can point to a sub instance
            A myA2 = new B();

            // a sub can not point to a base instance
            // B myB1 = new A();  //--> COMPILATION ERROR
            B myB2 = new B();
           
        }
    }
}

```
