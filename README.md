# Off-by-One Error in Java
This repository demonstrates a common off-by-one error in Java when iterating through an array. The `BuggyArray.java` file contains the erroneous code, while `FixedArray.java` provides the corrected version.

**Bug:** The original code attempts to access an array element beyond its bounds, resulting in an `ArrayIndexOutOfBoundsException`.

**Solution:** The corrected code uses the condition `i < array.length` to ensure that the loop iterates only up to the last valid index of the array.