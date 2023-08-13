# DSA-Searching
Every Element occurs twice except for one, Find Unique Element.

Example : 
         0  1  2  3  4   5   6  7  8  9  10  11  12
arr[] = {2, 2, 8, 8, 12, 12, 7, 9, 9, 4, 4, 10, 10}


Psuedo Code : 
      1. If only one element in the array then return one.
      2. If first two element is not equal then return first Occurance.
      3. If last two element is not equal then return first last Occurance.
      4. Mid = (left + right)/2.
      5. Check mid element with mid's left and mid's right if not equal return mid.
      6. If mid index is equal to mid - 1 then mid - 1.
      7. Check if mid number is even then mid + 2.
      8. If not then mid - 1.
  
