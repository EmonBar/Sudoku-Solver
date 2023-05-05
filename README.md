# Sudoku Solver

This project is an OCR (Optical Character Recognition) software that solves a sudoku grid.

## Download

To download our project, run the following command:

```
wget https://github.com/EmonBar/Sudoku-Solver/archive/refs/heads/main.zip -O "SudokuSolver.zip" &&
unzip ./"SudokuSolver.zip" &&
rm ./"SudokuSolver.zip"
```

## Usage

To run the project:

1. Go to: `sourcecode/SudokuFinal/Sudokun`

2. Enter the command:

```
chmod u+x compile.sh
```

3. Then enter:

```
./compile <number of the image you want to use> #Your image must be named with this form "SudokuGrid<numberOfYourImage>"
```

4. The GTK interface should open.

5. Click on the Load button and select the image you wish to use (the one that matches the number you entered earlier).

6. If the chosen image is not oriented properly, please add the rotation angle in the field to the right of the Rotate button, then press the same button.

7. Click successively on the Proceed to Extraction, Create Digit Values and Create NN Values buttons.

8. Exit the interface by pressing the Quit button.

9. The result is available in: `sourcecode/SudokuFinal/data/images`

## Clean Project

To clean the project, run the following command:

```
make clean
```

## Credits

- [BARBERIS Emon](https://github.com/EmonBar)
- [EKICI Enes](https://github.com/TRKirua)
- [ABOU-AL-TOUT Samy](https://github.com/Locovamos)
- [DIALLO Mateo](https://github.com/Matflashhdw)
