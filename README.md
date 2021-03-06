# Tchess program

Console application that can be used to play chess. The 
following players are included:

- User controlled player.
- Random move maker: only plays random legal moves.
- Greedy move maker: only cares about the result of the next move.
- Tchess engine: my chess engine, can play relatively fast and decent.

# Download

To skip building, download the complete app from the releases page.

# GUI version

As a school assignment to make an *MFC* GUI project, I expanded 
this program with a GUI. You can find it [here](https://github.com/Gtomika/tchess-gui).

# How to build

This is an *Eclipse CDT* project, can be imported, built and
run there. 

If you want to run the executable outside of Eclipse, then first 
the *res* directory must be copied to the folder of the executable.

**Boost:** This project uses Boost library, so to get a succesful 
build you
 - must have Boost headers on your computer.
 - must change the include path to your local path to Boost. 
