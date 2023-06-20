# CAPTCHA (Verification System)

This code script is an example of a CAPTCHA (Completely Automated Public Turing test to tell Computers and Humans Apart) verification system implemented using the Tkinter library in Python. The system generates a random numeric CAPTCHA image and prompts the user to enter the displayed value for verification.

## Dependencies

The following dependencies are required to run the script:
- Tkinter: GUI library for Python (usually comes pre-installed with Python)
- `captcha` library: Python library for generating CAPTCHA images

## How to Run

1. Save the script in a Python file with a `.py` extension (e.g., `captcha_verification.py`).
2. Make sure to have the TrueType fonts `ChelseaMarket-Regular.ttf` and `DejaVuSans-Oblique.ttf` in the same directory as the script.
3. Run the script using a Python interpreter:

```bash
python captcha_verification.py
```

## How It Works

1. The script uses the `ImageCaptcha` class from the `captcha` library to generate a random numeric CAPTCHA image.
2. The randomly generated numeric value is stored in the `random` variable.
3. The CAPTCHA image is saved as `out.png` using the `write` method of the `ImageCaptcha` object.
4. The Tkinter library is used to create a GUI window.
5. The CAPTCHA image is loaded from `out.png` and displayed in a `Label` widget.
6. The user can enter their guess in a `Text` widget.
7. When the user clicks the "Submit" button, the entered value is compared with the randomly generated value (`random`) to verify the CAPTCHA.
8. If the entered value matches the CAPTCHA, a success message is displayed using a message box. Otherwise, an alert message is shown.
9. The "Refresh" button generates a new random CAPTCHA image and updates the displayed image.

## Additional Notes

- The `refresh` function generates a new random CAPTCHA image and updates the displayed image.
- The `verify` function compares the entered value with the randomly generated value (`random`) for CAPTCHA verification.
- The CAPTCHA image is displayed using a `Label` widget, and the entered value is obtained using a `Text` widget.
- The `messagebox` module from Tkinter is used to display success and alert messages in pop-up message boxes.

Please make sure to have the necessary font files (`ChelseaMarket-Regular.ttf` and `DejaVuSans-Oblique.ttf`) in the same directory as the script, as the font paths are specified in the code.

Feel free to modify and enhance this code script as per your requirements.
```css
Make sure to save this content in a `readme.md` file in Markdown format.

