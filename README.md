#Perimeter of a Rectangle Program

## Problem Description

Write a complete, compilable C program that calculates the **perimeter** of a rectangle. The program should prompt the user to input a character representing the **unit of measurement**, the **length** and **width** (in meters):

- **'m'** for square meters (m²) and meters (m) for perimeter
- **'c'** for square centimeters (cm²) and centimeters (cm) for perimeter

## Formula

- **Perimeter = 2 × (Length + Width)**

If the unit is **'c'**, convert the area from square meters to square centimeters and the perimeter from meters to centimeters:

- **1 m² = 10,000 cm²**  
- **1 m = 100 cm**

## Input Requirements

1. **Unit of measurement** character ('m' or 'c').
2. **Length** of the rectangle in meters (can be a decimal value).
3. **Width** of the rectangle in meters (can be a decimal value).


## Output Requirements

- The perimeter should be displayed with **2-digit precision**.
- Include the appropriate units (m, cm for perimeter) in the output.

## Sample Input and Output

```
Display area and perimeter in (m for meters, c for centimeters): c
Enter the length (in meters): 4.5
Enter the width (in meters): 2.3
The perimeter of the rectangle is 1,360.00 cm.
```

## Notes

- Use appropriate headers, the `main` function, and correct C syntax.
- Use `printf` with formatting specifiers to control decimal precision.

