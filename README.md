PythonCrypto
* This module contain special algorithm which converts normal text to cipher text
* once you enter text with encryption key, text will be converted cipher text. which is nearly impossible to decrpyt without using decryption key.
* increase integrity. 
```python
 #importing encryptor
 from PythonCrypto import Encrypter
 #usage of Encrpter
 Encrypter('text','passkey')
 
 #importing decrypter
 from PythonCrypto import Decrypter
 Decrypter('cipherText','passkey')
```
Developing PythonCrypto
* To install PythonCrypto, along with the tools you need to develop
   and run tests, run the following
  in your virtualenv.
```bash
$ pip install -e .[dev]
```

