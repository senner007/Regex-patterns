# Regex-patterns
Regular Expressions demystified 



##### 1. Find middle of mail address, but not after john@ - https://regexr.com/3qqnn
```
(?<!john@)(?<=@).+(?=\.[a-z]{2,4})
```

##### 2. Check if numbers are full house - https://regexr.com/3qqma
```
\b(\d)\1{2}(\d)\2{1}(?<!\1)\b|\b(\d)\3{1}(\d)\4{2}(?<!\3)\b
```
