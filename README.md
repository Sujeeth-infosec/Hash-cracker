   ![Hash buster pic](https://github.com/Sujeeth-infosec/Hash-cracker/assets/56471468/0e50c587-ab57-4859-946e-ff47c50d4337)

  # Hash-Cracker

![Hash buster linux](https://github.com/Sujeeth-infosec/Hash-cracker/assets/56471468/6884f877-47fd-4d1a-843a-0c62a1668052)
# Features
+ Automatic hash type identification
+ Supports MD5, SHA1, SHA256, SHA384, SHA512
+ Can extract & crack hashes from a file
+ Can find hashes from a directory, recursively
+ Multi-threading

# Installation

Hash program can be run directly from the python script but I highly suggest you to install it with # make install

After the installation, you will be able to access it with buster command.




# Cracking_hash

You don't need to specify the hash type. Hash Buster will identify and crack it under 3 seconds.

# Usage

      buster -s <hash>  

By using this command you can crack an hash code into an normal password 


# Cracking hashes from a file


Hash can find your hashes even if they stored in a file like this 

    simple@gmail.com:21232f297a57a5a743894a0e4a801fc3
    {"json@gmail.com":"d033e22ae348aeb5660fc2140aec35850c4da997"}
    surrondedbytext8c6976e5b5410415bde908bd4dee15dfb167a9c873fc4bb8a81f6f2ab448a918surrondedbytext




# specifying number of threading 

Multi-threading can incredibly minimize the overall speed when you have a lot of hashes to crack by making requests in parallel.
    
    Hash -f /root/hash.txt -t 10
