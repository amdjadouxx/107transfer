# 107transfer
This is an Epitech project where a laboratory performs tests on new electronic components to be integrated into its last generation chipset.
Those components are entirely characterized by their transfer function, which determines frequency response; this function processes the input frequency and computes an output frequency.

## Tips
don't forget to use the "chmod" command to allow the executable to run on your device

## Installation
run this code to clone the current repository:
```bash
git clone https://github.com/amdjadouxx/107transfer.git
```

## Usage
A transfer function is defined by two strings (one for the numerator, one for the denominator), composed
by the polynomial coefficients split by the ‘*’ sign.

```./107transfer [num den]+```
```bash
./107transfer "1*2*3*4*5" "1"
```

# Test
I made some executable that you can use to test my 107transfer or to test your version of this project
(go to the "bonus" directory to use it)

## Usage
To use the unitest, you have to run this command on the repository:
```bash
./unittest
```

## for Epitech Students :)
To use the "debugger", you have to move the "testlauncher" directory on your repository.
then, run this command on the "testlauncher" directory:
```bash
./test_launcher
```
##Help
you can also run this command to configure the output of the "debugger":
```bash
./test_launcher -h
```

## Contributing
