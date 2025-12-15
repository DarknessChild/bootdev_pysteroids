# Pysteroids #
-----
This is my second guided project with [Boot.dev](https://www.boot.dev/).

-----
## Installation Instructions ##

1.  Install `uv` for your platform of choice
    - Skip this step if you have `uv` installed.
    - To check if `uv` is installed, try `uv --version`
    For Windows:
    ```
    pipx install uv
    ```
    For macOS (via Homebrew):
    ```
    brew install uv
    ```
    For Linux:
    ```
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

2.  Clone this repository down locally (using ~/Git as the example starting path)
    ```
    git clone git@github.com:DarknessChild/bootdev_pysteroids.git
    ```
3.  Switch to the cloned directory
    ```
    cd bootdev_pysteroids
    ```
4.  Create a Python Virtual Environment
    ```
    uv venv
    ```
5.  Install dependencies
    ```
    uv sync
    ```
-----
## Instructions to Run ##
1.  Activate the virtual environment
    ```
    source .venv/bin/activate
    ```
2.  Run the game
    ```
    uv run python main.py
    ```
