
### Case 1: 22 27 16 2 18 6 (Merge Sort)
## Aşama 1: 22 27 16  --  2 18 6
## Aşama 2: 22 27 -16 -- 2 18 - 6
## Aşama 3: 22 -27 -16 -- 2 - 18 - 6
## Aşama 4: 22 27 - 16 -- 2 18 -6
## Aşama 5: 16 22 27 -- 2 6 18  
## Aşama 6: 2 6 16 18 22 27
n - n/2 - n/4 - n/8 şeklinde gittiği için. 2^x=n 'den o(log(n)) olarak time complexity iafde edilebilir.

### Case 2: Average Case'dir çünkü 18 ortada.

### Case 3: 7,3,5,8,2,9,4,15,6  Selection Sort
## Aşama 1: 2,3,5,8,7,9,4,15,6
## Aşama 2: 2,3,5,8,7,9,4,15,6
## Aşama 3: 2,3,5,8,7,9,4,15,6
## Aşama 4: 2,3,5,6,7,9,4,15,8