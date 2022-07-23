# Binary-Search-Tree-Projesi
## Binary Search Tree Bitirme Projesi [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

# Aşamalar
## Dizinin en başındaki sayı 7 olduğundan kök (ROOT) = 7 dir.
www.patika.dev


7 den küçük sayılar Rootun soluna, büyük sayılar ise sağına yazılır. Dallanan sayılarda da aynı işlem devam eder.

          7
         /                                        (5 sayısı 7den küçüktür.)
        5
        
        
          7
         /
        5
       /                                          (1 sayısı 7den ve 5den küçüktür.)
      1
     
    
         7
        / \
       5   8                                      (8 sayısı 7den büyüktür.)
      /
     1   
     
     
         7
        / \
       5   8
      /
     1
      \                                           (3 sayısı 7den küçük 1den büyüktür.)
       3
       
       
          7
         / \
        5   8
       / \
      1   6                                       (6 sayısı 7den küçük 5den büyüktür.)
       \                                          
        3
        
        
          7
         / \
        5   8
       / \
      1   6
     / \                                         (0 sayısı 7den küçük,5 ve 1den küçüktür.)
    0   3
    
    
          7
         / \
        5   8
       / \   \
      1   6   9                                  (9 sayısı 7 ve 8den büyüktür.)
     / \
    0   3
    
    
           7
          / \
         5   8
        / \   \
       1   6   9
      / \
     0   3
          \                                      (4 sayısı 7,5,1 den küçük 3den büyüktür.)
           4


           7
          / \
         5   8
        / \   \
       1   6   9
      / \
     0   3
        / \                                      (2 sayısı 7,5 den küçük, 1 sayısından büyük, 3 sayısından küçüktür.)
       2   4