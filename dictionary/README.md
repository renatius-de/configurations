# create dictionary

```
aspell --lang de dump master | aspell --lang de expand | tr ' ' '\n' > de.dic
```

```
aspell --lang en dump master | aspell --lang en expand | tr ' ' '\n' > en.dic
```
