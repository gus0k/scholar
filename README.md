# Query google scholar and store results

It queries google scholar and stores the first MAX results in a csv file.

Only the information shown is parsed, there is no recursive traversal.

Usage

```sh

./get_query dark matter
```

Explore results

```
csvlook -d "|" -H data.csv | less -S
```


