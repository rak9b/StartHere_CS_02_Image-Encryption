# StartHere_CS_02_Image-Encryption
# Image Encryption System

A simple and secure image encryption system that uses pixel-level RGB channel manipulation to obscure and restore images.

---

## **Features**
- Encrypts images by altering their pixel RGB channels.
- Decrypts encrypted images to their original state.
- Lightweight and easy to integrate into other projects.

---

## **Setup**

### Prerequisites
- Python 3.8 or newer
- `pip` (Python package manager)

### Installation
1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd StartHere_CS_02_Image
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## **Usage**

### Import the Library
The system provides two primary functions:
- `encrypt_image(input_path, output_path)`
- `decrypt_image(input_path, output_path)`

Example:

```python
from src.image_crypto import ImageCrypto

# Encrypt an image
ImageCrypto.encrypt_image("input.png", "encrypted.png")
print("Image encrypted and saved as 'encrypted.png'.")

# Decrypt the encrypted image
ImageCrypto.decrypt_image("encrypted.png", "decrypted.png")
print("Image decrypted and saved as 'decrypted.png'.")
