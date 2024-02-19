# Ghost-Mouse-Keyboard
A ghost mouse and keyboard application using Python on Windows.

## How To
1. Run the requirements.py Python script to install the required modules via pip. The required modules are pynput (https://pypi.org/project/pynput/) and pyautogui (https://pypi.org/project/PyAutoGUI/).
2. Run the record.py Python script to record mouse inputs and keyboard inputs. When you've completed both hold the right mouse button for 2 seconds and then click ESC on the keyboard. This will create a JSON file.
3. Run the convert.py Python script that utilizes the created JSON file from step 2 to then create a play.py Python script.
4. Running the play.py Python script will re-run all the recorded keystrokes and mouse movements done in step 2.
