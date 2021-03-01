# pybase100
Encode and decode your text using emoji

This repository contais a Python 3 package for Base100 encoding alhorithm. It's simple: instead of alphanumeric strings you operate with emoji. For example:

![pybase100 in Telegram bot](https://github.com/MasterGroosha/pybase100/raw/master/images/pybase100_telegram.png?raw=true)

**Installation**: `pip install pybase100`

**Usage**:
```
import pybase100 as pb

string = "Hello, world!"
encoded = pb.encode(string) # Encode the string
print(encoded)
decoded = pb.decode(encoded) # Decode the encoded string
print(decoded)
```

## Credits
A huge thanks to Adam Niederer for his original Base100 version written in Rust: https://github.com/AdamNiederer/base100.  
And also to Viktor (https://github.com/stek29) for a great help while making pybase100 (well, most of work with pybase100 is done by him). Btw, he's [collecting base100 implementations](https://github.com/stek29/base100) as well.
