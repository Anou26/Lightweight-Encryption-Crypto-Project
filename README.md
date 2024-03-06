
## Lightweight Encryption Techniques

# Project Overview

This project offers an in-depth exploration and analysis of various encryption techniques, with a focus on lightweight cryptographic algorithms. It demonstrates the implementation, efficiency, and security aspects of several encryption methods, presenting a comparative study of their performance.

# Objective

The primary goal is to understand and compare different encryption algorithms, particularly emphasizing lightweight cryptography. This includes measuring encryption and decryption times, analyzing entropy, and contrasting these with more traditional, non-lightweight cryptography techniques.

# Key Features

Detailed implementation of ChaCha20, Salsa20, RC4, Hybrid encryption (RSA + AES), and 3DES.
Performance analysis (encryption/decryption times).
Entropy evaluation for assessing randomness and security.
Comparative studies between lightweight and non-lightweight cryptographic techniques.

# Libraries Used

cryptography.hazmat for core cryptographic functions.
OpenCV (cv2) for image processing.
numpy for numerical computations.
os and time for system operations and timing functions.
PyCrypto (Crypto.Cipher, Crypto.PublicKey, Crypto.Random) for cryptographic operations.
matplotlib for data visualization.
How to Implement the Code

# 1. Environment Setup
Ensure Python and Jupyter are installed on your system. Install the necessary libraries using pip:

bash
Copy code
pip install cryptography opencv-python numpy matplotlib pycryptodome
# 2. Running the Notebook
Clone the repository or download the Jupyter notebook file (Crypto_Project.ipynb).
Open the notebook in a Jupyter environment (Jupyter Lab or Jupyter Notebook).
Run the cells in sequence to observe the implementation and results.
# 3. Code Structure and Implementation
The notebook is structured into several key sections, each dedicated to a specific encryption technique.

ChaCha20, Salsa20, RC4

# Implementation: 
The initial sections cover the implementation of lightweight cryptography techniques like ChaCha20, Salsa20, and RC4.
# Performance Analysis:
Each section includes code to measure the encryption and decryption times, providing insights into the efficiency of each algorithm.
# Entropy Analysis: 
These sections also include entropy evaluation to assess the randomness and security strength of each algorithm.

## Hybrid Encryption (RSA + AES) and 3DES

# Non-Lightweight Techniques: 
Further sections delve into more traditional cryptographic methods, illustrating their implementation.

# Comparative Analysis: 
Performance metrics are gathered similarly to lightweight techniques for a comparative perspective.

# Final Analysis
The notebook concludes with a comprehensive comparison, illustrating the differences in performance and security between lightweight and non-lightweight cryptography techniques.

## How to Run

Download the lung image file from the provided zip folder.

Input file: lung.png

Adjust the file paths in the code to match the location of your image file. This step is essential for the code to find and process the image properly.
When you run each algorithm, a window will open showing the decrypted image.

Output: Each algorithm will produce an encrypted image, which will then be decrypted.

To move on to the next section of the code, you must manually stop the kernel after viewing each decrypted image. This is usually done through the Jupyter notebook interface.
Note: It's important to stop the kernel to close the image window and proceed with the rest of the notebook.

This README provides detailed instructions for setting up, running, and understanding the project.