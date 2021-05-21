# Transformation With Shift

## Challenge

* 20 points 

* AUTHOR: MADSTACKS

### Description

I wonder what this really is... [enc](https://mercury.picoctf.net/static/dd6004f51362ff76f98cb8c699510f23/enc) `''.join([chr((ord(flag[i]) << 8) + ord(flag[i + 1])) for i in range(0, len(flag), 2)])`

## Attempt

With the first glance, I thought this is just a seems complex Python code, I could break it after minutes.

### Read Code

```python
''.join([chr((ord(flag[i]) << 8) + ord(flag[i + 1])) for i in range(0, len(flag), 2)])
```



