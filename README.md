# Anaconda commands:

## Basic Conda Commands

- **Check conda version:**

  ```bash
  conda --version
  ```

- **Update conda:**

  ```bash
  conda update conda
  ```

- **Update Anaconda distribution:**

  ```bash
  conda update anaconda
  ```

## Creating Environments

- **Create a new environment with a specific Python version:**

  ```bash
  conda create -n myenv python=3.8
  ```

## Activating/Deactivating Environments

- **Activate an environment:**

  ```bash
  conda activate myenv
  ```

- **Deactivate the current environment:**

  ```bash
  conda deactivate
  ```

## Listing Environments

- **List all environments:**

  ```bash
  conda env list
  ```

## Removing Environments

- **Remove an environment:**

  ```bash
  conda remove --name myenv --all
  ```

## Packages

- **List all installed packages in the current environment:**

  ```bash
  conda list
  ```

- **Update a package:**

  ```bash
  conda update numpy
  ```

- **Update all packages in the environment:**

  ```bash
  conda update --all
  ```

- **Remove a package from the current environment:**

  ```bash
  conda remove numpy
  ```

- **Search for a package:**

  ```bash
  conda search package-name
  ```

- **Clean unused packages and caches:**

  ```bash
  conda clean --all
  ```
