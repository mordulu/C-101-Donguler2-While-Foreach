[Patika.dev](https://github.com/mordulu)


Dosyalarımın içinde yer alan program.cs'ye girilme zahmeti olmaması adına aşağıya çalışmamı önizleme olarak ekliyorum(süslü parantezler önizlemede hata verdiğinden konumlandırmalarına dikkat etmeyiniz)

# C-101 Donguler-2-While-Foreach

// See https://aka.ms/new-console-template for more information

//While 

//1 den başlayarak console dan girilen sayıya kadar (sayı dahil) ortalama hesaplayıp console a yazdıran program.

//Console.Write("Lütfen bir sayi giriniz: ");

//int sayi = int.Parse (Console.ReadLine());

//int sayac = 1;

//int toplam = 0;

//while (sayac<= sayi)

//{

//    toplam+= sayac;

//    sayac ++;

//}

//

//System.Console.WriteLine(toplam/sayi);

// 'a' dan 'z' ye kadar harfleri console a yazdır.

//char character = 'a';

//while (character < 'z')

//{

//    Console.Write(character);

//    character ++;

//

//}

System.Console.WriteLine("***** Foreach *****");

string[] arabalar = {"BMW","Ford","Toyota","Nissan"};

foreach (var araba in arabalar)

{

System.Console.WriteLine(araba);

}
