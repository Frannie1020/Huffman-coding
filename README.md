# Huffman coding

💡Experiment requirements  
This experiment requires the implementation of an exe program. This program follows the huffman encoding style and contains both a compression function and a decompression function. The user compresses with the following command:  
C:\>test.exe -c uncompress_filename compress_filename  
In the above command, test.exe is the program name and -c means to compress. uncompress_filename is the name of the file to be compressed and can contain path information, while compress_filename is the name of the file after compression and can also contain path information. The user can uncompress with the following command:  
C:\>test.exe -u compress_filename uncompress_filename  
In the above command, -u means to execute the uncompress command. compress_filename is the name of the file to be uncompressed, which can contain path information; uncompress_filename is the file obtained after decompression, which can also contain path information.  

💡Tip: When implementing the test.exe program, you need to consider how to store the huffman tree or encoding table or word frequency table, etc.  
This experiment requires the implementation of two versions of the test.exe program, one in C and the other in C++. The requirements for both versions are as follows:  
 For each version of the program, a diagram of the function call relationships, a diagram of the flow processing relationships and a textual description of them are required in the lab report;  
 For each version of the program, the source code needs to be given in the lab report. For checking purposes, the proportion of comments in the code should be 20% of the total number of lines;  
 For the C++ version of the program, a class relationship diagram needs to be given.  

