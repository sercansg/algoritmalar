# algoritmalar

 VeriYapilariveAlgoritmalar
   PROJE 1
A: Selection sort aşamaları: [22,27,16,2,18,6] -> Insertion Sort
1.[22, 27, 16, 2, 18, 6]
2.[16, 22, 27, 2, 18, 6]
3.[2, 16, 22, 27, 18, 6]
4.[2, 16, 18, 22, 27, 6]
5.[2, 6, 16, 18, 22, 27]

B: Big-O gösterimini yazınız.
n+(n-1)+(n-2)...(n-4)+1=[n.(n+1)]/2=(n^2+n)/2
o(n^2)
C: Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
Average Case
D: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1.[2,3,5,8,7,9,4,15,6]
2.[2,3,4,8,7,9,5,15,6]
3.[2,3,4,5,7,9,8,15,6]
4.[2,3,4,5,6,9,8,15,7]
PROJE 2
[16,21,11,8,12,22] -> Merge Sort
A) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. B) Big-O gösterimini yazınız.
A)

1.[16, 21, 11] ve [8, 12, 22]
2.[16, 21, 11] -> [16], [21, 11] -> [21], [11]
3.[8, 12, 22] -> [8], [12, 22] -> [12], [22]
4.[16] [11, 21] -> [11, 16, 21]
5.[8] [12, 22] -> [8, 12, 22]
6.[11, 16, 21] ve [8, 12, 22] -> [8, 11, 12, 16, 21, 22]
7.[8, 11, 12, 16, 21] - Sonuç
B)
2x=n
X=logn
Big-0= o (nlogn)
PROJE 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Root 7'dir.
5, soluna eklenir.
1, soluna eklenir.
8, sağına eklenir.
3, 5'in soluna eklenir.
6, 5'in sağına eklenir.
0, 1'in soluna eklenir.
9, 8'in sağına eklenir.
4, 3'ün sağına eklenir.
2, 1'in sağına eklenir.

  7
/   \
5       8
/ \       \
1   6     9
/ \    
0   3  
   /   \
    2   4
