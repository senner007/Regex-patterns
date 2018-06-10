# Regex-patterns
Regular Expressions demystified 


### Find middle of mail address, but not after john@
```
(?<!john@)(?<=@).+(?=\.[a-z]{2,4})

```
https://regexr.com/3qqma