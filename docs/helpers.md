# Helper Functions

This page documents some common helper functions used throughout the project.

## `format_date(date_string)`

Formats a date string into `YYYY-MM-DD` format.

**Parameters**

- `date_string` (`str`): The date as a string in any common format.

**Returns**

- `str`: Formatted date string.

**Example**

```python
formatted = format_date("03/09/2025")
print(formatted)  # Output: "2025-09-03"
```

---

## `calculate_total(items)`

Calculates the total price of a list of items.

**Parameters**

- `items` (`list`): List of items, each with a `price` field.

**Returns**

- `float`: The total price.

**Example**

```python
items = [{"price": 10.5}, {"price": 20.0}]
total = calculate_total(items)
print(total)  # Output: 30.5
```