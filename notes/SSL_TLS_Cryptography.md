1. sysmmetric encryption  
sysmmetric encryption also known as private-key cryptography,In order to ensure communication security,Alice and Bob first get the encryption algorithm and key recognized by both parties, When Alice needs to send data to Bob, she uses this key to encrypt the data. Bob uses the same key to decrypt the data, Eve can access the channel, So he can see the encrypted data,but because there is no key, so the original data can not been seen,Alice and Bob can always communicate securely as long as the key is secure.
> **Attention**:  
Three terms are used when discussing encryption: **plaintext**(raw data)、**cipher**(use for encryption)、**ciphertext**(encrypted data)
2. asymmetric encrytion
asymmetric encryption also known as public key encryption,uses two keys, one for private user and the other for shared by everyone . If you use someone's public key to encrypt data, then only their private key Being able to decrypt , on the other hand, if someone encrypts the data with a private key, anyone can use the corresponding public key to unlock the message, This latter operation does not provide confidentiality, but can be used as a digital signature
