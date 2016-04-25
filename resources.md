#Resources
#Strategy
Using a compile time flag we will allow the user to set the address space that they want their smart pointers to use. This define will set up the allocator to use on the smart pointer and the custom allocator will be some particular implementation.

The memory manager will hold a vector of pointers to the blocks of memory we have received from the OS.

A library that will be included in a header file. 

We will provide a base class with the smart pointer for the user to use.

We will overide new and delete for the smart pointer class?

Using Catch for unit testing

[Catch](https://github.com/philsquared/Catch)

[The Lost Art of C Structure Packing](http://www.catb.org/esr/structure-packing/#_bitfields)

[Pragma, Type Ordering, and char Arrays](http://stackoverflow.com/questions/4301759/disable-structure-padding-in-c-without-using-pragma)

[Smart Pointers in c++](https://msdn.microsoft.com/en-us/library/hh279674.aspx)

[Building your own memory manager for C/C++ projects](https://www6.software.ibm.com/developerworks/education/au-memorymanager/au-memorymanager-pdf.pdf)
