//Третья

internal class Program
{
    private static void Main(string[] args)
    {
        Console.WriteLine("Введите массив через пробел: ");

        string[] arr = Console.ReadLine().Split(" ");

        Func(arr, arr.Length - 1);
    }

    public static void Func(string[] arr, int length)
    {
        Console.Write(arr[length] + " ");
        length--;
        if (length >=  0)
            Func(arr, length);
    }
}
