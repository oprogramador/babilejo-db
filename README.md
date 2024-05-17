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
data["United States"] = { myName: "United States" };
data["Joe Biden"] = { myName: "Joe Biden"};
data["United States"].president = data["Joe Biden"];
data["United States"].president
```
