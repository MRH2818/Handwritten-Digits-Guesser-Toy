# Handwritten-Digits-Guesser-Toy
This is the code for a thing I made that guesses numerical digits the user draws. It uses a neural network trained with MNIST's dataset, through my deep learning framework. All graphics are done with SFML.

To build:
g++ -I src/include -c main.cpp
g++ main.o -o main -L src/lib -l sfml-graphics -l sfml-window -l sfml-system

To use, click on the grid to start drawing. You can draw anything you like, but the neural network will only recognize numberical digits. Press _i_ on your keyboard to invert the board and _c_ to clear it.
