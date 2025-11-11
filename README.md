
# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
MOV A,P0
MOV R0,A
MOV B,R0
MUL AB
MOV P2,A
END

```

## OUTPUT
<img width="1917" height="1079" alt="Screenshot 2025-11-11 081340" src="https://github.com/user-attachments/assets/62cb867d-145c-4b43-a5aa-7bcad9aac88d" />

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0     
MOV R0, A     
MOV B, A      
MUL AB        
MOV R1, A    
MOV A, R1     
MOV B, R0     
MUL AB        
MOV P2, A   
END
```




## OUTPUT

<img width="1918" height="1079" alt="Screenshot 2025-11-11 092600" src="https://github.com/user-attachments/assets/3bf8ff22-5659-441b-833b-afd20f3b1b8c" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
