**VirtualHandKeys** is a hand-gesture-based virtual keyboard that uses computer vision to track hand movements and detect gestures to simulate keyboard inputs.
This project leverages OpenCV, cvzone, and HandTrackingModule to detect hand gestures and translate them into keyboard actions.

Features-

  1.Hand Detection: Utilizes a webcam to track hand movements.
  
  2.Alphabet, Number and Symbol Input: Supports typing alphabets (A-Z), numbers (0-9) and symbols (#,<,|,etc.) with a virtual keyboard interface.
  
  3.Shift & Caps Lock: Toggle between uppercase and lowercase letters using the Shift and Caps Lock keys.
  
  4.Symbols Toggle: Switch between the alphabet and symbol layout with a dedicated "Symbols" button.
  
  5.Space, Enter, and Backspace: Includes standard keys like Space, Enter, and Backspace for text input and editing.
  
  6.Arrow Keys: Navigate through the text using the Left, Right, Up, and Down arrow keys.
  
  7.TAB Key: Insert tabs for indentation.
  
  8.Dynamic Feedback: Displays the typed text in real-time on the screen.
  
How It Works-

The program uses a webcam feed to detect hand gestures and track the position of the fingertips. When the tip of the index finger moves, it hovers over the virtual keys, a click is simulated by bringing the fingers together and the keypress is registered. The user can interact with various keys, including letters, numbers, symbols, and special function keys (Shift, Enter, Backspace, etc.).

Installation-

Clone this repository:

git clone https://github.com/sahithi-sss/VirtualHandKeys.git

Install the required dependencies

Run the program:

python main.py

Dependencies-

Python 3.x

OpenCV

cvzone

HandTrackingModule

pynput

Install all dependencies with-

pip install opencv-python cvzone pynput

Future Enhancements-

Improve gesture precision for a smoother typing experience.

Explore multi-language support.

Enhance usability for accessibility and custom keyboard setups.

Contributing

Contributions are welcome! Feel free to fork this project and submit pull requests to enhance functionality or fix bugs.



Contributing
Contributions are welcome! Feel free to fork this project and submit pull requests to enhance functionality or fix bugs.

License
This project is licensed under the MIT License.
