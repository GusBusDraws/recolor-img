# recolor-img

This project is used to show how Python can be used to replace the colors in an image.

# Project Structure

File structure of the project is as follows:

```
.
├── env  # Virtual environment
├── data  # Directory containing images
├── nbs  # Directory containing Jupyter notebooks
│   ├── 00-nb-intro.ipynb
│   └── 01-recolor-img.ipynb
├── src  # Directory containing any custom modules
│   └── test.py  # custom module containing test function
├── .gitignore
├── README.md  # This documentation file
└── requirements.txt  # File containing dependent packages of environment
```

# Install Instructions

1. Download repository from GitHub
2. Navigate to downloaded directory
3. Open a command line tool (bash/zsh terminal for macOS, Git Bash or cmd for Windows) in this location (or open a terminal and navigate to the location from within the terminal)
4. Check that Python is downloaded:
    ```
    python3 --version
    ```
5. Create a Python virtual environment in a directory we'll call `env`:
    ```
    python3 venv env
    ```
6. Activate your Python environment:
    - On Windows Git Bash cmd:
        ```
        . env\Scripts\activate.bat
        ```
    - On MacOS/Linux bash/zsh terminal:
        ```
        source env/bin/activate
        ```
7. Install the project dependent packages (dependencies) into the currently activated virtual environment using the `requirements.txt` file:
    ```
    python3 -m pip install -r requirements.txt
    ```
8. You can check that all the necessary packages and their dependencies were installed by looking at a list of all the packages installed by pip:
    ```
    python3 -m pip list
    ```

# Optional napari Install Instructions

1. In a terminal within the project directory with your virtual environment activated, run this command to install napari and all its dependencies:
    ```
    python3 -m pip install "napari[all]"
    ```
2. Verify that napari installed by checking its version:
    ```
    napari --version
    ```

# Running Instructions

1. Open a terminal and navigate to your project directory, or open a terminal from your project directory
2. Activate your virtual environment:
    - On Windows Git Bash cmd:
        ```
        . env\Scripts\activate.bat
        ```
    - On MacOS/Linux bash/zsh terminal:
        ```
        source env/bin/activate
        ```
3. Open a Jupyter notebook session with the virtual environment activated:
    ```
    jupyter notebook
    ```
