# Generating an SSH Key Pair

The task at hand is to generate an SSH key pair (*public and private*) that will be used to establish secure message exchange.

> **Execution plan:**
> 1. Generate a key pair using the RSA algorithm with a length of 2048 bits.
> 2. Add the private key to the GitHub Secrets with the name PRIVATE_KEY.
> 3. Upload the public key to the keys folder in the format name.pub.