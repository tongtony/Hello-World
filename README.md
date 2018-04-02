# Hello-World
My test drive of github
Hello every one. This is try to comit to a branch



import shutil
import os

def copy_and_overwrite(from_path, to_path):
    if os.path.exists(to_path):
        shutil.rmtree(to_path)
    shutil.copytree(from_path, to_path)

copy_and_overwrite('C:/Users/Tong/Desktop/Tax/tax2017/Ally','C:/Users/Tong/Desktop/Tax/tax2017/Ally2')


import subprocess
try:
    subprocess.check_call(['executable'])
except subprocess.CalledProcessError:
    pass # handle errors in the called executable
except OSError:
    pass # executable not found
