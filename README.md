# Dynamic memory allocation

The concept of dynamic memory allocation in c language enables the C programmer to allocate memory at runtime. Dynamic memory allocation in c language is possible by 4 functions of stdlib.h header file.

1.malloc()

2.calloc()

3.realloc()

4.free()

# Algorithm

1.Allocate memory for two integer variables using malloc().

2.Assign a value to the first variable using the first pointer.

3.Increment the first pointer to point to the second variable.

4.Assign a value to the second variable using the first pointer.

5.Use realloc() to change the size of the memory block pointed to by the first pointer.

6.Assign a value to the newly allocated memory location using the new pointer returned by realloc().

# Output

![image](https://user-images.githubusercontent.com/70435939/234365289-a6297a42-73c6-49fb-b911-ca9b5c72b4d5.png)

# Application
1. It is generally used to allocate a sequence of memory blocks (contiguous memory) like an array of elements. It is also present in <stdlib.h> header file.

2. Implementing data structures like linked lists, stacks, and queues.
