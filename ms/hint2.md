# Hint 2

Let’s automate the brute force by repeating an integer a large number of times:

```
$ echo 'content=Buy milk in '`printf %.0s5 {1..600}`' minutes' | http --form http://localhost:3001/create -v
```
