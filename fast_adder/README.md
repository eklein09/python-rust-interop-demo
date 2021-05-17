To get it to run:

1. Compile
```
maturin develop
```

2. Rename .so file
```
mv fast_adder.cpython-37m-darwin.so string_sum.so
```

3. Start python interpreter and import:
```
python
>>> from string_sum import sum_as_string
>>> sum_as_string(1,2)
```

