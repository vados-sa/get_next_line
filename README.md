# get_next_line

## 📝 Overview  
get_next_line is a function that retrieves a single line from a specified file descriptor, allowing sequential reading of file contents until EOF. This project is part of 42’s Common Core and focuses on low-level file manipulation in C.

## 🔧 Key Concepts Learned  
- **File Descriptors**: Reading from files, standard input, and other sources  
- **Static Variables**: Maintaining state across function calls  
- **I/O Operations**: Efficiently handling `read()` and managing buffers  
- **Memory Management**: Avoiding leaks while dynamically allocating memory using `malloc()` and `free()`
- **Custom Buffer Size**: Flexible compilation with different buffer sizes  

## 📌 How It Works  
1. Uses `read()` to fetch data from the file descriptor.  
2. Stores and manages data using a **static variable** to handle partial reads.  
3. Extracts a full line and returns it, keeping track of the remaining content.  
4. Repeats until EOF is reached, ensuring efficient memory usage.

## 🔹 Bonus Features  
- **Single Static Variable**: Implement `get_next_line` with only one static variable.  
- **Multiple File Descriptors**: Handle multiple file descriptors simultaneously, allowing interleaved reading without mixing lines from different sources.  


This project deepened my understanding of **file handling**, **dynamic memory allocation**, and how to build **robust, reusable functions** in C.
