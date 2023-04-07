# Veri-Yapi-lari-ve-Algoritmalar

[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1-Average case: Aradığımız sayının ortada olması
2-Worst case: Aradığımız sayının sonda olması
3-Best case: Aradığımız sayının dizinin en başında olması.

En küçük eleman 2 olduğu için, 2 ve 22 yer değiştirir: [2, 27, 16, 22, 18, 6]
En küçük eleman 6 olduğu için, 6 ve 27 yer değiştirir: [2, 6, 16, 22, 18, 27]
En küçük eleman 16 olduğu için, 16 ve 22 yer değiştirir: [2, 6, 16, 22, 18, 27]
En küçük eleman 18 olduğu için, 18 ve 22 yer değiştirir: [2, 6, 16, 18, 22, 27]
Son olarak, en küçük eleman 27 olduğu için, hiçbir eleman yer değiştirmez.

Her bir elemanın yerini belirlemek için diğer tüm elemanlarla karşılaştırılması gerektiği için,
algoritmanın çalışma zamanı O(n^2) dir.

18 Average casedir.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1.[2,3,5,8,7,9,4,15,6]
2.[2,3,5,8,7,9,4,15,6]
3.[2,3,4,8,7,9,5,15,6]
4.[2,3,4,5,7,9,8,15,6]
