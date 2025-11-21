# fansi_text

A Python module to fuzzy extract dates from a corpus of text.

## Installation

```
pip install fansi_text
```

## Usage

```python
from fansi_text import Red

print(Red("Red text"))
```

```python
from fansi_text import RGBColor

print(RGBColor("RGB Text", 200, 130, 60))
```

```python
print(f"{Bold(f"Bold {Green("green and bold ?")}")}. Then normal text ? Then {Underline(Overline("overlined"))}. Now {Italic(f"italic, add {Yellow(f" and {Bold(f"bold too!")} Then back to yellow and italic")} then just italic")} and finally back to normal.")
```