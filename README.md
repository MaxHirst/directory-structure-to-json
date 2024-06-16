# Directory Structure to JSON

This script generates a nested JSON file representing the structure of a given directory, including all folders, subfolders, and files. It provides an interactive interface for users to input the directory path and trigger the JSON generation process.

## Features

- **Interactive Directory Input**: Use a text input widget to specify the directory path.
- **Generate JSON**: Click a button to generate the nested JSON file.
- **Output**: The generated JSON file is saved in the specified directory.

## Requirements

- Python 3.x
- `ipywidgets` library
- Jupyter Notebook or JupyterLab

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/MaxHirst/directory-structure-to-json.git
    cd directory-structure-to-json
    ```

2. **Install Required Libraries**:

    Ensure you have `ipywidgets` installed. You can install it using pip:

    ```bash
    pip install ipywidgets
    ```

3. **Launch Jupyter Notebook**:

    ```bash
    jupyter notebook
    ```

## Usage

1. **Open the Notebook**:

    Open the `directory_structure_to_json.ipynb` file in Jupyter Notebook.

2. **Enter Directory Path**:

    Enter the path of the directory you want to analyze in the text input widget labeled "Directory:".

3. **Generate JSON**:

    Click the "Generate JSON" button to generate the nested JSON file. The JSON file will be saved in the specified directory as `directory_structure.json`.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Acknowledgements
- IPython Widgets
- Jupyter Notebook
