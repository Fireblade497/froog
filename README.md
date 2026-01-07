<h1>Welcome to my funny but simple project</h1>
<img src="https://cdn.discovermagazine.com/assets/image/50541/Glass_Frog-x.jpg" alt="no froog for you, old device user :(">

<h2>this simple python script requires well... python obviously, but also a basic knowledge of how to run python scripts via powershell/cmd.</h2>
<h3>tutorial on how to run:</h3>
<h4>1. Install python or you can use an ide</h4>
<h4>2. open powershell/cmd</h4>
<h4>3.type "cd C:/path/to/test/folder/"</h4>
<h4>4. type "python test.py" or if that doesn't work, try "py test.py"</h4>

<h3>before you ask...</h3>

<h4>yes, the "Press Enter to exit..." doesn't do anything, I did that on purpose to add to the joke</h4>


<h3>source code:</h3>
<h5>import tkinter as tk


root = tk.Tk()


root.title("froogle boopen boppen") 
root.geometry("1920x1080")            

img = tk.PhotoImage(file="froog.png")
label = tk.Label(root, image=img)
label.pack()

input("Press Enter to exit...")

root.mainloop()</h5>
