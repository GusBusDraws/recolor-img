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
3. Check that Python is downloaded:
    ```
    python3 --version
    ```
4. Create a Python virtual environment in a directory we'll call `env`:
    ```
    python3 venv env
    ```
5. Activate your Python environment from a cmd or bash terminal from **within** the project directoy:
    - On Windows cmd.exe:
        ```
        . env\Scripts\activate.bat
        ```
    - On MacOS/Linux bash:
        ```
        source env/bin/activate
        ```
6. Install the project dependent packages (dependencies) into the currently activated virtual environment using the `requirements.txt` file:
    ```
    python3 -m pip install -r requirements.txt
    ```
7. Open a Jupyter notebook session with our virtual environment activated:
    ```
    jupyter notebook
    ```
