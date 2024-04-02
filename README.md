# Python-Week---3

# GUI
#import all the elements/library from the Tkinter which is mostly used in GUI
#from tkinter import* 

#Everything in Kinter is a widget, like text, frame, button widget etc
#root = Tk() #The root widget

# Creating a window with a Label widget (ArdaCiTi)
my_name = Label(root, text = "ArdaCiTi") 

my_name.pack() #Think of the pack more like when you pack your car, you find the closest available space and just pack there, so is pretty much the same
my_name.grid(row=0, column=1) #The grid uses postions to position things on the window screen

root = mainloop() #Creating the main_loop, because when you have a programme running, its constantly looping

# Create Button widget

from tkinter import*

root = Tk() #The root widget

my_button = Button(root, text= "Click Here!").pack()

root = mainloop()
