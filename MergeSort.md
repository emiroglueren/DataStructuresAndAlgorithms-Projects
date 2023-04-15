# Proje 2

[16,21,11,8,12,22] -> Merge Sort

    Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    Big-O gösterimini yazınız.

# Cevaplar: 

Merge Sort bir sıralama algoritmasıdır. Verilen diziyi öncelikle yarıya böler ve bu yarıdaki elemanları sıralanana kadar tekrar tekrar yarıya bölmeye devam eder. Bölme işlemi sonlandıktan sonra, alt dizideki elemanlar karşılaştırılarak birleştirilir ve sıralanır. Bu birleştirme işlemi, elemanların birbirleriyle karşılaştırılarak sıralandığı Merge işlemi ile gerçekleşir.

1.Aşama: Dizi ortadan ikiye bölündü -> [16,21,11] ve [8,12,22]

2.Aşama: Alt diziler tekrar ikiye bölündü -> [16] - [21,11] - [8] - [12,22]

3.Aşama: Alt diziler tekrar ikiye bölündü ve böylece dizi elemanları tek olana kadar bölünmğş oldu. -> [16] - [21] - [11] - [8] - [12] - [22]

4.Aşama: Sıralamaya başlandı. -> [16] - [11,21] - [8] - [12,22]

5.Aşama: Alt diziler kendi aralarında sıralandı. -> [11,16,21] - [8,12,22]

6.Aşama: Alt diziler kendi aralarında tekrar sıralandı. Ve birleştirildi. 
-> [8,11,12,16,21,22]

Big-O gösterimi : O(nlogn)
