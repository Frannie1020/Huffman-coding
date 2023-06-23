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
Marking criteria for the lab report, including the following:  
 whether the experimental report is standardised  
 whether the content of the lab report is detailed  
 whether the lab report contains function call diagrams, flowcharts, class diagrams and their textual descriptions  
 whether the code comments in the lab report meet the requirements  
 whether the program is correct  
 whether the program is written in strict accordance with the principle of sub-functions  
 how well the C++ version of the program is coupled in terms of class relationships  
 whether the implementation of the program takes into account the large file case  

