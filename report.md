# Diff Coverage
## Diff: origin/main...HEAD, staged and unstaged changes

- api/calculator/calculator&#46;py (20.0%): Missing lines 17-21,24-26
- api/smiles/smiles&#46;py (50.0%): Missing lines 6,12

## Summary

- **Total**: 14 lines
- **Missing**: 10 lines
- **Coverage**: 28%



## api/calculator/calculator&#46;py

Lines 13-27

```python
  13             return "Cannot divide by 0"
  14         return x * 1.0 / y
  15 
  16     def square(x):
! 17         if x == 1:
! 18             return x
! 19         elif x == 2:
! 20             return x + 1
! 21         return x * x
  22 
  23     def log(x):
! 24         if x == 1:
! 25             return x + 1
! 26         return x
```


---



## api/smiles/smiles&#46;py

Lines 2-10

```python
   2     def smile(self):
   3         return ":)"
   4 
   5     def grin(self):
!  6         return ":D"
   7 
   8     def frown(self):
   9         return ":("
```


---


Lines 8-13

```python
   8     def frown(self):
   9         return ":("
  10 
  11     def wink(self):
! 12         return ";)"
```


---


