# Ceaser-Cipher: Encode/Decode Game

This project is a Python-based implementation of the Caesar Cipher, one of the earliest and simplest techniques in the history 
of cryptography. The Caesar Cipher works by shifting each letter in a message by a chosen number of positions in the alphabet. 
For example, with a shift of three, the letter “a” becomes “d”, “b” becomes “e”, and so on. When the end of the alphabet is 
reached, the shift wraps around back to the beginning. This project allows users to both encode and decode messages using 
this method, making it an interactive way to explore the foundations of encryption.

The program begins by asking the user whether they would like to encode (encrypt) or decode (decrypt) a message.
Once selected, the user is prompted to enter their message and provide a shift value. The algorithm then processes the 
text by shifting each alphabetical character accordingly while leaving non-alphabet characters, such as spaces, 
punctuation, and numbers, unchanged for readability. The result is displayed to the user, who can then choose to 
either continue with another message or exit the program.

Although the Caesar Cipher itself is not secure by modern standards, it provides a valuable introduction to how 
substitution ciphers and encryption principles work. In real-world scenarios, encryption is used to protect sensitive 
information such as passwords, bank transactions, and private communications. While modern cryptography relies on highly 
advanced mathematical algorithms, the Caesar Cipher represents the foundation upon which these techniques were built. 
Understanding this cipher helps learners grasp the importance of data security and the evolution of cryptographic methods 
over time.

To run this program, you need to have Python installed on your system. Save the project file and execute it using the 
command python filename.py in your terminal or IDE. Once running, simply follow the on-screen prompts to encode or decode 
your own messages. This makes the program both educational and interactive, as it allows you to experiment with different 
inputs and shift values.

This project is an excellent example of how programming can be used to simulate real-world problems and solutions. 
Just as the Caesar Cipher was once used by Julius Caesar to protect military messages, this program shows how encryption 
transforms ordinary text into something that can only be understood with the right key. While simple, it demonstrates the 
crucial role of algorithms, modular arithmetic, and logical thinking in both programming and cybersecurity.
