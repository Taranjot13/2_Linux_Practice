## 🔹 Basics
```bash
#!/bin/bash
echo "Hello World"
🔹 Variables
name="Taranjot"

echo $name

🔹 Conditionals

if [ "$name" = "Taranjot" ]; then
  echo "Hi"
fi


🔹 Loops

for i in {1..5}; do echo $i; done


🔹 Arguments
$0, $1, $2, ...


🔹 Functions

myfunc() {
  echo "Function"
}
myfunc


