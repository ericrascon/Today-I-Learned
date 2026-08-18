# VLOOKUP Formula  

The VLOOKUP function tends to work in a 4 parter.

1. Select the value (cell) you want to lookup AKA lookup value
2. Select the range of where the lookup value is — the lookup value **SHOULD ALWAYS** be the first column.
3. This would be the columnn number of your range for your return value.
4. Select FALSE for an exact match or TRUE for approximate match.

The VOOLUP will always only look at numbers from the right. The return value of the VLOOKUP will always be the first matching it finds as well. 

`=VLOOKUP($F5,Table2,2,FALSE)` or `=VLOOKUP(F2,A2:B11,2,FALSE)` (range)

# Examples

<img width="475" height="297" alt="image" src="https://github.com/user-attachments/assets/c770b078-48c5-4707-9bb4-c7942d5e433d" />

# Best Practice

Create a table before starting a VLOOKUP function — will help with avoiding formula errors.
