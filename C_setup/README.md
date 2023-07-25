
  # Let's start our setup 📝  
  Please Note that this tutorial aims for the easiest and most lightweight setup to code/run/debug C projects. This is not the only acceptable workflow. Feel free to use the one you are most comfortable with ✨  
  
  # Table of contents  
1. [Install VS code](#paragraph1)  
2. [Add C/C++ extension](#paragraph2)   
3. [Install GCC](#paragraph3)  

  ## Install VS code 🚀  
  <p>It is as simple as going to this link and installing the compatible version with your PC.</p>
  
  <h3>Download: 
  <a href="https://code.visualstudio.com/download"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png" alt="VS code" width="25" height="25"/> </a> 
  </h3>

<br>
  
  ## Add C/C++ extension 👽  
  After installing vs code you can install the extension as shown in the following image
  <!-- Put the image here -->
      
<br>

  ## Install GCC ⚙  
  <h3>If you are a <em>Windows</em> user, you can find the complete guide to installing gcc in the following tutorial: <a href='https://www.msys2.org/'>Here</a></h3>

  <br>

  <h3>For Linux users</h3>
  
```bash
# One command :)
$ sudo apt install gcc
```
<br>

 ## Notes:
- Don't forget to check that gcc is installed properly
  - Open terminal and type the following command to check for the installed version
  
  ```bash
  $ gcc --version
  ``` 
  - Create a simple hello world program and make sure it compiles and runs without any problems

  ```bash
  # Compile the program 
  $ gcc file.c

  # If compiled successfuly, a new executable will be created.
  # Let's try to run it
  $ ./a.exe
  ```

- If you have any problem don't hesitate to contact me 🤖