# Mergy
Mergy is a pdf merger. An App where you can merge more than one pdf files easily! Give it a try.

This project is a Python-based application that uses the Tkinter library for its graphical user interface (GUI). It's designed as a PDF merger tool, allowing users to select multiple PDF files from their computer, add them to a list, and then merge them into a single PDF document. The application is particularly user-friendly, providing a simple and intuitive interface for everyday users who need to combine PDF documents.

### Key Features:

1. **PDF Selection and Display**:
   - Users can browse their file system to select PDF files.
   - Selected files are displayed in a list box within the application, making it easy to see which files are queued for merging.

2. **Interactive GUI**:
   - The interface is built using Tkinter, which is a widely used standard GUI toolkit in Python.
   - It features buttons with icons for adding more PDFs and for initiating the merge process.
   - A scroll bar is provided for ease of navigation when the number of selected PDFs exceeds the display area.

3. **Merge Functionality**:
   - Once the desired PDFs are selected, the user can merge them into a single document by clicking the merge button.
   - The application uses a separate `Merger` class (assumed to be defined in `Merger.py`) for the actual merging process.

4. **User Feedback and Interaction**:
   - The application provides feedback in various forms, such as error messages when trying to merge less than two PDFs.
   - It also includes a right-click menu for additional options like removing a selected PDF from the list.

5. **Customization and Aesthetics**:
   - The GUI is customized with colors, fonts, and icons to enhance user experience.
   - It includes an animated GIF that plays during the merging process, providing a visual indication that the process is ongoing.

6. **Resource Management**:
   - The program uses a function `ResourcePath` to correctly access resource files (like images and icons) both during development and after packaging the application with PyInstaller.

7. **Cross-Platform Compatibility**:
   - As a Python and Tkinter-based application, it's inherently cross-platform, meaning it should work on Windows, macOS, and Linux.

### Usage Scenarios:

- **Office Work**: Ideal for professionals who regularly work with multiple PDF documents and need a quick way to combine them.
- **Academia**: Useful for students or researchers who need to merge different sections of a report or research paper.
- **Personal Use**: Handy for any personal document organization, such as combining travel documents, receipts, or scanned pages.

### Development Details:

- **Python and Tkinter**: The project is developed in Python, making use of the Tkinter library for the GUI, which is known for its simplicity and effectiveness for creating lightweight applications.
- **Modularity**: The code structure suggests a modular design with a separate `Merger` class handling the merging logic, promoting good coding practices.
- **Asset Management**: The application handles resources in a way that supports both development and deployed environments, particularly important when converting the script to a standalone executable.

In summary, this PDF Merger application is a practical tool, built with Python and Tkinter, offering an easy-to-use solution for combining multiple PDF files into a single document through a clean and intuitive interface.
