from tkinter import *
root = Tk()
root.geometry("600x453")
root.title("code with harry")

#  for icon change in title of gui window
root.wm_iconbitmap("1.ico")

# for change in Gui use cinfigure
root.configure(background="grey")

# for get Height and width of Gui window
width = root.winfo_screenwidth()
height = root.winfo_screenheight()
print(f"{width}x{height}")

Button(text="close",command=root.destroy).pack()

root.mainloop()
