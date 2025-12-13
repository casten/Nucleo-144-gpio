
# STM32 Nucleo-144 boards (MB1137) Back View

```
                ST-Link 
                USB Micro
                 _____
     ___________|_____|____________________________________
    |                                                      | 
    |                                                      | 
    |                   ST-LINK                            | 
    |              Debugger/Programmer                     | 
    |                 Bottom View                          | 
    |______________________________________________________|
    |   CN12   CN7                                    CN11 |
    |   o o    o o                                    o o  |
    |   o o    o o                                    o o  |
    |   o o    o o                             CN8    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o          ___________        o o    o o  |
    |   o o    o o         |           |       o o    o o  |
    |   o o    o o         |           |       o o    o o  |
    |   o o    o o         |   STM32   |       o o    o o  |
    |   o o    o o CN10    |           |       o o    o o  |
    |   o o    o o         |___________|              o o  |
    |   o o    o o                        CN9  o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o                                           o o  |
    |   o o                                           o o  |
    |   o o                                           o o  |
    |   o o                                           o o  |
    |   o o                                           o o  |
    |   o o                                           o o  |
    |   o o                                           o o  |
    |   o o                                           o o  |
    |                                                      |
    |             ________                                 |
    |            |        |           _____                |
    |____________|        |__________|     |_______________|
                 |________|          |_____|
                  Ethernet           User USB    
```
 



```
            CN11
        (ST Morpho - Back)
 -----------------------------     
 GPIO | Name |   | Name | GPIO
      -------------------  
   40 | PC8  |o o| PC9  | 41
   38 | PC6  |o o| PB8  | 24
   37 | PC5  |o o| PB9  | 25
      | V5V  |o o| AVDD |   
   56 | PD8  |o o| GND  |  
      | PA12 |o o| PA5  | 5
      | PA11 |o o| PA6  | 6
   28 | PB12 |o o| PA7  | 7
   27 | PB11 |o o| PB6  | 22
      | GND  |o o| PC7  | 39
   18 | PB2  |o o| PA9  | 10
   17 | PB1  |o o| PA0  | ?
   31 | PB15 |o o| PB10 | 26
   30 | PB14 |o o| PB4  | 20
   29 | PB13 |o o| PB5  | 21
      | AGND |o o| PB3  | 19
   36 | PC4  |o o| PA10 | 10
   85 | PF5  |o o| PA2  | 2
   84 | PF4  |o o| PA3  | 3
   72 | PE8  |o o| GND  |  
   90 | F10  |o o| PD13 | 61
   71 | PE7  |o o| PD12 | 60
   62 | PD14 |o o| PD11 | 59
   63 | PD15 |o o| PE10 | 74
   94 | PF14 |o o| PE12 | 76
   73 | PE9  |o o| PE14 | 78
      | GND  |o o| PE15 | 79
   75 | PE11 |o o| PE13 | 77
   83 | PF3  |o o| PF13 | 93
   95 | PF15 |o o| PF12 | 92
   91 | PF11 |o o| PG14 | 110
   64 | PE0  |o o| GND  |  
  104 | PG8  |o o| PD10 | 58
  101 | PG5  |o o| PG7  | 103
  102 | PG6  |o o| PG4  | 100
```

```
            CN7
           (Back)
 -----------------------------     
 GPIO | Name|   | Name | GPIO
      -------------------  
   24 | PB8  |o o| PC6  | 38
   25 | PB9  |o o| PB15 | 31
      | AVDD |o o| PB13 | 29
      | GND  |o o| PB12 | 28
    5 | PA5  |o o| PA15 | 15
    6 | PA6  |o o| PC7  | 39
    7 | PA7  |o o| PB5  | 21
   62 | PD14 |o o| PB3  | 19
   63 | PD15 |o o| PA4  | 4
   92 | PF12 |o o| PB4  | 20
```

