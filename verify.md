The machine is very straight forward. You check the hashes and then match it with the given one, then decrypt the one that matches with the given key.

first login using hte ssh creds.
Then list sha256sum checksum hashes, and then piping them to grep the given hash.
Only one file will be listed. 
Then pass it with the ./decrypt.sh path/to/file.
![image](https://github.com/user-attachments/assets/30c8eb8d-dd5e-40d0-8a36-0f04483c7214)
