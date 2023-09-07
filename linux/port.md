
Show all port:
```bash
netstat -anp tcp | grep LISTEN
```

To kill process locking port 3000 on Linux:

sudo lsof -i :3000

or

npx kill-port 3000


