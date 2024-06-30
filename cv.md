# Anastasia Alekbarova

## Contacts

**email**: <kriliai110@gmail.com>\
**phone**: +79777710490\
**Github**: [monochrime](https://github.com/monochrime "профиль на гитхабе") 

## Personal Info

I have been working with people, including children, for more than 8 years, and this taught me, first of all, soft skills.

Thanks to this, I learn quickly, I can work in a team, I interact well with people, and I also know how to take responsibility and manage them.

Back in university I was passionate about code, but I stepped away from it for a few years, and now I hope to do it again with the same passion as before.

## Education

- NUST MISiS
     - micro- and nanosystem technologies
     - certificate "quantum communication technologies"

## Skills

- HTML (basic)
- C# (basic)
- Python (basic)

## Code example
```C#
 class Program
    {
        delegate double fx(double i);
        //Объявление делегата
        static double f1(double x)
        {
            //Метод: f1
            return Math.Pow(Math.Tan(x),2) + (1 / Math.Pow(Math.Tan(x),2));
        }
        static double f2(double x)
        {
            //Метод 2
            return Math.Tan(x) - (1 / Math.Tan(x)) - 2 * x - Math.Tan(Math.PI / 6) + (1 / Math.Tan(Math.PI / 6)) + Math.PI / 3;
        }
        static double po(fx f, double a, double b)
        {
            return (f(b) - f(a));
        }
        static double sw(fx f, double a, double b, int n)
        {
            double c = 0, x = a, h = (b - a) / n;
            for (int i = 1; i < n; i++)
            {
                x += h; c += f(x);
            }
            return (2 * c + f(a) + f(b)) * h / 2;
        }
        static void Main()
        {
            double s1 = sw(f1, Math.PI/6, Math.PI/3, 50);
            Console.WriteLine("Интеграл равен {0:f4}", s1);
            double p1 = po(f2, Math.PI/6, Math.PI/3);
            Console.WriteLine("Проверка = {0:f4}", p1);
            Console.ReadKey();
        }
    }
```

## Languages 

* Russian - native
* English - Advanced
     * IELTS (2019): C1, 7.5

