# babilejo-db

```
Who is "president" of "United States"?
I do not know.
"president" of "United States" is "Joe Biden".
Who is "president" of "United States"?
"Joe Biden"
```

```js
data = {};
data["United States"] = { myName: "United States", start: new Date() };
data["Joe Biden"] = { myName: "Joe Biden", start: new Date() };
data["United States"].president = { name: "Joe Biden", start: new Date() };
data["United States"].president;
data[data["United States"].president.name]
```
