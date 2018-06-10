# Regex-patterns
Regular Expressions demystified 



##### 1. Find middle of mail address, but not after john@ - https://regexr.com/3qqnn
```
(?<!john@)(?<=@).+(?=\.[a-z]{2,4})
```

##### 2. Check if numbers are full house - https://regexr.com/3qqma
```
(?<!john@)(?<=@).+(?=\.[a-z]{2,4})
```
