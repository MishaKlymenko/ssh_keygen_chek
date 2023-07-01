# Generating an SSH Key Pair

To generate an SSH key pair (*public and private*), you need to use the **RSA** encryption algorithm with a length of **4096** bits.

### After generating the keys, you need to upload them to the repository:
* Upload the public key (the key with the .pub extension) to the "keys" folder.
* Add the private key to the repository secrets.

> To create a repository secret, follow these steps:
>  - Go to the Settings tab.
>  ![Go to the Settings tab.](https://scontent.flwo4-1.fna.fbcdn.net/v/t39.30808-6/357030427_3155634571248455_5139720667699006405_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=730e14&_nc_ohc=pWmeG0J_M3sAX8syK_U&_nc_oc=AQmo21KBgATA_-v8Or1lqjeSp2VzRU9dmleJkYMuWqcfEPoSU1MA9u7nboyyfOvnseHUcckEjHWYyMo6xbN9iKeg&_nc_ht=scontent.flwo4-1.fna&oh=00_AfAk-E5mnqJP9_gWos3Q8NhnKuF1yYP1ocMFgySruHoDjg&oe=64A4FCDF)
>  - In the Settings tab, select "Secrets and variables" > "Actions".
>  - Click on the "New repository secret" button.
>  - Provide a name for the private key, and the actual secret value (your private key). The name of the private key should be "private_key".