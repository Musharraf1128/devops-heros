# data.sh

## Code

```bash
#!/bin/sh

mkdir test
cd test
touch file.txt
echo "This is a file" > file
cat file
echo "This is the overriden content" > file
cat file
```

## Output

```
This is a file
This is the overriden content
```

## Screenshot

![data.sh output](./screenshots/data.png)
