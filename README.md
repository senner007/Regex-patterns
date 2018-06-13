# Regex-patterns
Regular Expressions demystified 



##### * Find middle of mail address, but not after john@ - https://regexr.com/3qqnn
```
(?<!john@)(?<=@).+(?=\.[a-z]{2,4})
```

##### * Check if numbers are full house - https://regexr.com/3qqma
```
\b(\d)\1{2}(\d)\2{1}(?<!\1)\b|\b(\d)\3{1}(\d)\4{2}(?<!\3)\b
```

##### * Match all words that do not contain hyphen(with negative lookbehind) - https://regexr.com/3r036
```
\b(?<!-)\w+(?!-)\b
```

##### * Match all words that do not contain hyphen(without negative lookbehind) - https://regexr.com/3r03r
```
(?:[^-]|^)\b(\w+)\b(?=[^-]|$)
```

https://stackoverflow.com/questions/50823649/regex-match-all-words-that-do-not-contain-hyphen


##### * Regex to allow letters, one space between words and a total length of 50 - https://regexr.com/3r030
```
(?:[^-]|^)\b(\w+)\b(?=[^-]|$)
```
https://stackoverflow.com/questions/26142059/regex-to-allow-letters-one-space-between-words-and-a-total-length-of-50/26142092#26142092
