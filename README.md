1. We first calculate the effective number of rotations d by taking the remainder of d divided by the length of the array n. This is because if d is greater than n, we can reduce it to a smaller value that has the same effect.
2. We create a new array rotatedArray to store the rotated elements.
3. We iterate through the original array a and for each element at index i, we place it at the new index (i + d) % n in the rotatedArray. The % n ensures that we wrap around the array if the new index is out of bounds.
4. Finally, we return the "rotatedArray".
