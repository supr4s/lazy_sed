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

Basic substitution - replace toto with tata

```
sed 's/toto/tata/g' file.txt
```

Deleting lines with multiples patterns

```
sed -e '/pattern1/d ; /pattern2/d ; /pattern3/d ; /pattern4/d' ./my_files.txt
```

To be continued ...
