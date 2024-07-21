# Data Compressor and Decompressor (Java)
This project implements a Java application for compressing and decompressing data files using various algorithms: LZW, GZIP, Huffman, and Run-Length Encoding (RLE).

Features
Compress and decompress files using LZW, GZIP (built-in library), Huffman, and RLE algorithms.
User-friendly interface (optional, depending on implementation) to select the desired algorithm and files.
Displays compression ratio for each algorithm (compressed file size vs. original file size).

Algorithms Implemented
LZW (Lempel-Ziv-Welch): A dictionary-based algorithm that replaces repeating sequences with codes.
GZIP (built-in library): Utilizes the GNU zip compression format for efficient file compression.
Huffman: Assigns shorter codes to more frequent characters, achieving better compression for files with skewed character frequencies.
Run-Length Encoding (RLE): Represents a sequence of identical values with a single value and its repetition count. (Suitable for specific data types)


