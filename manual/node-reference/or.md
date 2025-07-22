# Or

![](../../images/node-reference/or.png)

The **`Or` node** performs a **logical OR operation** between two or more Boolean (`bool`) inputs. It returns `true` if **at least one** of the input values is `true`; otherwise, it returns `false`.

### 🔧 How It Works

- The node checks all connected Boolean inputs.
- If **any** of them is `true`, the result is `true`.
- Only if **all inputs** are `false`, the result will be `false`.

### 📥 Inputs

| Port Name | Type  | Description                        |
|-----------|-------|------------------------------------|
| `A`       | `bool`| First Boolean value                |
| `B`       | `bool`| Second Boolean value               |
| *(Optional)* Additional Inputs | `bool` | Any other Boolean inputs to check |

### 📤 Output

| Port Name | Type  | Description                       |
|-----------|-------|-----------------------------------|
| `Result`  | `bool`| The result of the logical OR check |

### 📌 Notes

- This is a **short-circuiting OR**, which means if the first `true` is found, evaluation may stop.
- The `Or` node is useful for conditions where **any** of multiple conditions being `true` is enough to proceed.
- Often used in flow control, state checks, or validating multiple flags.