# 192 - Word Frequency Solutions

## MY SOLUTION

```
cat words.txt | tr '[:blank:]' '\n' | sort | uniq -c | sort -rn -k 1 | awk '{print $2" "$1}'
```
