# Usage

* dump - module for extracting AD objects (users/computers/groups) and saving to the database (sqlite3)

```python
python3 -m ADBox -m dump -srv 192.168.1.100 -usr TEST\user -passwd TestPassword
```

* gui - graphical interface for viewing objects

```python
 python3 -m ADBox -m gui
```
