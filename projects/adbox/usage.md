# Usage

* dump - module for extracting AD objects (users/computers/groups) and saving to the database (sqlite3)

{% hint style="info" %}
python3 -m ADBox -m dump -srv 192.168.1.100 -usr TEST\user -passwd TestPassword
{% endhint %}

* gui - graphical interface for viewing objects

{% hint style="info" %}
python3 -m ADBox -m gui
{% endhint %}
