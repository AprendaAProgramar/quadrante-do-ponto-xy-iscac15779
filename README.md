# Atividade1
Quadrante do Ponto XY

Verifique em que quadrante do referencial cartesiano se encontra um ponto com as corrdenas (x,y) introduzidas pelo utilizador.

    class Program
    {
        static void Main(string[] args)
        {
            int coordenadax,coordenaday;
            Console.WriteLine("Insira a coordenada x:");
            coordenadax = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Insira a coordenada y:");
            coordenaday = Convert.ToInt32(Console.ReadLine());
            if (coordenadax > 0 && coordenaday > 0)
            {
                Console.WriteLine("As coordenadas ({0},{1}) pertencem ao 1º quadrante", coordenadax, coordenaday);
            }    
            if(coordenadax < 0 && coordenaday > 0)
            {
                Console.WriteLine("As coordenadas ({0},{1}) pertencem ao 2º quadrante", coordenadax, coordenaday); 
            }
            if (coordenadax < 0 && coordenaday < 0)
            {
                Console.WriteLine("As coordenadas ({0},{1}) pertencem ao 3º quadrante", coordenadax, coordenaday);
            }
            if (coordenadax > 0 && coordenaday < 0)
            {
                Console.WriteLine("As coordenadas ({0},{1}) pertencem ao 4º quadrante", coordenadax, coordenaday);
            }
                
        }
    }
