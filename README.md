# Vala
Personal programs to learn Vala and exercises using Introducing Vala Programming (in separate branch). Vala is used as the primary language for Elementary OS, which is a newer Linux distro. The OS itself and all its applications are built with the Vala language. Vala is more or less a tranformation language to ease the burdon of C level code. The valac compiler works by translating the Vala syntax into C and then uses a C compiler to finish packaging the binary (typically uses GCC). With the valac compiler actually comes 2 different syntax languages, Vala and Genie. Vala is more similar to C# while Genie is very similar to Python. There are no differences in functionality between the 2 dialects except for syntactically they are different. There are rumors that Genie also is missing features that Vala does support, have yet to come across this.

# Coming Soon...
    Chapters from Introducing Vala Programming.pdf

## Environment Setup
1. Depending on your OS, installation will vary, check https://wiki.gnome.org/Projects/Vala for more information for your OS.
2. After installing vala verify you have the valac compiler with the following command:
    - valac --version
3. If you plan to use gtk+3 you will need to use a package manager like Homebrew. (brew install gtk+3)
4. To compile a program with the gtk+3 package you will run the following command:
    - valac --pkg gtk+-3.0 main.vala
    
## Dependancies
1. ValaC
2. (Optional but is necessary for any GNOME GUIs)
