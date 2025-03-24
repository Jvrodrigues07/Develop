using System;

class Program
{
    static void Main()
    {
        // Solicita ao usuário que informe dois números
        Console.Write("Digite o primeiro número: ");
        double numero1 = Convert.ToDouble(Console.ReadLine());
        
        Console.Write("Digite o segundo número: ");
        double numero2 = Convert.ToDouble(Console.ReadLine());
        
        // Calcula a média aritmética
        double media = (numero1 + numero2) / 2;
        
        // Exibe o resultado
        Console.WriteLine($"A média aritmética é: {media}");
    }
}
