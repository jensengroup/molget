# Molget
Molget is a bash script to get 3D coordinates from chemical names using [OpenBabel](https://github.com/openbabel/openbabel) and Cactus.

## Usage
After you have cloned the repository you have to make molget executable by performing the following

    chmod +x molget

You can now use `molget` like this

    ./molget methane

to generate 3D coordinates of methane.

Multiple chemical names can be retrieved simultaneously as such:

    ./molget water thf dmso dmf

There is also a help message that will should you all the options:

    ./molget -h
