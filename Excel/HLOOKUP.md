# HLOOKUP Formula

The HLOOKUP function works much in the same way a VLOOKUP does with the exception that formula is capturing data in a from horizontal format.

1. Select the value (cell) you want to lookup AKA lookup value
2. Select the range of where the lookup value is — the lookup value SHOULD ALWAYS be the first column.
3. This would be the row number of your range for your return value.
4. Select FALSE for an exact match or TRUE for approximate match.

`=HLOOKUP(J9,I4:T6,2,FALSE)`

## Examples

<img width="1192" height="166" alt="image" src="https://github.com/user-attachments/assets/53d95e77-7584-419b-89a5-31291335aef5" />

# Related Posts

- [VLOOKUP Formula](https://github.com/ericrascon/Today-I-Learned/blob/main/Excel/VLOOKUP.md)
