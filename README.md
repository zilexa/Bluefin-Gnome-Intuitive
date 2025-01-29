This script will finalize your OS setup and make it ready-to-go for daily use, for most users.

See https://projectbluefin.io/, the recommended OS especially for modern laptops and PCs. It explains why and also explains the main differentiator: it's based Fedora Silverblue, a so called atomic or "immutable" OS, where the OS and it's apps and tools are locked down. Just like iOS and Android. It gives you an easy to use, safe, secure desktop that end users (family members for example) can't accidentally 'break'. 
Instructions on how to install are on that page.

# Why Bluefin GNOME-Intuitive?
Bluefin comes with the most popular Linux GUI, Gnome. Gnome is inspired by MacOS but had taken minimalism to the extreme. 
I personally find Gnome a horrible out-of-the-box experience, especially for new users coming from MacOS and Windows. Not because its unfinished or incomplete but because the desktop you are initially presented with, hides too much bare basic functionality and requires mostly gestures to understand.
Gnome however can be an absolute bliss to use by selecting the right extensions and make light changes to its standard configuration.

# What will Bluefin GNOME-Intuitive do?
The script itself is small and contains comments explaining every step. It does 5 things:
1. During initial Bluefin setup, you get to choose the OS languages. But the current version of Bluefin doesn't apply your selection to the applications you install later as end user (Flatpak apps) via the the app store (simply called "Software"). The first step will interactively add the language support you need (if any besides English).
2. Install just a few basic useful apps. and replace the text editor for a less bare but still simple (and still in Gnome native programming language, GTK) text editor.
3. Configure a couple of apps, for example, to ensure LibreOffice looks familiar for most users, with icons and ribbon like Office365, saving files as docx etc.
4. To ensure your Office365 files don't look weird, it will also install all Office365 fonts and set Calibiri as default.
5. Apply Gnome configuration (and install the necessary Gnome extensions) that will allow users to immediately recognise OS elements, with less elements than default Gnome: a single all in one bar, on the left side of the screen, to ensure maximum screen space for actual work. 
   
# How to apply the script?
After installing Bluefin OS, download the script then execute it as follows:

1. Click [here](https://downgit.github.io/#/home?url=https://github.com/zilexa/Bluefin-Gnome-Intuitive/blob/main/postinstall.sh) to download postinstall.sh.
2. Open Terminal
3. go to Downloads: `cd Downloads` [ENTER]
4. `bash postinstall.sh` [ENTER]
5. Follow instructions about language support and enter your password when asked. 

Feel free to edit the script to your needs before executing.

Enjoy!
