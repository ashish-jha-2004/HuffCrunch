# Huffman Compression Algorithm in C++

This project implements a file compression tool using the Huffman Coding Algorithm in C++. Huffman coding is a lossless data compression algorithm that uses variable-length codes to represent characters based on their frequencies. This implementation compresses files by creating an optimal binary tree for encoding and decoding.

## Features

- **Efficient Compression:** Uses Huffman coding to achieve lossless file compression.
- **File Input/Output:** Compresses and decompresses files by reading from and writing to the file system.
- **Custom Huffman Tree:** Builds a Huffman Tree based on the frequency of characters in the input file.
- **Binary File Support:** Supports compression of binary files.
- **Decompression:** Ability to decode a compressed file back to its original state.

## How It Works

1. **Frequency Calculation:** The algorithm first reads the input file to calculate the frequency of each character.
2. **Huffman Tree Construction:** A binary tree is built, where characters with higher frequencies have shorter codes.
3. **File Compression:** Each character is replaced with its corresponding binary code to reduce file size.
4. **File Decompression:** The encoded file is decoded using the Huffman Tree to reconstruct the original file.


