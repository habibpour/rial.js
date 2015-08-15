# rial.js
a tiny JavaScript library for money and currency formatting

var rial = new Rial( {
			decimal : ",",
			alphabet : "fa",
			currency : "هزار تومان",
			cut : -3,
			} );

			
rial.get("425420000000");
// ۴۲۵,۴۲۰,۰۰۰ هزار تومان


rial.Alphabet("en").Currency("تومان").get("425420000000");
// 425,420,000,000 تومان
