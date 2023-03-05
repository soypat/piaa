# piaa
Pico Industrial Abierta Argentina.

Inspired by the CIAA project.

# Project setup
I'd believe the project should be set automatically since I've taken care to include all libraries as "Project" libraries, not "Global". 
In any case, if that fails you may follow the steps detailed here to setup any symbol, footprint and 3D model libraries that may be needed
to work or visualize the PIAA.

1. Initialize git submodules with external symbol and footprint libraries such as the Raspberry pi pico's footprint:

    ```sh
    git submodule update --init
    ```

    Now follow the symbol installation instructions at [this link](https://github.com/ncarandini/KiCad-RP-Pico/blob/main/Install%20instructions.md)
    and use the footprint in the folder [RP-Pico Libraries](./submodules/KiCad-RP-Pico/RP-Pico Libraries).

2. Setup `piaalib` symbol and footprint libraries. They are located under [design/lib/piaalib](./design/lib/piaalib).
The steps to adding these libraries are the same as with the RP-Pico libraries.
