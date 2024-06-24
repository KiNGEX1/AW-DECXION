# AW-DECXION

AW-DECXION decrypts files using Base64, Marshal, zlib, Rot13, and AES encryption methods with ease.

## Features

- Decrypts Base64 encoded strings
- Decrypts Marshal serialized and encoded strings
- Decrypts zlib compressed strings
- Decrypts Rot13 encoded strings
- Decrypts AES encrypted strings

## Version

1.5

## Author

[KiNGEX](https://t.me/join_another_world), [Nork](https://t.me/join_another_world)

## Installation

### Prerequisites

- Python 3.x
- Pip (Python package manager)

### Termux

1. **Install Python and Pip**:
    ```sh
    pkg install python
    pkg install python-pip
    ```

2. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/AW-DECXION.git
    cd AW-DECXION
    ```

3. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

### Kali Linux

1. **Install Python and Pip**:
    ```sh
    sudo apt update
    sudo apt install python3 python3-pip
    ```

2. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/AW-DECXION.git
    cd AW-DECXION
    ```

3. **Install Dependencies**:
    ```sh
    pip3 install -r requirements.txt
    ```

### Windows

1. **Install Python and Pip**:
    - Download and install Python from [python.org](https://www.python.org/downloads/).
    - Ensure `pip` is installed by running the following command in Command Prompt:
        ```sh
        python -m ensurepip --upgrade
        ```

2. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/AW-DECXION.git
    cd AW-DECXION
    ```

3. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Navigate to the AW-DECXION directory**:
    ```sh
    cd AW-DECXION
    ```

2. **Run the Script**:
    ```sh
    python aw_decxion-tool.ENC.py
    ```

3. **Follow the Prompts**:
    - The script will display decryption options.
    - Enter the option number corresponding to the encryption method of the file.
    - Enter the path to the encrypted file.
    - If AES decryption is chosen, you will be prompted to enter the AES decryption key.

4. **Decrypted Content**:
    - The decrypted content will be saved in a file named `decrypted_content.txt` inside the `decrypted_files` folder.

## Example

```sh
$ python aw_decxion.py

AW-DECXION
Developed by: KiNGEX,Nork
Version: 1.5

AW-DECXION decrypts files using Base64, Marshal, zlib, Rot13, and AES encryption methods with ease

Decryption Options:
1. Base64
2. Marshal
3. zlib
4. Rot13
5. AES

Enter option number: 1
Enter path to encrypted file: path/to/encrypted_file.txt

Decrypted content saved to: decrypted_files/decrypted_content.txt
