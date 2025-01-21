This script will finalize your OS setup and make it ready-to-go for daily use, for most users.

See https://projectbluefin.io/, the recommended OS especially for modern laptops and PCs. Instructions on how to install are on that page.

# Why Bluefin GNOME-Intuitive?
I personally find Gnome a horrible out-of-the-box experience, especially for new users coming from MacOS and Windows. Not because its unfinished or incomplete but because the desktop you see hides too much bare basic functionality and requires mostly gestures to understand.

# What will Bluefin GNOME-Intuitive do?
The script itself is small and contains comments explaining every step. It does 4 things.
1. During initial Bluefin setup, you get to choose the OS languages. However this is not applied to the applications you install later as end user (Flatpak apps) via the the app store (called simply "Software"). The first step will interactively add the language support you need (if any besides English).
2. Install just a few basic useful apps. and replace the text editor for a less bare but still simple (and still in Gnome native programming language, GTK) text editor.
3. Configure a couple of apps, for example, to ensure LibreOffice looks familiar for most users, with icons and ribbon like Office365, saving files as docx etc. To ensure your Office365 files don't look weird, it will also install all Office365 fonts and set Calibiri as default.
4. Apply Gnome configuration (and install the necessary Gnome extensions) that will allow users to immediately recognise OS elements, with less elements than default Gnome: a single all in one bar, on the left side of the screen, to ensure maximum screen space for actual work. 
   
# How to apply the script?
After installing Bluefin OS, download the script then execute it as follows:

1. Open Terminal
2. go to Downloads: `cd Downloads` [ENTER]
3. `bash postinstall.sh` [ENTER]
4. Follow instructions about language support and enter your password when asked. 

Feel free to edit the script to your needs before executing.

Enjoy!
