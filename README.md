Steganography system requires any type of image file and the information or message
that is to be hidden. It has two modules encrypt and decrypt.

Microsoft .Net framework / Visual Studio prepares a huge amount of tool and options
for programmers that they simplify programming. One of .Net tools for pictures and
images is auto-converting most types of pictures to BMP format. We can use this tool
in this software called “Steganography” that is written in C# , .Net language and you
can use this software to hide your information in any type of pictures without any
converting its format to BMP (software converts inside it).
The algorithm used for Encryption and Decryption in this application provides using
several layers lieu of using only LSB layer of image. Writing data starts from last
layer (8st or LSB layer); because significant of this layer is least and every upper
layer has doubled significant from its down layer. So every step we go to upper layer
image quality decreases and image retouching transpires.

The encrypt module is used to hide information into the image; no one can see that
information or file. This module requires any type of image and message and gives
the only one image file in destination.
The decrypt module is used to get the hidden information in an image file. It take the
image file as an output, and give two file at destination folder, one is the same image
file and another is the message file that is hidden it that.
