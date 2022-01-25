# routerdos
Python code that runs a dos (denial-of-service) attack in a router network

**WARNING** For educational purposes only, **DO NOT** use for Malicious purposes. Only use on routers with consent. Attacking a network by dos is **Highly Illegal**. If you conduct a DDoS attack, you could receive a prison sentence, a fine or both.


Repository is not liable for any damages or inconvenience the code can possibly cause

**WHAT IS IT?**

a denial-of-service attack is a cyber-attack in which the perpetrator seeks to make a machine or network resource unavailable to its intended users by temporarily or indefinitely disrupting services of a host connected to a network.

**INFO** Using low-end Machines is not adviced since you will be sending thousands of data. 

**What it does?**
This code is made to not be powerful enough to actually take down the network while running. It stresses the network to the point that it is unusable.
(Ex. from 50mbps to 0.8mbps). As this is a dos attack, the code is limited by the power of the machine.


**REQUIREMENTS**

1.Download python- https://www.python.org/downloads/

**HOW TO INSTALL**

git clone https://github.com/astavis/routerdos.git

**HOW TO USE** 
WARNING (Make sure that you have consent, or own the network you will be targetting since it will cause inconvenience)

1 cd routerdos

2.ls (should see: LICENSE README.md dos.py)

3.python3 dos.py. - You would need to have the router ip address. Can be found if you are connected to it.

**INFO** 
short representation- https://vimeo.com/669666271

**Personal shit**

Dug up this code while cleaning up. One of my simple projects at the time. Includes the socket module and basic Python, Usable for reference when learning.



MIT License

Copyright (c) 2022 astavis

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
