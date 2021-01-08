---
title: "SNVMDB"
---

## What it is?

SNVMDB is a simplest and easiest database management tool for python.
It is use JSON as databases format

## How can I install it?

You can install it from GitHub, because I`m too lazy to host it to PyPi...
So do the:

```py
pip install git+"https://github.com/SNVMK/snvmdb"
```

And you need install Git and add it to path before install!
Also you can download package directly: [Download!](snvmdb.zip)

## How can I use this?

After you install this, you can write a simple code!
Example:

```py
import snvmdb

db = snvmdb.Database("db.json")

students = db.create_table("students")
students.put("John", 21)
students.put("Suzie", 19)

content = db.show()
table_content = students.show()
print(content)
print(table_content)
```

**But whats doing this code?** Lets show line-by-line!

```py
import snvmdb
```

It is importing library that we have installed.

```py
db = snvmdb.Database("db.json")
```

Initialize empty database and store it to variable.
You may need re-start code after this.

```py
students = db.create_table("students")
```

Create new table "students" and store it to variable.

```py
students.put("John", 21)
students.put("Suzie", 19)
```

Put two pairs to table: John: 21 and Suzi: 19.

```py
content = db.show()
table_content = students.show()
print(content)
print(table_content) 
```

Show all tables in database and items in table

## Are there docs?

Yeah! You can read docs on [this page!](https://snvmk.tk/snvmdb/snvmdb.html "SNVMDB Docs")

## Where can I contribute to this project?

You can support and update this project at [GitHub repo](https://github.com/SNVMK/snvmdb)

---

[![Foo](https://nick-name.ru/img.php?nick=SNVMK&sert=23&text=t4)](https://nick-name.ru/nickname/id1556381/)
