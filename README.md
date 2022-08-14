# Insertion-Sort

patika dev linkim: https://app.patika.dev/nasituygun

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```

[22,27,16,2,18,6] -> Input 


- [2,27,16,22,18,6] -> 1.Adim 
- [2,6,16,22,18,27] -> 2.Adim 
- [2,6,16,18,22,27] -> 3. Adim 
```


2.Big-O gösterimini yazınız.
```

- n*(n+1)/2 -> O(n^2)
```

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```

[2,6,16,18,22,27] -> sirali dizimiz
- 18 sayisi ortalarda oldugu icin average case kapsamina girer.
```



4.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```

 [7,3,5,8,2,9,4,15,6] -> input
- [2,3,5,8,7,9,4,15,6] -> 1.adim
- [2,3,4,8,7,9,5,15,6] -> 2.Adim
- [2,3,4,5,7,9,8,15,6] -> 3.Adim
- [2,3,4,5,6,9,8,15,7] -> 4.Adim
```

