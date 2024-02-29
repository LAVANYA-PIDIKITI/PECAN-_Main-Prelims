# La Vie en Transpose
The file encrypted-text.txt was encrypted using transposition cipher. Try and bruteforce the decryption with help of provided files.
4 files containing 
## `transposition_encrypt.py`
```python
def encrypt_message(key, message):
    ciphertext = [''] * key

    for col in range(key):
        pointer = col

        while pointer < len(message):
            ciphertext[col] += message[pointer]
            pointer += key

    return ''.join(ciphertext)
```
## `encrypted.txt`
```
H
uvtoAseol tn dw  l oasomr ivelwge doh c rsslwd
ooh
AnseTngerhds ee 
a ytGnr hidosov saueheng osghyl   odbaIu lb rmooc eoulh mtoef
 saa
...(so on..)
```
# Solution:
Now construct a program such that it performs decryption
```python
def decrypt_message(key, message):
    ciphertext = [''] * key

    for col in range(key):
        pointer = col

        while pointer < len(message):
            ciphertext[col] += message[pointer]
            pointer += key

    return ''.join(ciphertext)


def load_file(filename):
    with open(filename, 'r') as file:
        return file.read()


# Example usage:
def main():
    key = 5  # The key used for encryption
    filename = 'encrypted-text.txt'  # File containing the encrypted message

    # Load the encrypted message from the file
    encrypted_message = load_file(filename)

    # Decrypt the message using the key
    decrypted_message = decrypt_message(key, encrypted_message)

    # Print the decrypted message
    print("Decrypted Message:")
    print(decrypted_message)


if __name__ == "__main__":
    main()
```
