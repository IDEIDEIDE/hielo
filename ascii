#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
Created on Mon Nov 22 10:19:27 2021

@author: clockshield
"""

import tkinter as tk
from tkinter import *

root=Tk()
root.title("AScii")
root.geometry("400x400")

label_getName = Entry(root)
label_getName.place(relx = 0.5, rely = 0.5, anchor=CENTER)

label = Label(root, text = "Name in Ascii : ", fg = "black", bg  = "yellow")
def ASCII():
    get_input = label_getName.get()
    for letters in get_input:
        
        label["text"] += str(ord(letters)) + " " 
        
btn = Button(root, text = "Show ASCII", command=ASCII)
btn.place(relx = 0.5, rely = 0.4, anchor=CENTER)

label.place(relx = 0.5, rely = 0.6, anchor=CENTER)
root.mainloop()