# Generating an SSH Key Pair

To generate an SSH key pair (*public and private*), you need to use the **RSA** encryption algorithm with a length of **4096** bits.

### After generating the keys, you need to upload them to the repository:
* Upload the public key (the key with the .pub extension) to the "keys" folder.
* Add the private key to the repository secrets.

> **To create a repository secret, follow these steps:**
>
>  ***- Go to the Settings tab.***
>
>  ![Go to the Settings tab.](https://scontent.flwo4-1.fna.fbcdn.net/v/t39.30808-6/357030427_3155634571248455_5139720667699006405_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=730e14&_nc_ohc=pWmeG0J_M3sAX8syK_U&_nc_oc=AQmo21KBgATA_-v8Or1lqjeSp2VzRU9dmleJkYMuWqcfEPoSU1MA9u7nboyyfOvnseHUcckEjHWYyMo6xbN9iKeg&_nc_ht=scontent.flwo4-1.fna&oh=00_AfAk-E5mnqJP9_gWos3Q8NhnKuF1yYP1ocMFgySruHoDjg&oe=64A4FCDF)
>
>  ***- In the Settings tab, select "Secrets and variables" > "Actions".***
>
>  ![In the Settings tab, select "Secrets and variables" > "Actions".](https://scontent.flwo4-2.fna.fbcdn.net/v/t39.30808-6/357414557_3155636124581633_4623543185013486187_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=730e14&_nc_ohc=-ZvwsxlAnHoAX8Gc6SJ&_nc_ht=scontent.flwo4-2.fna&oh=00_AfDcm0SnpmCb_LSIUU9iL4qDJb9j5v2O14v4pwet5410Sg&oe=64A402B7)
>
>  ***- Click on the "New repository secret" button.***
>
>  ![Click on the "New repository secret" button.](https://scontent.flwo4-2.fna.fbcdn.net/v/t39.30808-6/356876959_3155640201247892_824621912438044762_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=730e14&_nc_ohc=B4p68nBoA8wAX93o5xK&_nc_ht=scontent.flwo4-2.fna&oh=00_AfDF_9RGGYm0zIIFdrnsrZfjhe2d7dpHouQX8lgPCF3LRg&oe=64A3D8A2)
>
>  ***- Provide a name for the private key, and the actual secret value (your private key). The name of the private key should be "private_key".***
>
>  ![Provide a name for the private key, and the actual secret value (your private key). The name of the private key should be "private_key".](https://scontent.flwo4-2.fna.fbcdn.net/v/t39.30808-6/356264089_3155641861247726_9136241533568193152_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=730e14&_nc_ohc=hamvYbcMX3MAX9zNgCW&_nc_ht=scontent.flwo4-2.fna&oh=00_AfCOcpWj-9Vu4xJUHHu9IgYQXZ6diMJAku7hbuuVha08WA&oe=64A44013)