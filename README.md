# AES-Encryption_JS-app
Implementing a javascript AES encryption app that takes in 32 bit plain text (in hex) and returns the actual AES cipher (in hex).

The app runs very efficiently due to the use of lookup tables that makes encryption almost instantaneous.
The output can also show the encryption state at the ten different rounds of AES. Each round shows the current used key and the text that is being encrypted.
The states are shown in matrices of 4 words (4 bytes each).
