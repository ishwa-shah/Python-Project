It involves creating a User Interface using Tkinter module complete with Login/Register availabilities. The functionality performed involves identifying text from an image (*.jpg, *.png) and providing the user with the option to choose the text (as clickable text) to get the meaning and pronunciation. The major details of the project are mentioned in the video (via audio.)

*****Modules involved*****:
tkinter: for GUI
pytesseract: for converting image to text
cv2: for reading the image for pytesseract
PyDictionary: for getting meanings of the selected word
PIL: pillow for reading images for Labels (tkinter)
gtts: for text-to-speech conversion
email_validator: to validate email input from user
string: for certain string based functions
re: for access to re.split()
os: for access to list of files and directories and for audio play

*****Notes to be taken care of*****:
-> The indentation of the Labels, Buttons, Windows and Menu may vary from device to device and application to application
-> In case of any error, reload/refresh the kernel before running the code, else a "pyimage" error may be observed
-> Ensure that the image type meets the requirements based on where it is to be used.
-> Pytesseract usually has a high accuracy. However, it is not full-proof. There maybe instances where it is unable to identify the text in the image or wrongly identifies it. It's better to choose an image with high clarity.
-> As of now, the language is restricted to English. However, it can be expanded for multiple languages.
-> As of now, the email input is for storage purposes only. However, it can be used for 'Forgot Password' feature among others.
-> As of now, user profile details have not been provided beyond the file storage. The username is mentioned as the title of the Menu window. Hence, the user can be recognised from the Menu window.
-> Pytesseract takes a while to interpret the text. In case it doesn't respond, try again a few times.
-> Do not directly close the Login, Register or Menu windows. Use the Quit/Back to Main Screen buttons. If closed by mistake, restart the kernal. (for Jupyter Notebook) 

*****Certain parameter(s) that may or may not be mentioned in the video*****:
-> For register and login windows, a few requirements are to be met. Unless the requirements are met, no further procedure observed.
The requirements include: the 'password' and 'confirm password' options should have the same value for password, the first letter of the username should be an uppercase alphabet, the minimum required length of the username is 4 characters, ensure that the username is not already in use. In case of login window, there will be separate messages for invalid username and invalid password. Priority given to username.
-> Both pack_forget() and destroy() are used for similar tasks.
-> There are single-line comments preceding functions/methods that brief you about the purpose of the function
-> All the global varibles declared right after the import module section are used for checking various conditions in order to decide whether to undergo certain actions or not. 
-> The Register and Login windows both proceed to the Menu Window for that particular user.
-> The outer try - except block is present just in case a minor possible exception has been overlooked. 
