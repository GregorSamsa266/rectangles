# rectangles
namespace rectangles.project
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int a, b, area, perimeter;
            a = 5;
            b = 7;
            area = a * b;
            perimeter = a + b;

            Console.WriteLine("çevre:" + " " + perimeter);
            Console.WriteLine("alan:" + " " + area);

            Console.Read();
        }
    }
}
