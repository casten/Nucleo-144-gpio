
STM32 Nucleo-144 boards (MB1137)
Top View


                                       ST-Link 
                                       USB Micro
                                        _____
     __________________________________|_____|_____________
    |                                                      | 
    |                                                      | 
    |                   ST-LINK                            | 
    |              Debugger/Programmer                     | 
    |                                                      | 
    |______________________________________________________|
    |   CN11                                   CN7    CN12 |
    |   o o                                    o o    o o  |
    |   o o                                    o o    o o  |
    |   o o    CN8                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o                             o o    o o  |
    |   o o    o o          ___________        o o    o o  |
    |   o o    o o         |           |       o o    o o  |
    |   o o    o o         |           |       o o    o o  |
    |   o o    o o         |   STM32   |       o o    o o  |
    |   o o    o o         |           |  CN10 o o    o o  |
    |   o o                |___________|       o o    o o  |
    |   o o    o o CN9                         o o    o o  |
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
    |                                   ________           |
    |                _____             |        |          |
    |_______________|     |____________|        |__________|
                    |_____|            |________|
                   User USB             Ethernet
 


```
           CN11
        (ST Morpho)            
 -----------------------------     
 GPIO | Name |   | Name | GPIO
 -----------------------------     
   42 | PC10 |o o| PC11 | 43
   44 | PC12 |o o| PD2  | 50
      | VDD  |o o| E5V  |    
      | BT0  |o o| GND  |    
   86 | PF6  |o o| NC   |    
   87 | PF7  |o o| +3V3 |    
   13 | PA13 |o o| NRST |    
   14 | PA14 |o o| 3V3  |    
   15 | PA15 |o o| +5V  |    
      | GND  |o o| GND  |    
   23 | PB7  |o o| GND  |    
   45 | PC13 |o o| VIN  |    
      | PC14 |o o|      |    
      | PC15 |o o| PA0  | 0   
      | OSC1 |o o| PA1  | 1   
  113 | PH1  |o o| PA4  | 4   
      | VBAT |o o| PB0  | 16
   34 | PC2  |o o| PC1  | 33
   35 | PC3  |o o| PC0  | 32
   52 | PD4  |o o| PD3  | 51
   53 | PD5  |o o| PG2  | 98
   54 | PD6  |o o| PG3  | 99
   55 | PD7  |o o| PE2  | 66
   67 | PE3  |o o| PE4  | 68
      | GND  |o o| PE5  | 69
   81 | PF1  |o o| PF2  | 82
   80 | PF0  |o o| PF8  | 88
   49 | PD1  |o o| PF9  | 89
   48 | PD0  |o o| PG1  | 97
   96 | PG0  |o o| GND  |    
   61 | PE1  |o o| PE6  | 70
  105 | PG9  |o o| PG15 | 111
  108 | PG12 |o o| PG10 | 106
      | PH2  |o o| PG13 | 109
   57 | PD9  |o o| PG11 | 107 
```

```
            CN8
 -----------------------------     
 GPIO | Name  |   | Name | GPIO
------------------------------     
      | NC    |o o| PC8  | 40
      | IOREF |o o| PC9  | 41
      | RESET |o o| PC10 | 42
      | +3V3  |o o| PC11 | 43
      | +5V   |o o| PC12 | 44
      | GND   |o o| PD2  | 50
      | GND   |o o| PG2  | 98
      | VIN   |o o| PG3  | 99

```
```
            CN9
           (Back)
 -----------------------------     
 GPIO | Name|   | Name | GPIO
------------------------------     
    3 | PA3  |o o| PD7 | 55
   32 | PC0  |o o| PD6 | 54
   35 | PC3  |o o| PD5 | 53
   83 | PF3  |o o| PD4 | 52 
   85 | PF5  |o o| PD3 | 51 
   90 | PF10 |o o| GND |    
      | NC   |o o| PE2 | 66 
      | NC   |o o| PE4 | 68 
   82 | PF2  |o o| PE5 | 69 
   81 | PF1  |o o| PE6 | 70 
   80 | PF0  |o o| PE3 | 67 
      | GND  |o o| PF8 | 88 
   48 | PD0  |o o| PF7 | 87 
   49 | PD1  |o o| PF9 | 89 
   96 | PG0  |o o| PG1 | 97 
```



