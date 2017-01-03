# Deep learning using by the iython notebook and Docker
====

Deep learning using by the iython notebook

## Description

I provide the enviroment for deep learning from scratch by the docker and vagrant

https://github.com/oreilly-japan/deep-learning-from-scratch

#
### Install

Vagrant

https://www.vagrantup.com/

```
vagrant up
```

Docker

```
ansible-playbook -i provisioning/hosts provisioning/site.yml
```

#
### Usage
#

You run the docker enviroments

```
docker run -p 8888:8888 -it {deep learning docker image id or docker image name} bash
```

You access docker enviroments, You execute the bellow command

```
ipython notebook --no-browser --port 8888 --ip=*
```

You access the ipython notebook (you type the vagrant ip address)

```
http://192.168.33.25:8888
```

#
### Code Directory Structure
#

```
- docker
- provisioning
Vagrantfile
```

#
### Licence
#
```
The MIT License (MIT)

Copyright (c) 2015 Masaya Ogushi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
#
### Author
#
[SnowMasaya](https://github.com/SnowMasaya)
### References
#
>[Docker](https://www.docker.com/)<br>
>[docker-project-template](https://github.com/ahawkins/docker-project-template)
>[deep-learning-from-scratch](https://github.com/oreilly-japan/deep-learning-from-scratch)
