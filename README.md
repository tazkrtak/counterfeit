# Counterfeit

Fake API data for testing.

```bash
## Root endpoint
curl my-json-server.typicode.com/tazkrtak/counterfeit/

## Deploying Alias* (create a sequential commit and push it)
git deployit
```

## Alias*

```bash
git config alias.deployit '!git commit -a -m "$(( $(git log -1 --format=%s) + 1 ))" && git push origin master'
```
