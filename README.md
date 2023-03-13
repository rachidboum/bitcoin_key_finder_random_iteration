# bitcoin_key_finder_random_iteration

# **Bitcoin Key Finder**
This program is a tool for finding private keys of Bitcoin wallets using brute-force methodology. 
It searches for private keys within a user-defined range and checks if any of them correspond to a Bitcoin address listed in a TXT file.

## requirements
To run this program, you will need:
•	Python 3.7 or higher
•	bit and multiprocessing libraries
You can install the necessary libraries using pip: 
pip install bit multiprocessing 
	
## Usage
1.	Download the code and save it to your computer.
2.	Save the list of Bitcoin addresses you want to search in a TXT file. One address per line.
3.	Open a terminal or command prompt and navigate to the directory where the code is saved.
4.	Run the program by entering the following command:
python bitcoin_key_finder.py 
5.	The program will prompt you to enter the range of private keys you want to search. 
6.	Enter the minimum and maximum values in decimal 1==115792089237316195423570985008687907852837564279074904382605163141518161494335.
7.	The program will display an estimated time for completion and start searching for private keys. 
8.	If a private key corresponding to one of the Bitcoin addresses is found, it will be saved to a file named CompressedWinner.txt or UncompressedWinner.txt, depending on the address type.
9.	When the program finishes, it will log the total time taken for the search.

### Note: The program is optimized for multi-core CPUs, and it will use all available cores by default. You can modify the number of cores used by changing the cores variable value in the code.

