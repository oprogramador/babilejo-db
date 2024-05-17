# babilejo-db

```
Who is "president" of "United States"?
I do not know.
"president" of "United States" is "Joe Biden".
Who is "president" of "United States"?
"Joe Biden"
Says: "Joe Biden" will be "president" of "United States" in year 2026.
Says: "Donald Trump" will be "president" of "United States" in year 2026.
Says: "Joe Biden" will be "president" of "United States" in year 2026.
Says: "Donald Trump" will be "president" of "United States" in year 2026.
Says: "Joe Biden" will be "president" of "United States" in year 2026.
Who will be "president" of "United States" in year 2026?
There is 60% probability for "Joe Biden" and 40% probability for "Donald Trump".
```

```js
data = {};
data["United States"] = { myName: "United States", start: new Date() };
data["Joe Biden"] = { myName: "Joe Biden", start: new Date() };
data["Donald Trump"] = { myName: "Donald Trump", start: new Date() };
data["United States"].president = { name: "Joe Biden", start: new Date(), predictions: [] };
data["United States"].president;
data[data["United States"].president.name];
data["United States"].president.predictions.push({ start: new Date('2026'), name: "Joe Biden" });
data["United States"].president.predictions.push({ start: new Date('2026'), name: "Donald Trump" });
data["United States"].president.predictions.push({ start: new Date('2026'), name: "Joe Biden" });
data["United States"].president.predictions.push({ start: new Date('2026'), name: "Donald Trump" });
data["United States"].president.predictions.push({ start: new Date('2026'), name: "Joe Biden" });
data["United States"].president.predictions
```
