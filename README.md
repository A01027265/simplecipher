# Simple Cipher
Simple cipher contains simple implementations of cryptography and cryptoanalysis on Caesar's Cipher, Vigenere's Cipher, and One Time Pads.

## Authors
- Emilio Popovits Blake (A01027265)
- Eduardo Harari (A010)

# Caesar's Cipher
To decipher a ciphertext ciphered with Caesar's Cipher, the program uses the following table of the frequency of the letters of the alphabet in English:

| Letter | Frequency | Proportions | Letter | Frequency | Proportions |
|--------|-----------|-------------|--------|-----------|-------------|
| E      | 11.1607%  | 56.88       | M      | 3.0129%   | 15.36       |
| A      | 8.4966%   | 43.31       | H      | 3.0034%   | 15.31       |
| R      | 7.5809%   | 38.64       | G      | 2.4705%   | 12.59       |
| I      | 7.5448%   | 38.45       | B      | 2.0720%   | 10.56       |
| O      | 7.1635%   | 36.51       | F      | 1.8121%   | 9.24        |
| T      | 6.9509%   | 35.43       | Y      | 1.7779%   | 9.06        |
| N      | 6.6544%   | 33.92       | W      | 1.2899%   | 6.57        |
| S      | 5.7351%   | 29.23       | K      | 1.1016%   | 5.61        |
| L      | 5.4893%   | 27.98       | V      | 1.0074%   | 5.13        |
| C      | 4.5388%   | 23.13       | X      | 0.2902%   | 1.48        |
| U      | 3.6308%   | 18.51       | Z      | 0.2722%   | 1.39        |
| D      | 3.3844%   | 17.25       | J      | 0.1965%   | 1.00        |
| P      | 3.1671%   | 16.14       | Q      | 0.1962%   | (1)         |
<br />
> The third column represents proportions, taking the least common letter (Q) as equal to 1. The letter E is over 56 times more common than Q in forming individual English words.

[Table Source](https://www3.nd.edu/~busiforc/handouts/cryptography/letterfrequencies.html)

| a | b | c | d | e | f | g | h | i | j | k | l | m | n | o | p | q | r | s | t | u | v | w | x | y | z |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| f | g | h | i | j | k | l | m | n | o | p | q | r | s | t | u | v | w | x | y | z | a | b | c | d | e |