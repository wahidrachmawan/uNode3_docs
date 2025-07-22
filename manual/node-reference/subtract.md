# Subtract

![](../../images/node-reference/subtract.png)

The **`Subtract` node** performs a **subtraction operation** between two numeric values. It subtracts the second input (`B`) from the first input (`A`) and outputs the result.

### 🔧 How It Works

- Takes two numeric inputs: `A` and `B`.
- Outputs the result of `A - B`.

This node is commonly used in calculations, counters, movement systems, or anywhere you need to reduce a value.

### 📥 Inputs

| Port Name | Type               | Description                    |
|-----------|--------------------|--------------------------------|
| `A`       | `int` / `float` / `double` | The number to subtract from     |
| `B`       | `int` / `float` / `double` | The number to subtract          |

### 📤 Output

| Port Name | Type               | Description               |
|-----------|--------------------|---------------------------|
| `Result`  | Same as input type | The result of `A - B`     |