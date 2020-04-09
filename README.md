# 8_bit-PC


Project based on the project of [8 bit PC by Ben Eater](https://eater.net/8bit/ "8 bit by Ben Eater").  



# Version 1

Board divided into 3 parts:

## Left


|Name of unit|Description|
| ------------ | ----------|
|**Clock**|Creats clock signal for the board. Can be used also as debugger - clock signal can be made by user |
|**Memory address (MAR)**|Choose from which address PC reads. In *Prog*  mode user can specify address to which instructions in RAM module will be written |
|**RAM**| Contains instructions for specified memory address. In *Prog* mode user can specify instruction for chosen in MAR module addres   |
|**Instruction register (IR)**| Decides which step of the program will be made next. It is sent to PC module. Also sends the address to read from  |
|**Control Word (CW)**| Operates whole PC. Also shows which flag is ON during working|



## Middle
|Name of unit|Description|
| ----- |-----|
|**Display module**|Shows current information on the bus   |
|**Sorting module**|Unit transports signals from left and right board to specified unit|


## Right
|Name of unit|Description|
|-----|-----|
|**Program counter (PC)**|Makes steps for the PC. Can also change them because of *jump* function    |
|**Power**| Main power unit. Contains overvoltage and reverse polarity protection |
|**A register**|Register that can read from and write informations for the bus. Contains information on which computer is working recently |
|**Arithmetic Logic Unit (ALU)**| Mathematical unit. Operates on variables from A and B registers. Module can add and substruct them   |
|**B register**|Register that can read informations from the bus. Contains information on which computer is working recently  |
|**Output register**| Show the variable on 4 display LED. Unit has two modes: non-neagtive and negative  |


# Links

This materials were really helpful during creation:

+ [Tutorial how to build the 8 bit PC](https://www.youtube.com/watch?v=HyznrdDSSGM&list=PLowKtXNTBypGqImE405J2565dvjafglHU)
+ [Ben Eater project site](https://eater.net/8bit/ )
+ [Helpful list of 74ls series ](https://www.futurlec.com/IC74LS00Series.shtml)

