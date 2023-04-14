# RC6-Algorithm  
This is an implementation of the RC6 symmetric block cipher algorithm in [language], designed to provide secure encryption and decryption of data.  

# Background  
The RC6 algorithm is a symmetric block cipher designed by Ronald Rivest in 1996. It is an extension of the RC5 algorithm, with a larger block size and improved diffusion properties. RC6 is considered a secure and efficient algorithm for data encryption and decryption.  

# Usage  
*  To use this project, first clone the repository:  
git clone https://github.com/sudeepsrawat/RC6-Algorithm.git  
* To run RC6 algorithm, place the input file containing plaintext and user key in the same directory with the algorithm  
* Type "python AlgoRC6.py" for encryption. It wil generate a output file with ciphertext  
* To decrypt, place the input file containing the ciphertext and userkey in the same directory  
* Type "python AlgoRC6.py" for decryption. It wil generate a output file with plaintext  
* To encrypt your own string, first convert it into hex value and then paste it in input file replacing the given plaintext  
* Note - Please name the input file as "Input" for both encryption and decryption before running the algorithm (Sample input is provided)  

# Output  
Encryption  
![Screenshot 2023-04-14 130753](https://user-images.githubusercontent.com/101885608/232111270-ab0eaa4d-7ad0-4afe-8dc5-33330ad0c784.png)
  

Decryption 
![Screenshot 2023-04-14 130545](https://user-images.githubusercontent.com/101885608/232110896-5e083bc9-9b38-4d94-9bc4-8be0d6899d8e.png)


# Reference  
The paper used to prepare this algorithm - https://people.csail.mit.edu/rivest/pubs/RRSY98.pdf
