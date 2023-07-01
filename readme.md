# Generating an SSH Key Pair

To generate an SSH key pair (*public and private*), you need to use the **RSA** encryption algorithm with a length of **4096** bits.

### After generating the keys, you need to upload them to the repository:
* Upload the public key (the key with the .pub extension) to the "keys" folder.
* Add the private key to the repository secrets.

> To create a repository secret, follow these steps:
>  - Go to the Settings tab.
>  ![Go to the Settings tab.](https://drive.google.com/drive/u/0/folders/1p4-5gPrntz-0KZ8gTfRaMhcxgRtA3NRi)
>  - In the Settings tab, select "Secrets and variables" > "Actions".
>  - Click on the "New repository secret" button.
>  - Provide a name for the private key, and the actual secret value (your private key). The name of the private key should be "private_key".