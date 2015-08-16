# rial.js
a tiny JavaScript library for money and currency formatting
<pre>
<code>var rial = new Rial( {
			decimal : ",",
			alphabet : "fa",
			currency : "هزار ریال",
			cut : 3,
			} );</code>

<code>rial.get("425420000000");</code>
// ۴۲۵,۴۲۰,۰۰۰ هزار ریال

<code>rial.Alphabet("en").Currency("ریال").Cut(0).get("425420000000");</code>
// 425,420,000,000 ریال

<code>rial.Decimal(".").Alphabet("en").Currency("").Cut(0).get("۴۲۵,۴۲۰,۰۰۰");</code>
// 425.420.000
</pre>

