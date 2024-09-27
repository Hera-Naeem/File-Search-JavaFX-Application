
# File Search Application

This File Search application allows users to search for files based on file types, file names, and file content within a specific directory selected by the user. Supported file types include `.txt`, `.docx`, and `.pdf`.

## Features

- **Search by File Type**: Filter search results by file type (e.g., `.txt`, `.docx`, `.pdf`).
- **Search by File Name**: Look for files by their names.
- **Search by File Content**: Search within the content of the files for specific keywords.
- **Directory Selection**: Users can select any directory from their PC to perform the search.
- **Case-Insensitive Search**: The search functionality is case-insensitive.

### Prerequisites

- Java Development Kit (JDK) 17 or higher
- JavaFX SDK

## Dependencies

- **JavaFX**: For building the GUI.
- **Apache PDFBox**: For handling PDF files.
- **Apache POI**: For handling `.docx` files.
- **Log4j**: For logging purposes.

### Configuration

The necessary dependencies and plugins are defined in the `pom.xml` file.

## Notes

- Ensure the `javafx-sdk` path is correctly specified in the `run.bat` and `run.sh` scripts.
- This application requires a proper JavaFX setup to run successfully.
