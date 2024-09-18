# Binary-Search-Tree-

ilk olarak
Root: 7
BST oluşturulmaya 7 ile başlanır ve 7 kök düğüm olur.

    7
Eleman 5:

5, 7'den küçüktür, bu yüzden 5, 7'nin soluna eklenir.

    7
   /
  5
Eleman 1:

1, 7'den ve 5'ten küçüktür, bu yüzden 1, 5'in soluna eklenir.

    7
   /
  5
 /
1
Eleman 8:

8, 7'den büyüktür, bu yüzden 8, 7'nin sağına eklenir.

    7
   / \
  5   8
 /
1
Eleman 3:

3, 7'den ve 5'ten küçüktür ama 1'den büyüktür, bu yüzden 3, 1'in sağına eklenir.

    7
   / \
  5   8
 /
1
 \
  3
Eleman 6:

6, 7'den küçüktür ama 5'ten büyüktür, bu yüzden 6, 5'in sağına eklenir.
    7
   / \
  5   8
 / \
1   6
 \
  3
Eleman 0:

0, 7'den, 5'ten ve 1'den küçüktür, bu yüzden 0, 1'in soluna eklenir.

    7
   / \
  5   8
 / \
1   6
/
0 3



8. **Eleman 9**:
- 9, 7'den ve 8'den büyüktür, bu yüzden 9, 8'in sağına eklenir.


   7
  / \
 5   8
/ \   \
1 6 9 /
0 3


9. **Eleman 4**:
- 4, 7'den, 5'ten ve 1'den büyüktür ama 3'ten büyüktür, bu yüzden 4, 3'ün sağına eklenir.

   7
  / \
 5   8
/ \   \
1 6 9 /
0 3
4


10. **Eleman 2**:
 - 2, 7'den ve 5'ten küçüktür ama 1'den büyüktür, bu yüzden 2, 1'in sağına eklenir.

 ```
    7
   / \
  5   8
 / \   \
1   6   9
/ \
0   3
 / \
2   4
 ```

### BST'nin Son Hali
Bu aşamalardan sonra, BST'nin tam hali:
   7
  / \
 5   8
/ \   \
1 6 9 /
0 3 /
2 4
