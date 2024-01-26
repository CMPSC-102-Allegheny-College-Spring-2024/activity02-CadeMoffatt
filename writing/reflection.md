# Data Type
: Please remove the markers and notes from this file
so that the final document is written in a professional fashion
suitable for publication. If you have questions about how to
structure, format, and write this document, please ask for a
preliminary assessment of your work in advance of the deadline.

## Name 
Cade Moffatt

## Program Output

### What is the output from running the following commands?


```
    The value of a feasible number is 115792089237316195423570985008687907853269984665640564039457584007913129639936
    The value of another feasible number is     179769313486231590772930519078902473361797697894230657273430081157732675805500963132708477322407536021120113879871393357658789768  814416622492847430639474124377767893424865485276302219601246094119453082952085005768838150682342462881473913110540827237163350510  684586298239947245938479716304835356329624224137216
```
- `python demonstrate-variable-limitations.py`


```
    1.0 is not the same as 1.1
    1.0 is the same as 1.0
    .33333 + .33333 + .33333 is not equal to 1
    .33333333333 + .33333333333 + .3333333333 is not equal to 1
    The value of 1/3 is 0.3333333333333333
    0.3333333333333333 + 0.3333333333333333 + 0.3333333333333333 is equal to 1
    1/3 + 1/3 + 1/3 is equal 1
```
- `python compare-variables.py`

## Program Questions

### Why is it not feasible to perform the computation `2**2**100`?

: It is not feasible to perform the computation due to the fact that it is such a massive computation. '2**2**100' is way bigger compared to '2**2**10'

### What is the value of `1/3` according to the Python language? Why?

: The value of 1/3 according to the python language is .3333333. This is due to the fact that 1/3 is .3 repeating. So the program recognizes 1/3 as .3333333 which is very close to the actual representation but ver so slightly wrong as it is a repeating number.

### Why is the value of `.33333 + .33333 + .33333 == 1` equal to `False`?

: This is False because it is actually equal to .999999. This is why it is an issue that python recognizes 1/3 as .333333 rather than as a repeating number. It will not equal 1 unless the value is seen as repeating.

(Did you remember to add your name?!)