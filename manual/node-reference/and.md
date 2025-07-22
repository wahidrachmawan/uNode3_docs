# And

![](../../images/node-reference/and.png)

The **`And` node** performs a **logical AND operation** on two or more Boolean (`bool`) inputs. It returns `true` only if **all** input values are `true`; otherwise, it returns `false`.

### 🔧 How It Works

- The node evaluates all connected Boolean inputs.
- The result is `true` **only if every input is true**.
- If **any** input is `false`, the result is immediately `false`.

### 📥 Inputs

| Port Name | Type  | Description                        |
|-----------|-------|------------------------------------|
| `A`       | `bool`| First Boolean value                |
| `B`       | `bool`| Second Boolean value               |
| *(Optional)* Additional Inputs | `bool` | Additional Boolean values to evaluate |

### 📤 Output

| Port Name | Type  | Description                          |
|-----------|-------|--------------------------------------|
| `Result`  | `bool`| The result of the logical AND check  |

### 📌 Notes

- This is a **short-circuiting AND**, which means evaluation may stop early if any input is `false`.
- Commonly used when **all conditions** must be met to proceed.
- Frequently used in conditional branching, permission checks, and validation.
