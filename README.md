
# File Sorter

This project is a Python-based script designed to automatically sort files in a folder by their extensions. The script moves files into corresponding folders named after their extension types (e.g., `.txt` files go into a `txt_files` folder). It's flexible and can handle a variety of file types, allowing users to run it on any folder by providing the folder path as input.

## Features

- Automatically sorts files based on their extensions.
- Creates new folders for each file type (if they don't already exist).
- Handles a wide range of file types.
- Platform-independent (works on Linux, macOS, and Windows).

## Requirements

- Python 3.x
- Libraries: `os`, `shutil` (both are built-in Python libraries).

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/atomos2/file-sorter.git
   cd file-sorter
   ```

2. Run the Jupyter notebook or the Python script:

### Running the Script

- If you're running the Python script directly, use the command below:
   ```bash
   python file_sorter.py
   ```

- When prompted, enter the full path of the folder you want to sort:
   ```
   Enter the full path of the folder you want to sort: /path/to/your/folder
   ```

3. The script will create new folders for each file type (if they don't already exist) and move the files into the corresponding folders.

### Running in Jupyter Notebook

If you prefer to run the notebook, use the following command to open it in Jupyter:
```bash
jupyter notebook FileSorter.ipynb
```
Execute the cells to run the sorting process within the notebook environment.

## Example

Before running the script, the folder structure might look like this:

```
/path/to/your/folder
   ├── report.docx
   ├── photo.jpg
   ├── data.csv
   ├── script.py
```

After running the script, the folder will be organized like this:

```
/path/to/your/folder
   ├── docx_files
       └── report.docx
   ├── jpg_files
       └── photo.jpg
   ├── csv_files
       └── data.csv
   ├── py_files
       └── script.py
```


### Key Sections in This `README.md`:
- **Project Title and Description**: A brief explanation of what the project does.
- **Features**: Lists the capabilities of your file sorter script.
- **Requirements**: Specifies Python and the required libraries.
- **How to Use**: Explains how to run the script or notebook step by step.
- **Example**: Demonstrates how files are sorted and organized in a sample folder.


