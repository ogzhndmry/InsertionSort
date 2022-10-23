# InsertionSort

**[22,27,16,2,18,6] -> Insertion Sort** 

**1-)** ***Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.***

- En küçük sayı 2 olduğu için *2*  ile *22*  yer değiştirdi.
[2,27,16,22,18,6]
- 2 den sonra en küçük sayı *6* olduğu için *6* ile *27* yer değiştirdi.
[2,6,16,22,18,27]
- 6 dan sonra en küçük sayı *16* olduğu yerde sabit.
[2,6,16,22,18,27]
- 16 dan sonra en küçük sayı *18* ile *22* yer değiştirdi 
[2,6,16,18,22,27]
- Sıralanmış bir dizi elde ettik.

**2-)** ***Big-O gösterimini yazınız.***

- BigO(n²)

**3-)** Time Complexity: 
- Average case: Aradığımız sayının ortada olması
- Worst case: Aradığımız sayının sonda olması
- Best case: Aradığımız sayının dizinin en başında olması.

**4-)** ***Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.***

[2,6,16,18,22,27] *18* sayısı ne en sonda ne de en başta olmadığı için *Average Case* kapsamına girer.

**5-)** ***[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.***

1. [7,3,5,8,2,9,4,15,6] *2* ile *7* ile yer değiştirdi.
2. [2,3,5,8,7,9,4,15,6] *3* sabit
3. [2,3,5,8,7,9,4,15,6] *4* ile *5* yer değiştirdi.
4. [2,3,4,8,7,9,5,15,6] *5* ile *8* yer değiştirdi.