1. Create an empty area for the sorted books (call this "Sorted Pile").
2. Pick up one book from the unsorted pile.
3. If the sorted pile is empty, place the book onto the sorted pile.
4. Start at the top of the sorted pile, while you haven't reached the end of the sorted pile and the current book's title is alphabetically after the title of the book you're comparing it with, move to the next book in the sorted pile.
5. Repeat step 4 until you find the first book in the sorted pile that is alphabetically **before** the picked book.
6. Insert the current book into the sorted pile right before the first alphabetically before book.
7. If the unsorted pile is not empty, jump to step 2.
8. The sorted pile now has all the books in alphabetical order.


# Pseudocode for Sorting Books Alphabetically

``` pseudocode
Create an empty area for the sorted books (call this "Sorted Pile").
Ensure all your books are in the "Unsorted Pile".

while (the Unsorted Pile is not empty) do:
    Pick up one book from the Unsorted Pile.
    If (the Sorted Pile is empty):
        Place the book onto the Sorted Pile.
    else:
        Start at the top of the Sorted Pile.
        While (you haven't reached the end of the Sorted Pile &&
                the current book's title is alphabetically after the title of the book you're comparing it with) do:
            Move to the next book in the Sorted Pile.
        Insert the current book into the Sorted Pile at the correct position.
    if (the Unsorted Pile is empty):
        break

The Sorted Pile now has all the books in alphabetical order.
```

