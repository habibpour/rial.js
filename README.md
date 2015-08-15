# rial.js
a tiny JavaScript library for money and currency formatting

var rial = new Rial( {
			decimal : ",",
			alphabet : "fa",
			currency : "هزار تومان",
			cut : -3,
			} );

rial.get("425420000000");
// ۴۲۵,۴۲۰,۰۰۰,۰۰۰ هزار تومان
