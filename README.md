# notAnImage Project

The main aim of that project is to be able store image files as a simple text file. 
The idea is getting every single pixel's RGB value and writing them into a txt file line by line.
Users can specify the compression rate of their images to be saved. The compression rate is used in a way that every that rate amount of pixels' RGB values median are stored in a single line instead of each pixel's RGB values being stored. This can save a lot of space.
In my opinion, hiding private and classified images in our storage systems as a text file is safer.
Users can also open an image from their previously saved txt files. 

Libraries used:
- PIL (Pillow) -> Getting RGB values as a tuple.
- Numpy -> Saving the values.
- Tkinter -> Simple GUI. File and Folder dialogs are done by this library. 

Contributions are welcomed. 
Also, I am planning to add an encoding and decoding feature to make the txt files a lot more secure.