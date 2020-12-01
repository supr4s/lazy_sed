Delete last character

```
sed 's/.$//'
```

Delete numbers

```
sed 's/[0-9]*//g
```

Delete empty lines

```
sed '/^$/d'
```

Transform URL in FQDN

```
sed 's/https\?:\/\///'
```
Print every lines matching $1

```
sed '/'$1'/!d'
```

To be continued ...
