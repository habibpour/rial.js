# rial.js
a tiny JavaScript library for money and currency formatting

<code>
var rial = new Rial( {
			decimal : ",",
			alphabet : "fa",
			currency : "هزار تومان",
			cut : -3,
			} );
</code>

<code>			
rial.get("425420000000");
</code>
// ۴۲۵,۴۲۰,۰۰۰ هزار تومان

<code>
rial.Alphabet("en").Currency("تومان").get("425420000000");
</code>
// 425,420,000,000 تومان
