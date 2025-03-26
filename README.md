# Caesar-s-Encryption
This project was developed in Python and uses the concept of the Caesar Cipher, combined with symbol substitution, to encrypt messages entered by the user. The approach involves shifting characters in the alphabet and adding an extra layer of complexity through symbolic replacements.

# Full Explanation
This project is designed to encrypt and decrypt texts using the Caesar Cipher, a simple substitution method where each character in a text is shifted by a fixed number of positions in the alphabet. It is interactive, allowing the user to choose between encrypting or decrypting a text, as well as saving the results to a file.
How Encryption Works: The user inputs the text they want to encrypt and provides a numerical key (an integer).
The program shifts each letter of the text based on the provided key. For example, with a key of 3, the letter 'a' becomes 'd', 'b' becomes 'e', and so on. The shift is circular, meaning that when the end of the alphabet is reached, it starts again from the beginning (e.g., 'z' becomes 'c').
To add complexity, the text undergoes an additional substitution process, where specific letters are replaced with symbols.
The encrypted text is saved to a file in the user's documents directory.
How Decryption Works: The user provides the encrypted text along with the same key used to encrypt it.
The program reverses the symbol substitutions to retrieve the original letters.
Then, it applies the reverse shift (subtracting the key) to recover the original text, once again ensuring a circular shift through the alphabet.
The final result is displayed on the console.
