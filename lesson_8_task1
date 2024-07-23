//Первая

internal class Program
{
    private static void Main(string[] args)
    {
        int a = int.Parse(Console.ReadLine());
        int b = int.Parse(Console.ReadLine());

        if (a < 1)
            a = 1;
        if (b < a)
            return;
        Func(a, b);
    }

    public static void Func(int a, int b)
    {
        Console.Write(a);
        a++;
        if (a <= b)
            Func(a, b);
    }
}
