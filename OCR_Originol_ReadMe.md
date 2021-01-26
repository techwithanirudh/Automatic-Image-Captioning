## Problems and Fixes

    . = means ans or solution
    . \n means put a new line

1.   ModuleNotFoundError: No module named 'path' = from pathlib import Path * 2
2.   FileNotFoundError: [Errno 2] No such file or directory: '../model/accuracy.txt' = replace all the .. dots with a single dot . * 5
3.   FileNotFoundError: [Errno 2] No such file or directory: './model/accuracy.txt' = import os \n os.chdir('/content/SimpleHTR')
4.   Exception: No saved model found in: ../model/ = line 2


---


    Q: This is giving nonsense. 
    A: This wont work for an whole sentence this will only work for word

