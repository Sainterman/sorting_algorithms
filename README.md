# Sorting Algorithms
Sorting algorithms implemented in C language including bubble sort, insertion sort, quick sort etc...

## Data Structures and Functions:
### Functions:
#### * [print_array](./print_array.c): Print array of integers
#### * [print_list](./print_list.c): Print a list of integers

### Data Structures:
#### *[doubly linked list]

``` c-objdump
/**
** struct listint_s - Doubly linked list node
*
* @n: Integer stored in the node
* @prev: Pointer to the previous element of the list
* @next: Pointer to the next element of the list
*/
      typedef struct listint_s
      {
          const int n;
              struct listint_s *prev;
                  struct listint_s *next;
} listint_t;
```

### Big-O format used for tasks
* O(1)
* O(n)
* O(n!)
* n square -> O(n^2)
* log(n) -> O(log(n))
* n * log(n) -> O(nlog(n))
* n + k -> O(n+k)

## Tasks:
### * [0.Bubble sort](./0-bubble_sort.c)
