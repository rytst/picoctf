[Useful Link](https://georgeom.net/StegOnline/upload)



[Tool1](https://www.futureboy.us/stegano/decinput.html)


### result
```
The flag is not here maybe think in simpler terms. Data that explains data.
```

Tool2

```
steghide extract -sf ukn_reality.jpg
```

### result

```
The flag is not here maybe think in simpler terms. Data that explains data.
```

## Solution

```
exiftool ukn_reality.jpg
```

then,

```
echo cGljb0NURntNRTc0RDQ3QV9ISUREM05fNGRhYmRkY2J9Cg== | base64 --decode
```

got flag
