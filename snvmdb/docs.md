---
title: "SNVMDB Docs"
---

## ***class* Database(*file*: str)**

Creates or loads database file, which name given in *file* argument
If file doesn`t exists, it is try to create it

### ***def* load()**

Load database. **You dont need to do this**, it is called automatically on init.

### ***def* save()**

Save changes. **It is** also called **automatically** on all changes.

### ***def* create_table(table)**

Create new table with name given in *table*, and return it.

### ***def* get_table(table)**

Get already exists *table*, and return it.

### ***def* show()**

Return all tables in database.

## ***class* Table(*name*: str)**

Represents table with name. You cant instantiate this class, it is abstract.

### ***def* put(key, value)**

Put *key* to table and assign *value* to it.

### ***def* drop()**

Remove table.

### ***def* del_key(key)**

Delete key from table.

### ***def* get_key(key)**

Get key, and return it.

### ***def* shоw()**

Return all keys in table.

[![Foo](https://nick-name.ru/img.php?nick=SNVMK&sert=2&text=t4)](https://nick-name.ru/nickname/id1556381/)
