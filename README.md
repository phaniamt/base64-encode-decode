# base64-encode-decode

#### Encode string into base64 example

```
echo -n hello | base64
```
Output: aGVsbG8=
#### Decode string into base64 example
```
echo `echo aGVsbG8= | base64 -d`
```
Output: hello

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
e hello
```
Output : aGVsbG8=

#### Run the below command for test the base64 decode script
```
d aGVsbG8=
```
Output : hello
