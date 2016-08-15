# Rial.js
A tiny JavaScript library for money and currency formatting
```javascript
var rial = new Rial({
	decimal : ",",
	alphabet : "fa",
	currency : "هزار ریال",
	cut : 3,
});

rial.get("425420000000"); // ۴۲۵,۴۲۰,۰۰۰ هزار ریال

rial.Alphabet("en").Currency("ریال").Cut(0).get("425420000000"); // 425,420,000,000 ریال

rial.Decimal(".").Alphabet("en").Currency("").Cut(0).get("۴۲۵,۴۲۰,۰۰۰"); // 425.420.000
```
