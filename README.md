<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Conditioning and Activity Plan</title>
	<link rel="stylesheet" href="styles.css">
</head>
<body>
	<header>
		<h1>Conditioning and Activity Plan</h1>
	</header>
	<nav>
		<ul>
			<li><a href="#schedule">Weekly Schedule</a></li>
			<li><a href="#nutrition">Nutrition Plan</a></li>
			<li><a href="#progress">Log Progress</a></li>
		</ul>
	</nav>
	<section id="schedule">
		<h2>Weekly Schedule</h2>
		<table>
			<thead>
				<tr>
					<th>Day</th>
					<th>Activities</th>
					<th>Times</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>Tuesday</td>
					<td>Taekwondo</td>
					<td>5:15 PM - 6:15 PM</td>
				</tr>
				<tr>
					<td>Wednesday</td>
					<td>Taekwondo</td>
					<td>6:30 PM - 7:30 PM</td>
				</tr>
				<tr>
					<td>Saturday</td>
					<td>Taekwondo</td>
					<td>10:30 AM - 11:30 AM</td>
				</tr>
			</tbody>
		</table>
	</section>
	<section id="nutrition">
		<h2>Nutrition Plan</h2>
		<p>Here's a simple guideline for daily meals tailored for an active lifestyle.</p>
		<ul>
			<li>Breakfast: Omelette with salmon</li>
			<li>Lunch: Chicken breast with wild rice (Pre-pack night before)</li>
			<li>Dinner: Grilled steak with side salad</li>
		</ul>
	</section>
	<section id="progress">
		<h2>Log Your Progress</h2>
		<form id="logForm">
			<label for="date">Date:</label>
			<input type="date" id="date" name="date"><br>
			<label for="activity">Activity:</label>
			<input type="text" id="activity" name="activity"><br>
			<label for="duration">Duration (in hours):</label>
			<input type="text" id="duration" name="duration"><br>
			<button type="submit">Submit</button>
		</form>
	</section>
	<footer>
		<p>&copy; 2024 by Your Site Name. All rights reserved.</p>
	</footer>
	<script src="scripts.js"></script>
</body>
</html>
