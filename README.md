
# File Search Application

This File Search application allows users to search for files based on file types, file names, and file content within a specific directory selected by the user. Supported file types include `.txt`, `.docx`, and `.pdf`.

## Features

- **Search by File Type**: Filter search results by file type (e.g., `.txt`, `.docx`, `.pdf`).
- **Search by File Name**: Look for files by their names.
- **Search by File Content**: Search within the content of the files for specific keywords.
- **Directory Selection**: Users can select any directory from their PC to perform the search.
- **Case-Insensitive Search**: The search functionality is case-insensitive.

## How to Run

### Prerequisites

- Java Development Kit (JDK) 17 or higher
- JavaFX SDK

### Running the Application

#### Windows

1. **Navigate to the project directory**:
   ```sh
   cd C:\Users\heran\OneDrive\Desktop\demo\target
   ```
2. **Run the application**:
   ```sh
   .\run.bat
   ```

#### Unix-like Environment (WSL or Git Bash)

1. **Navigate to the project directory**:
   ```sh
   cd /mnt/c/Users/heran/OneDrive/Desktop/demo/target
   ```
2. **Make the script executable** (if not already done):
   ```sh
   chmod +x run.sh
   ```
3. **Run the application**:
   ```sh
   ./run.sh
   ```

### Building the Project

To build the project, use the following Maven commands:

1. **Clean and package the project**:
   ```sh
   mvn clean package
   ```

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
