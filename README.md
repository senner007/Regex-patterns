# Regex-patterns
Regular Expressions demystified 



##### 1. Find middle of mail address, but not after john@ - https://regexr.com/3qqma
```
(?<!john@)(?<=@).+(?=\.[a-z]{2,4})
```
