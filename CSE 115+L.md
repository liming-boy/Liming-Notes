#### Shortcut of (r-1)

Based on the image provided, the text explains a **shortcut method** for finding the **$(r-1)$'s complement** of a number in any base (radix) $r$.

Here is a clear breakdown of how this shortcut works, using the examples shown in the image.

##### The Core Rule

To find the $(r-1)$'s complement of any number, you simply **subtract each individual digit of the number from the maximum possible digit value in that base** (which is always $r - 1$).

##### Step-by-Step Breakdown of the Examples

##### 1. Base 8 (Octal) $\rightarrow$ 7's Complement

For base $r = 8$, the $(r-1)$ value is **7**. To find the 7's complement of $(620143)_8$, subtract every digit from 7:

|**Max Digit**|**Given Digit**|**Result**|
|---|---|---|
|7|6|**1**|
|7|2|**5**|
|7|0|**7**|
|7|1|**6**|
|7|4|**3**|
|7|3|**4**|

- **Ans:** `157634`
    

##### 2. Base 16 (Hexadecimal) $\rightarrow$ 15's Complement

For base $r = 16$, the $(r-1)$ value is **15** (represented as **F** in hex). To find the 15's complement of $(A4D7E)_{16}$, subtract each value from 15.

_(Remember: A=10, B=11, C=12, D=13, E=14, F=15)_

- $15 - A (10) =$ **5**
    
- $15 - 4 =$ **B** (11)
    
- $15 - D (13) =$ **2**
    
- $15 - 7 =$ **8**
    
- $15 - E (14) =$ **1**
    
- **Ans:** `5B281`
    

##### 3. Base 2 (Binary) $\rightarrow$ 1's Complement

For base $r = 2$, the $(r-1)$ value is **1**.

As the note highlights, binary is the easiest of all. Subtracting a binary digit from 1 effectively just flips it ($1-1=0$ and $1-0=1$). To find the 1's complement of $(110100101)_2$, you simply **swap all 1s to 0s and all 0s to 1s**:

- Given: `1 1 0 1 0 0 1 0 1`
    
- Fllipped: `0 0 1 0 1 1 0 1 0`
    
- **Ans:** `001011010`

### 2. The Core Rule (Right to Left)

This new slide builds directly on the last one, but moves from finding the $(r-1)$'s complement to finding the **$r$'s complement** (the radix complement, like 10's complement in decimal or 2's complement in binary) using a **one-step shortcut**.

Instead of finding the $(r-1)$'s complement and then adding 1, this trick lets you write down the answer instantly by working from **right to left**.

#### The Core Rule (Right-to-Left)

When looking at the number from right to left:

1. **Leave any trailing (initial) zeros exactly as they are.**
    
2. **Subtract the first non-zero digit you hit from the base $r$.**
    
3. **Subtract all the remaining digits to the left from $(r-1)$.**
    

#### Breakdown of the Main Example: $(529400)_{10}$

We want the **10's complement** (so $r = 10$ and $r-1 = 9$). Look at the number from right to left: `0` $\leftarrow$ `0` $\leftarrow$ `4` $\leftarrow$ `9` $\leftarrow$ `2` $\leftarrow$ `5`.

- **Trailing Zeros:** The two rightmost digits are `00`. Leave them alone. $\rightarrow$ **`00`**
    
- **First Non-Zero Digit:** The first non-zero digit we hit is `4`. Subtract it from **$r$ (10)**: $10 - 4 =$ **`6`**
    
- **Remaining Digits:** For all digits to the left (`529`), subtract them from **$r-1$ (9)**:
    
    - $9 - 9 =$ **`0`**
        
    - $9 - 2 =$ **`7`**
        
    - $9 - 5 =$ **`4`**
        

Put it all together from left to right: **`470600`**

#### Step-by-Step Breakdown of the Practice Examples

### 1. $(8210)_{10} \rightarrow$ 10's Complement ($r=10, r-1=9$)

- **Trailing Zeros:** Keep the `0` $\rightarrow$ **`0`**
    
- **First Non-Zero:** The `1`. Subtract from 10: $10 - 1 =$ **`9`**
    
- **Remaining Digits (`82`):** Subtract from 9:
    
    - $9 - 2 =$ **`7`**
        
    - $9 - 8 =$ **`1`**
        
- **Ans:** `1790`
    

#### 2. $(61352)_{10} \rightarrow$ 10's Complement ($r=10, r-1=9$)

- **Trailing Zeros:** None!
    
- **First Non-Zero:** The rightmost digit is `2`. Subtract from 10: $10 - 2 =$ **`8`**
    
- **Remaining Digits (`6135`):** Subtract from 9:
    
    - $9 - 5 =$ **`4`**
        
    - $9 - 3 =$ **`6`**
        
    - $9 - 1 =$ **`8`**
        
    - $9 - 6 =$ **`3`**
        
- **Ans:** `38648`
    

#### 3. $(6201430)_8 \rightarrow$ 8's Complement ($r=8, r-1=7$)

- **Trailing Zeros:** Keep the `0` $\rightarrow$ **`0`**
    
- **First Non-Zero:** The `3`. Subtract from 8: $8 - 3 =$ **`5`**
    
- **Remaining Digits (`62014`):** Subtract from 7:
    
    - $7 - 4 =$ **`3`**
        
    - $7 - 1 =$ **`6`**
        
    - $7 - 0 =$ **`7`**
        
    - $7 - 2 =$ **`5`**
        
    - $7 - 6 =$ **`1`**
        
- **Ans:** `1576350`
    

#### 4. $(A4D7E0)_{16} \rightarrow$ 16's Complement ($r=16, r-1=15$ or `F`)

_(Quick reminder: E=14, 7=7, D=13, 4=4, A=10)_

- **Trailing Zeros:** Keep the `0` $\rightarrow$ **`0`**
    
- **First Non-Zero:** The `E` (14). Subtract from 16: $16 - 14 =$ **`2`**
    
- **Remaining Digits (`A4D7`):** Subtract from 15:
    
    - $15 - 7 =$ **`8`**
        
    - $15 - D (13) =$ **`2`**
        
    - $15 - 4 =$ **`B`** (11)
        
    - $15 - A (10) =$ **`5`**
        
- **Ans:** `5B2820`

![[Pasted image 20260611034103.png]]