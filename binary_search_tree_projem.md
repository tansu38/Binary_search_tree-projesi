[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Serach-Tree aşamalrının yazımı:
- Önce diziyi sıralı bir şekilde yazarız:
[0,1,2,3,4,5,6,7,8,9]
- Root'u belirlemek için dizinin en ortadaki değerini buluruz.
n(ort) = n(toplam)/n = 45/10 = 4.5 --> Root 4 ya da 5 alınabilir.
Root= 5
- Sağ ve sol tarafları oluştururken her zaman en ortadaki sayıyı almaya çalışırsak sonuca en kısa sürede ulaşırız.Yani şöyle:

---
           5  
         /   \   
        3     7  
       / \   /  \
      1   4 6    8 
     / \          \
    0   2          9
---