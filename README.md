# dockerpack
*Editor: Sam*
## 1. Profile
Build the Dockerfile automatically.
## 2. Installation
1. Download the job
```shell
git pull https://github.com/m4wjw/dockerpack.git
```
2. Grant the executive mod to the file
```shell
chmod +x dockerpack
```
3. Move it to /usr/bin/
```shell
mv ./dockerpack /usr/bin/
```
## 3. Usage
### 3.1 Attention Points
1. You should confirm that the file "Dockerfile" is existing in each package.
2. The "Dockerfile" must be named as "Dockerfile".
### 3.1 Syntax
`dockerpack {the present path of the packages} <-v>`
```shell
-v : verbose
```
### 3.2 Logs
You could find the functioning log in /tmp
### 3.3 Results
Run `docker images`, you could notice that the docker images have been built and preserved in the docker.
