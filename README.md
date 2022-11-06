# Patika.Dev_Proje1
VeriYapilariVeAlgoritmalarProje1

https://app.patika.dev/dadasoglu

**[22,27,16,2,18,6] -> Insertion Sort**

**1-) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.**

*cevap 1* 

1.aşama <- [22|27,16,2,18,6]

2.aşama <- [22,27|16,2,18,6]

3.aşama <- [16,22,27|2,18,6]

4.aşama <- [2,16,22,27|18,6]

5.aşama <- [2,16,18,22,27|6]

6.aşama <- [2,6,16,18,22,27|]

**2-) Big-O gösterimini yazınız.**

*cevap 2*

Worst Case   <- O(n^2)

Average Case <- O(n^2)

Best Case    <- O(n)

**3-)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.**

*cevap 3*

Average case <- [6,16,22,2,18,27]

Worst case <- [27,22,18,16,6,2]

Best case <-[2,6,16,18,22,27]

**4-)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**

*cevap 4*

[2,6,16,18,22,27] şeklinde sıraladığımız zaman 18 sayısı ortada  olduğu için **Average case** kapsamına girer.

**5-) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

*cevap 5*

1.adım <-[7|3,5,8,2,9,4,15,6]

2.adım <-[3,7|5,8,2,9,4,15,6]

3.adım <-[3,5,7|8,2,9,4,15,6]

4.adım <-[3,5,7,8|2,9,4,15,6]







