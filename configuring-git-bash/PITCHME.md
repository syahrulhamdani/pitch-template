@snap[text-08 h1-08]
# Configuring Git Bash
@size[0.6em](for Windows Users)
@snapend

---?color=black
@title[Motivation]

If you're on Windows, you'll need to run a few commands to run **Python** and **Anaconda**

---?color=black
@title[Step 1]

@snap[north-west]
#### Step 1
@snapend

@snap[west]
@box[bg-blue span-35](Go to your `home` directory)
@snapend

@snap[east]
@img[span-50](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5adfb95f_step1-cd/step1-cd.png)
@snapend

+++?color=black
@title[Step 2]

@snap[north-west]
#### Step 2
@snapend

@snap[west]
@box[bg-blue span-35](Get the path your to home directory)
@snapend

@snap[east]
@img[span-50](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5adfb984_step2-pwd/step2-pwd.png)
@snapend

+++?color=black
@title[Step 3]

@snap[north-west]
#### Step 3
@snapend

@snap[west]
@box[bg-blue span-35](Get the path to your Anaconda installation, by typing `ls`)
@snapend

+++?color=black
@title[Step 4]

@snap[north-west]
#### Step 4
@snapend

@snap[west text-center]
@box[bg-blue span-35](Add Python & Anaconda to PATH in `.bashrc`)
Replace `[YOUR PATH]` with your PATH, say `/c/Users/Juno/Anaconda3`.
```bash
echo 'export PATH="$PATH:[YOUR_PATH]:[YOUR_PATH]/Scripts"' >> .bashrc
```
@snapend

@snap[east]
@img[span-50](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5adfba33_step3-path/step3-path.png)
@snapend

+++?color=black
@title[Step 5]

@snap[north-west]
#### Step 5
@snapend

@snap[west text-center]
@box[bg-blue span-35](Add alias for Python in `.bashrc` file)
Using this command to tell Git Bash where to find Python executable file.
```bash
echo 'alias python="winpty python.exe"' >> .bashrc
```
@snapend

@snap[east]
@img[span-50](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5adfba70_step4-alias/step4-alias.png)
@snapend

+++?color=black
@title[Step 6]

@snap[north-west]
#### Step 6
@snapend

@snap[west text-center]
@box[bg-blue span-35](Execute commands from `.bashrc`)
Run the following line to execute the file.
```bash
source .bashrc
```
@snapend

@snap[east]
@img[span-50](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5adfbaaf_step5-source/step5-source.png)
@snapend

+++?color=black
@title[Step 7]

@snap[north-west]
#### Step 7
@snapend

@snap[west text-center]
@box[bg-blue span-35](Test Run)
Run these commands to make sure `conda`, `python`, and the Python interpreter can be accessed.
@snapend

@snap[east]
@img[span-50](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5adfbb3f_step6-testrun/step6-testrun.png)
Enter `exit()` to leave the python interpreter after the last step above.
@snapend
