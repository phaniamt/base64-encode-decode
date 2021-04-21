# base64-encode-decode

#### Give execute permissions to scripts
```
chmod +x e
chmod +x d
```
#### Move scripts to system path
```
sudo mv e /usr/local/bin/
sudo mv d /usr/local/bin/
```
#### Run the below command for test the base64 encode script
```
e 5000
```
Output : NTAwMA==

#### Run the below command for test the base64 decode script
```
d NTAwMA==
```
Output : 5000
