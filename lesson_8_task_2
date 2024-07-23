//Вторая

internal class Program
{
    private static void Main(string[] args)
    {

        int a = int.Parse(Console.ReadLine());
        int b = int.Parse(Console.ReadLine());

        if (a < 0 || b < 0)
            return;

        Console.WriteLine(Func(a, b));
    }

    public static Int64 Func(Int64 a, Int64 b)
    {
        if (a == 0)
            return b + 1;

        if (a > 0 && b == 0)
            return Func(a - 1, 1);

        return Func(a - 1, Func(a, b - 1));
    }
}
