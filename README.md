<!DOCTYPE html>
<html>
<head>
	<title>טיולים בפורטוגל</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<h1>טיולים בפורטו</h1>
		<nav>
			<ul>
				<li><a href="#">הסיורים שלנו</a></li>
				<li><a href="#">Contact</a></li>
				<!-- *Add additional navigation links as needed* -->
			</ul>
		</nav>
	</header>
	<main>
		<section>
			<h2>קונספט הפרי טור:</h2>
			<p> טיולים בקונספט "free tour" הם סיורים תיירותיים בהם המדריך מוביל את הקבוצה בעיר ומספר על האתרים המרכזיים וההיסטוריה של העיר. הייחוד של טיולים כאלה הוא שהם ללא עלות מראש, ובמקום זאת מבוססים על תרומות מתיירים ששמחים לתת לפי יכולתם או בסכום שהם מבחרים לתת לסיור. בטיולים מסוג זה אין חובה לתת כסף, אך מבוססים על מודל של "תתן לפי כמה שנהנת". טיולים כאלה נהנים מפופולריות רבה, מטיילים ומסייעים לפתח את הערכה לסיורים מקצועיים יותר בעתיד.</p>
		</section>
		<section>
			<h2>יצירת קשר</h2>
			<form action="submit-form.php" method="POST">
				<label for="name">שם:</label>
				<input type="text" name="name" id="name" required>
				<label for="email">Email:</label>
				<input type="email" name="email" id="email" required>
				<label for="message">הודעה:</label>
				<textarea name="message" id="message" required></textarea>
				<button type="submit">Send</button>
			</form>
			<!-- *Add additional contact information or social media links as needed* -->
		</section>
	</main>
	<footer>
		<p>&copy;כל הזכויות שמורות לאתר זה</p>
		<!-- -->
	</footer>
</body>
</html>
