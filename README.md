# Peripheral SOM Daughterboard
Template with aligned M3 holes and board to board connector placement.

# How to Use
- Repositories -> New repository -> Repository template
- Naming convention: (System Name)-Peripheral-SOM-Daughterboard-(Function)

# Specifications
- SPI1 is main SPI
- I2C1 is main I2C
- SPI2 can be swapped out for 4xGPIO
- I2C2 can be swapped out for 2xGPIO
- 3.3V Power
- 3.3V Analog
- 5V Power
- Associated Grounds

# Design Considerations
- Can be larger than Peripheral SOM
- Front layer (top) will be sandwiched with Peripheral SOM
  - **Throughole and other bottom mounted Peripheral SOM components may interfere with front layer (top)**
  - Outline provided on drawing layer for convenience

# Images
![image](https://github.com/lhr-solar/Peripheral-SOM-Daughterboard-Template/assets/89665539/a94c2161-674a-4dec-a41e-15f87d97375c)
![image](https://github.com/lhr-solar/Peripheral-SOM-Daughterboard-Template/assets/89665539/f9905dd1-f083-41d3-b77d-e2b347df0191)