```
            CN10
           (Back)
 -----------------------------     
 GPIO | Name|   | Name | GPIO
      -------------------  
    93 | PF13 |o o| AVDD | 
    73 | PE9  |o o| AGND | 
    75 | PE11 |o o| GND  | 
    94 | PF14 |o o| PB1  | 17
    77 | PE13 |o o| PC2  | 34
    95 | PF15 |o o| PF4  | 84
   110 | PG14 |o o| PB6  | 22
   105 | PG9  |o o| PB2  | 18
    72 | PE8  |o o| GND  | 
    71 | PE7  |o o| PD13 | 61
       | GND  |o o| PD12 | 60
    74 | PE10 |o o| PD11 | 59
    76 | PE12 |o o| PE2  | 66
    78 | PE14 |o o| GND  | 
    79 | PE15 |o o| PA0  | 0
    26 | PB10 |o o| PB0  | 16
    27 | PB11 |o o| PE0  | 64
```



```
            CN8
           (Back)
 -----------------------------     
 GPIO | Name |   | Name  | GPIO
      -------------------  
   40 | PC8  |o o| NC    | 
   41 | PC9  |o o| IOREF | 
   42 | PC10 |o o| RESET | 
   43 | PC11 |o o| +3V3  | 
   44 | PC12 |o o| +5V   | 
   50 | PD2  |o o| GND   | 
   98 | PG2  |o o| GND   | 
   99 | PG3  |o o| VIN   | 
```

```
            CN9
           (Back)
 -----------------------------     
 GPIO | Name|   | Name | GPIO
      -------------------  
   55 | PD7 |o o| PA3  | 3
   54 | PD6 |o o| PC0  | 32
   53 | PD5 |o o| PC3  | 35
   52 | PD4 |o o| PF3  | 83
   51 | PD3 |o o| PF5  | 85
      | GND |o o| PF10 | 90
   66 | PE2 |o o| NC   | 
   68 | PE4 |o o| NC   | 
   69 | PE5 |o o| PF2  | 82
   70 | PE6 |o o| PF1  | 81
   67 | PE3 |o o| PF0  | 80
   88 | PF8 |o o| GND  | 
   87 | PF7 |o o| PD0  | 48
   89 | PF9 |o o| PD1  | 49
   97 | PG1 |o o| PG0  | 96
```




```
            CN11
     (ST Morpho - Back)
 -----------------------------     
 GPIO | Name |   | Name | GPIO
      -------------------  
   43 | PC11 |o o| PC10 | 42
   50 | PD2  |o o| PC12 | 44
      | E5V  |o o| VDD  | 
      | GND  |o o| BT0  | 
      | NC   |o o| PF6  | 86
      | +3V3 |o o| PF7  | 87
      | NRST |o o| PA13 | 13
      | 3V3  |o o| PA14 | 14
      | +5V  |o o| PA15 | 15
      | GND  |o o| GND  | 
      | GND  |o o| PB7  | 23
      | VIN  |o o| PC13 | 45
      |      |o o| PC14 | 
    0 | PA0  |o o| PC15 | 
    1 | PA1  |o o| OSC1 | 
    4 | PA4  |o o| PH1  | 113
   16 | PB0  |o o| VBAT | 
   33 | PC1  |o o| PC2  | 34
   32 | PC0  |o o| PC3  | 35
   51 | PD3  |o o| PD4  | 52
   98 | PG2  |o o| PD5  | 53
   99 | PG3  |o o| PD6  | 54
   66 | PE2  |o o| PD7  | 55
   68 | PE4  |o o| PE3  | 67
   69 | PE5  |o o| GND  | 
   82 | PF2  |o o| PF1  | 81
   88 | PF8  |o o| PF0  | 80
   89 | PF9  |o o| PD1  | 49
   97 | PG1  |o o| PD0  | 48
      | GND  |o o| PG0  | 96
   70 | PE6  |o o| PE1  | 61
  111 | PG15 |o o| PG9  | 105
  106 | PG10 |o o| PG12 | 108
  109 | PG13 |o o| PH2  | 
  107 | PG11 |o o| PD9  | 57
```




