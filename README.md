# Secured-File-Sharing-Through-Quantum-Computing.
This project implements a secure file-sharing system that leverages Advanced Encryption Standard (AES) and Quantum Cryptography to ensure resilience against classical and quantum-based attacks. By integrating Quantum Key Distribution (QKD) and steganography, the system facilitates secure key exchange and covert data transmission. It utilizes AWS Cloud Storage for scalable and remote access while maintaining data integrity, making it suitable for critical industries like finance, healthcare, and defense.

**Output**

![1](https://github.com/user-attachments/assets/529a9b65-d1f7-4d28-9c6d-a0f6d1d5d39d)
![2](https://github.com/user-attachments/assets/c9a38d49-2f7d-421e-a715-ce4da092259c)
![3](https://github.com/user-attachments/assets/b80e268e-6617-4549-ab7c-b6c24c331367)
![4](https://github.com/user-attachments/assets/55e26168-c3ee-49ed-8c87-96f05666b41a)
![5](https://github.com/user-attachments/assets/707f0eba-a955-443b-a2dd-c4ff17a13813)

Features

	•	Quantum Key Distribution (QKD): Ensures secure key exchange with quantum cryptographic techniques.
	•	Advanced Encryption Standard (AES): Provides robust encryption for sensitive data.
	•	Steganography: Embeds encrypted data into images for covert file transmission.
	•	AWS Cloud Integration: Offers scalable and efficient file storage and access.
	•	Future-Proof Security: Combines classical and quantum-resistant encryption methods.
	•	Performance Validations: Rigorous testing for reliability, efficiency, and resilience against quantum threats.

Technologies Used

	•	Quantum Computing (Quantum Key Distribution)
	•	AES Encryption
	•	Steganography
	•	AWS Cloud Services
	•	Python/Other Relevant Programming Languages

Getting Started

Prerequisites

	1.	Install Python (or any language used).
	2.	Set up an AWS account for cloud storage services.
	3.	(Optional) Quantum Cryptography libraries/frameworks if specific to the project (e.g., Qiskit).

Installation

	1.	Clone this repository:

git clone https://github.com/yourusername/quantum-secure-file-sharing.git
cd quantum-secure-file-sharing


	2.	Install dependencies:

pip install -r requirements.txt


	3.	Configure AWS credentials for cloud access.

Usage

	1.	Run the key generation module for Quantum Key Distribution (QKD):

python qkd_key_generation.py


	2.	Encrypt the file using AES:

python aes_encrypt.py --input <file_path>


	3.	Embed the encrypted file into an image using steganography:

python steganography_embed.py --image <image_path> --data <encrypted_file>


	4.	Upload the steganographed image to AWS Cloud Storage:

python upload_to_aws.py --file <file_path>



File Sharing Process

	1.	The recipient downloads the steganographed image from AWS.
	2.	Extract the encrypted data using the steganography extraction module.
	3.	Decrypt the file using the AES decryption module and the shared quantum key.

Project Architecture

	•	Encryption: AES + Quantum Cryptographic keys
	•	Data Transmission: Steganography for covert channels
	•	Cloud Integration: AWS for secure, scalable storage

Performance Testing

The system has been validated for:

	•	Encryption and Decryption Time
	•	Steganographic Embedding and Extraction Speed
	•	Quantum Resilience
	•	AWS File Access Latency

Applications

	•	Finance: Secure transactions and sensitive data sharing.
	•	Healthcare: Protection of patient records and research data.
	•	Defense: Confidential communication and secure file exchanges.

Contributing

Contributions are welcome! Please follow these steps:

	1.	Fork the repository.
	2.	Create a new branch for your feature:

git checkout -b feature-name


	3.	Commit your changes:

git commit -m "Add your message here"


	4.	Push your branch:

git push origin feature-name


	5.	Open a pull request.

License

This project is licensed under the MIT License.

Acknowledgments

	•	Quantum Computing Libraries/Resources (if applicable)
	•	Tutorials and communities that supported the development.