```
            CN7
 -----------------------------     
 GPIO | Name|   | Name | GPIO
------------------------------     
   38 | PC6  |o o| PB8  | 24
   31 | PB15 |o o| PB9  | 25
   29 | PB13 |o o| AVDD |   
   28 | PB12 |o o| GND  |   
   15 | PA15 |o o| PA5  |  5
   39 | PC7  |o o| PA6  |  6
   21 | PB5  |o o| PA7  |  7
   19 | PB3  |o o| PD14 | 62
    4 | PA4  |o o| PD15 | 63
   20 | PB4  |o o| PF12 | 92

```

```
            CN10
 -----------------------------     
 GPIO | Name|   | Name | GPIO
 -----------------------------
      | AVDD |o o| PF13 | 93
      | AGND |o o| PE9  | 73
      | GND  |o o| PE11 | 75
   17 | PB1  |o o| PF14 | 94
   34 | PC2  |o o| PE13 | 77
   84 | PF4  |o o| PF15 | 95
   22 | PB6  |o o| PG14 | 110
   18 | PB2  |o o| PG9  | 105
      | GND  |o o| PE8  | 72
   61 | PD13 |o o| PE7  | 71
   60 | PD12 |o o| GND  |    
   59 | PD11 |o o| PE10 | 74
   66 | PE2  |o o| PE12 | 76
      | GND  |o o| PE14 | 78
   0  | PA0  |o o| PE15 | 79
   16 | PB0  |o o| PB10 | 26
   64 | PE0  |o o| PB11 | 27
```


```
            CN12
        (ST Morpho)
 -----------------------------     
 GPIO | Name |   | Name | GPIO
 ----------------------------- 
  41 | PC9  |o o| PC8  | 40 
  24 | PB8  |o o| PC6  | 38 
  25 | PB9  |o o| PC5  | 37 
     | AVDD |o o| V5V  |     
     | GND  |o o| PD8  | 56 
  5  | PA5  |o o| PA12 |     
  6  | PA6  |o o| PA11 |     
  7  | PA7  |o o| PB12 | 28 
  22 | PB6  |o o| PB11 | 27 
  39 | PC7  |o o| GND  |     
  10 | PA9  |o o| PB2  | 18 
     | PA0  |o o| PB1  | 17 
  26 | PB10 |o o| PB15 | 31 
  20 | PB4  |o o| PB14 | 30 
  21 | PB5  |o o| PB13 | 29 
  19 | PB3  |o o| AGND |     
  10 | PA10 |o o| PC4  | 36 
  2  | PA2  |o o| PF5  | 85 
  3  | PA3  |o o| PF4  | 84 
     | GND  |o o| PE8  | 72 
  61 | PD13 |o o| F10  | 90 
  60 | PD12 |o o| PE7  | 71 
  59 | PD11 |o o| PD14 | 62 
  74 | PE10 |o o| PD15 | 63 
  76 | PE12 |o o| PF14 | 94 
  78 | PE14 |o o| PE9  | 73 
  79 | PE15 |o o| GND  |     
  77 | PE13 |o o| PE11 | 75 
  93 | PF13 |o o| PF3  | 83 
  92 | PF12 |o o| PF15 | 95 
 110 | PG14 |o o| PF11 | 91 
     | GND  |o o| PE0  | 64 
  58 | PD10 |o o| PG8  | 104 
 103 | PG7  |o o| PG5  | 101 
 100 | PG4  |o o| PG6  | 102
```











