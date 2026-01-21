# Huffman Compressor

A text file compression tool using Huffman coding algorithm, built with C++.

## About

Data Structures and Algorithms course project that compresses and decompresses text files using Huffman coding. This algorithm encodes characters based on their frequency, reducing file sizes without data loss.

## Features

- **Compress**: Convert text files to compact binary format
- **Decompress**: Restore original text from compressed files
- Lossless compression
- Efficient storage optimization
- Fast data transmission

## Technical Implementation

- Huffman coding algorithm
- Priority queues
- Binary trees
- Character frequency analysis

## How to Run

**Compile:**
```bash
g++ compress.cpp -o compress
g++ decompress.cpp -o decompress
```

**Compress a file:**
```bash
./compress input.txt output.bin
```

**Decompress a file:**
```bash
./decompress output.bin restored.txt
```

## How It Works

1. Analyzes character frequency in input text
2. Builds a Huffman tree based on frequencies
3. Generates binary codes for each character
4. Encodes text using shorter codes for frequent characters
5. Decompressor rebuilds the tree and decodes the binary data

---

Data Structures and Algorithms group project by **tidgeeyyy** and team
