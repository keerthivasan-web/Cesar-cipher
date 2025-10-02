# Cesar-cipher
The Caesar cipher is a simple substitution cipher where each letter in a plaintext message is shifted a fixed number of positions down the alphabet. For example, with a shift of 3, 'A' becomes 'D', 'B' becomes 'E', and so on. To decrypt, the process is reversed, shifting the letters back by the same amount.
How it works
Choose a key: A fixed number (the shift value) is chosen for the cipher. 
Encrypt: Each letter in the message is replaced with a letter a fixed number of places further down the alphabet. 
Wrap-around: If the shift goes past 'Z' (or 'z'), it wraps around to the beginning of the alphabet. 
Non-letters: Numbers, spaces, and punctuation remain the same. 
Decrypt: To decrypt, you shift each letter backward by the same fixed number. 
Example
With a shift of 3: 
Plaintext: ATTACK AT ONCE
Encrypted: DWWDFN DW RQFH
Key Features
Simple substitution: Each letter is replaced with another letter. 
Fixed key: A single, fixed number (the shift) determines the encryption for the entire message. 
Historical significance: It's one of the oldest known encryption techniques, reportedly used by Julius Caesar. 
Weak security: The Caesar cipher is very easy to break, often through frequency analysis or brute force by trying all 25 possible shifts. 
