# FACTORIAL-OF-A-NUMBER
# FACTORIAL OF A NUMBER USING 8051 (Keil)

## AIM
To write and execute an Assembly language program to perform the factorial of a number using 8051 Keil.

---

## APPARATUS REQUIRED
- Personal computer with Keil software

---

## ALGORITHM
1. **Start**
2. **Input**: Read the number `n`.
3. **Initialize**:
   - Set factorial to `1`.
   - Set `i` to `1`.
4. **Loop**: While `i` is less than or equal to `n`:
   - Multiply factorial by `i`.
   - Increment `i` by `1`.
5. **Output**: Store or print the value of factorial.
6. **End**

---

## FLOWCHART
<img width="506" height="525" alt="image" src="https://github.com/user-attachments/assets/f3b47187-6f0f-490c-8704-f2973cb2b276" />


---

## PROGRAM
```asm
ORG 0000H
MOV R0,#30H
MOV A,@R0
MOV R1,A
MOV A,#01H
FACT:
MOV B,R1
MUL AB
DJNZ R1,FACT
MOV 31H,A
END
```
OUTPUT

<img width="957" height="190" alt="image" src="https://github.com/user-attachments/assets/28b10bcb-eaf3-4ad4-a951-c374f684d200" />


---
MANUAL CALCULATIONS

<img width="1600" height="1301" alt="image" src="https://github.com/user-attachments/assets/d5a66ae4-4a34-4062-b454-c28aa8c3d1b4" />

---

RESULT

Thus, the factorial of a number was calculated and executed successfully using 8051 Keil.

---


