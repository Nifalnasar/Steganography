## Jsteg

Jsteg is a package for hiding data inside JPEG files with a technique known as steganography. This is accomplished by copying each bit of the data into the least-significant bits (LSB) of the image. The amount of data that can be hidden depends on the file size of the jpeg; it takes about 10-14 bytes of jpeg to store each byte of the hidden data.

## Installation

```
$ sudo wget -O /usr/bin/jsteg https://github.com/lukechampine/jsteg/releases/download/v0.1.0/jsteg-linux-amd64
$ sudo chmod +x /usr/bin/jsteg
$ sudo wget -O /usr/bin/slink https://github.com/lukechampine/jsteg/releases/download/v0.2.0/slink-linux-amd64
$ chmod +x /usr/bin/slink
```
Downloaded Successfully.

## Create a text file
![image](https://github.com/Nifalnasar/Steganography/assets/141356053/205cd685-9337-42d4-b435-7305637351e2)

## Usage
Jsteg tool can be initialised by typing the following command.
`jsteg`
![image](https://github.com/Nifalnasar/Steganography/assets/141356053/fc1da53c-c0a2-480a-aeb7-3c48e74e16fc)

## Hiding data

Let the name of the file to be embedded be 'nifal.txt'.
The file to be embedded contains the following data.

![image](https://github.com/Nifalnasar/Steganography/assets/141356053/6678ea39-f457-4634-9113-d7b0110b26bd)

## Revealing data

![image](https://github.com/Nifalnasar/Steganography/assets/141356053/2b2fb4c4-f933-4f3b-8fd3-446a98e34bc7)
