# rial.js
a tiny JavaScript library for money and currency formatting
<pre>
<code>
var rial = new Rial( {
			decimal : ",",
			alphabet : "fa",
			currency : "هزار تومان",
			cut : -3,
			} );
</code>
</pre>

<pre>
<code>			
rial.get("425420000000");
</code>
</pre>
// ۴۲۵,۴۲۰,۰۰۰ هزار تومان

<pre>
<code>
rial.Alphabet("en").Currency("تومان").Cut(0).get("425420000000");
</code>
</pre>
// 425,420,000,000 تومان

<pre>
<code>
rial.Decimal(".").Alphabet("en").Currency("").Cut(0).get("۴۲۵,۴۲۰,۰۰۰");
</code>
</pre>
// 425.420.000
