# OpenSSL

-> can be used for creating key-pairs

-> certificates

-> It can be used for calculating "hash"(encrypted data) or encrypt a confidential file

### Use OpenSSL 
-> It has implementations for almost all type of cryptographic functions.

-> You can use it to encrypt your document or to sign your document.

-> You can also use it set up tls on your webserver.

### Important
    OpenSSL is opensource and it is available for all OS.

#### Two important libraries in OpenSSL

``` LIBSSL ``` -> LIBSSL is used to preform TLS related operations and LIBSSL is dependent on LIBCRYPTO

```LIBCRYPTO``` -> LIBCRYPTO is used by OpenSSL to perform cryptographic operations such as encryption, signing, etc...


### Five Pillars of OpenSSL

-> Integrity

    SHA1 and SHA256 are the normal text files which contains the hash of the software (i.e checksum which checks for error)

-> Confidential

-> Authentication 

-> Authorization 

-> Non-Repudiation

    
