# Algorithmn

## Shuffling

### Fisher-Yates Shuffle

- shuffling a finite sequence
- produces unbiased permuatation, every permutation is equally likely
- time-complexity: O(n)

  function shuffle<T>(array: Array<T>)
    for index in range [array.length -> 0)
      var new_index = 0 < random() < index 
      swap array[index] with array[new_index]
