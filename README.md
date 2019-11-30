SaVeR
=====

Separated Values Re-writer


I often need to munge a column of data (either from Excel or a DB query)

I had a set of Python scripts that did most of what I want but to make it accesible to others on my team, I wrote a standalone HTML/JS version.

One of my main use cases is creating a list for a SQL 'in' clause based on a spreadsheet or an exception email listing the failed keys.

I'll paste this into the left text box and choose the option to split on newlines.

```
123
456
789
```

on the right side I'll pick the options for:

  comma separator, smart quotes, and add parenthesis

and get back

`(123,456,789)`

which is easily pasted into an 'where key in' SQL clause.




