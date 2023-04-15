# Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

    Average case: Aradığımız sayının ortada olması
    Worst case: Aradığımız sayının sonda olması
    Best case: Aradığımız sayının dizinin en başında olması.

.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# Cevaplar:

 1.Aadım : Dizideki en küçük sayı bulunur.Dizideki en küçük sayı 2'dir. Daha sonra dizinin ilk elemanı olan 22 ile yer değiştirir.

 2.Adım : Dizideki 2 sayısından sonraki en küçük sayı bulunur. En küçük sayı 6'dır. Daha sonra dizinin ikinci elemanı olan  27 ile yer değiştirir.

 3.Adım : Dizikdeki 6 sayısından sonraki en küçük sayı bulunur. En küçük sayı 16'dır. Dizinin üçüncü elemanı zaten 16 olduğu için herhangi bir yer değişikliği yapılmaz.

 4.Adım : Dizideki 16 sayısından sonraki en küçük sayı bulunur. En küçük sayı 18'dir. Dizinin dördüncü elemanı olan 22 ile yer değiştirilir.

 5.Adım : Dizideki 18 sayısından sonraki en küçük sayı bulunur. En küçük sayı 22'dir. Dizinin 5. ve 6. sayıları olması gereken sırada olduğu için değişiklik yapılmaz.

--------------------------------------------------------------------

 Insertion Sort'a göre sonuç : [2,6,16,18,22,27]

Big-O Gösterimi  : O(n^2)'dir. Çünkü her bir elemanın doğru konuma yerleştirilmesi için dizideki diğer tüm elemanlarla karşılaştırılması gerekmektedir.

Dizi sıralandıktan sonra 18 sayısı dizinin ortasında yer aldığı için Avarage Case kapsamına girer.

--------------------------------------------------------------------

 Selection Sort'a göre ilk 4 adım;

 1.Adım: Önce en küçük sayı olan 2 ile 7 er değiştirir. [2,3,5,8,7,9,4,15,6]

 2.Adım: Daha sonra 2'den sonraki en küçük sayı bulunur. 3 sayısının yerinde bir değişiklik 
olmaz. [2,3,5,8,7,9,4,15,6]

 3.Adım: Daha sonra 3'ten sonraki en küçük sayı bulunur. 4 sayısı ile 5 sayısı yer değiştirir. [2,3,4,8,7,9,5,15,6]

 4.Adım: Daha sonra 4'ten sonraki en küçük sayı bulunur. 5 ile 8 sayısı yer değiştirir.[2,3,4,5,7,9,8,15,6]

--------------------------------------------------------------------