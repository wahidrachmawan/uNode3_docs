# Modulo

![](../../images/node-reference/modulo.png)

The **`Modulo` node** performs a **remainder (modulus) operation** between two numeric values. It returns the **remainder** after dividing the first input by the second.

### 🔧 How It Works

- The node calculates: `A % B`
- This means it divides `A` by `B` and returns **what's left over** after the division.
- Commonly used for looping, alternating behavior, and checking if a number is divisible by another.

### ⚠️ Division by Zero

- If the second input (`B`) is `0`, the result will be **undefined** (may result in `NaN`, error, or platform-specific behavior).
- Always make sure the divisor is **non-zero**.

### 📥 Inputs

| Port Name | Type               | Description                        |
|-----------|--------------------|------------------------------------|
| `A`       | `int` / `float` / `double` | The dividend (number to divide)   |
| `B`       | `int` / `float` / `double` | The divisor (number to divide by) |

### 📤 Output

| Port Name | Type               | Description                     |
|-----------|--------------------|---------------------------------|
| `Result`  | Same as input type | The remainder after division    |

### 📌 Notes

- Works best with integer values (`int`) for classic modulus behavior.
- Floating point modulo is also supported but may return fractional remainders.