# MP3-Tag-Reader-and-Editor
This project is a C-based MP3 Tag Reader and Editor that reads, displays, and modifies ID3v2 metadata tags in MP3 files. It supports editing fields such as Title, Artist, Album, Year, Genre, and Comments through a command-line interface using efficient binary file handling, modular programming, and standard C libraries.

# MP3 Tag Reader and Editor

The **MP3 Tag Reader and Editor** is a command-line application developed in **C** that enables users to read, display, and modify **ID3v2 metadata tags** stored in MP3 audio files. The project provides an efficient way to manage audio metadata without affecting the actual audio content. It demonstrates the practical use of binary file handling, modular programming, and structured software development in C.

The application supports reading and editing commonly used metadata fields such as **Title, Artist, Album, Year, Genre, and Comments**. It processes MP3 files by accessing the ID3v2 header, extracting the required tag information, and updating selected fields while preserving the integrity of the remaining file data.

Designed with a modular architecture, the project separates functionalities into multiple source and header files, making the code easy to understand, maintain, and extend. It uses standard C libraries for file operations, string manipulation, and memory management, ensuring portability across Linux-based systems.

The project is operated entirely through a **Command-Line Interface (CLI)**, where users can provide commands and arguments to read or modify metadata. Error handling and input validation are implemented to ensure reliable execution when invalid files or incorrect arguments are provided.

### Key Features

* Read ID3v2 metadata tags from MP3 files.
* Edit Title, Artist, Album, Year, Genre, and Comments.
* Preserve original audio data while updating metadata.
* Efficient binary file processing.
* Modular and reusable C code.
* Command-line interface for easy interaction.
* Robust error handling and validation.

### Technologies Used

* C Programming
* GCC Compiler
* Linux/Ubuntu
* Standard C Libraries (`stdio.h`, `stdlib.h`, `string.h`)
* Binary File Handling
* ID3v2 Metadata Format
* Command-Line Interface (CLI)

This project is ideal for learning low-level file manipulation, binary data processing, modular software design, and practical implementation of metadata management in C. It serves as a strong demonstration of systems programming concepts and file handling techniques suitable for academic projects and software development portfolios.
