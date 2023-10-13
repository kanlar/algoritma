# algoritma
Proje Dosyalarım
- **Proje 1**
   
    
    **[22,27,16,2,18,6]** -> Insertion Sort
    
    - Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
        
        **Cevap** : 

        **[2,27,16,22,18,6]**
        
        **[2,6,16,22,18,27]**
        
        **[2,6,16,22,18,27]**
        
        **[2,6,16,18,22,27]**
        
    - Big-O gösterimini yazınız.
    
        **Cevap** : 
      o(n)

    - Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
        
        **Cevap** : Average case
        
    - **[7,3,5,8,2,9,4,15,6**] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
        
        **Cevap** : 

    
        **[2,3,5,8,7,9,4,15,6**] 
        
        **[2,3,4,8,7,9,5,15,6**] 
        
        **[2,3,4,5,7,9,8,15,6**]

        **[2,3,4,5,6,9,8,15,7**]

  ---
     **Proje 2 **
     - **[16,21,11,8,12,22**] -> Merge Sort
     - Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
       **Cevap** : 
 ```
Answer a: 

Step 1:               [16,21,11]                             [8,12,22]
                    /           \                         /           \
Step 2:          [16,21]    -    [11]                  [8,12]    -    [22]
                /        \             \               /      \            \
Step 3:      [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
                \       /              /             \         /            /
Step 4:          [16,21]    -    [11]                  [8,12]    -    [22]
                     \            /                        \           /
Step 5:                [11,16,21]                            [8,12,22]
                                  
Step 6:                               [8,11,12,16,21,22]
```
 - Big-O gösterimini yazınız.

   **Cevap** :
       log(nlogn)

---
**Proje 3**
   - **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2**] dizisinin Binary-Search-Tree aşamalarını yazınız.

   - Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
     **Cevap** :
     ```
       
      Root x = 6
                                   6
                                 /   \ 
                                5     7
                              /         \
                             1           8
                           /   \           \
                          0     3           9
                              /   \      
                             2     4    
                                      
      Step 1:     7 > 6 için root'un sağında 7 bulunur.
      Step 2:     5 < 6 için root'un solunda 5 bulunur.
      Step 3:     1 < 6 için 1 root'un soluna eklenir.
      Step 4:     8 > 6 için 8 root'un sağına eklenir.
      Step 5:     3 < 6 için 3 root'un soluna eklenir.
      Step 6:     0 < 6 için 0 root'un soluna eklenir.
      Step 7:     9 > 6 için 9 root'un sağına eklenir.
      Step 8:     4 < 6 için 4 root'un soluna eklenir.                        
      Step 9:     2 < 6 için 2 root'un soluna eklenir.                         
      ```


      

  
