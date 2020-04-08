<!DOCTYPE html>
<html lang="en">

	<head>
		<meta charset="utf-8" />
		<title>Party Tickets Order Form</title>
		<link rel="stylesheet" href="styles/normalize.css">
		<link rel="stylesheet" href="styles/main.css">
	</head>

	<body>
		<!-- header starts -->
		<header>
			<img src="images/pumpkin.gif" alt="Pumpkin" width="85">
			<h2>The Halloween Store</h2>
			<h3>For the little Goblin in all of us!</h3>
		</header>
		
		<!-- navigation starts -->
		<nav id="nav_menu">
			<ul>
				<li><a href="index.html" class="current">Home</a></li>
				<li><a href="about_us.html">About Us</a>
					<ul>						
						<li><a href="our_history.html">Our History</a></li>
						<li><a href="our_team.html">Our Team</a></li>
					</ul>
				</li>
				<li><a href="products.html">Our Products</a></li>
				<li><a href="tickets_order_form.html">Party Tickets</a></li>
				<li><a href="contact_us.html">Contact Us</a></li>
			</ul>
		</nav>

		<!-- main content starts -->
		<main>
			<!-- sidebar starts -->
			<aside>
				<ul>
					<li><a href="products/props.html">Props</a></li>
					<li><a href="products/costumes.html">Costumes</a></li>
					<li><a href="products/special.html">Special FX</a></li>
					<li><a href="products/masks.html">Masks</a></li>
				</ul>
			</aside>

			<!-- the main section of the content starts -->
			<section>
				<h1>Buy Tickets for a Halloween Party</h1>
				
				<!-- Form Starts here -->
				<form name="order_form" action="place_order.html" method="post">
				
				<!-- first part of form Membershit info -->
					<fieldset id="member_info">
						<legend>Membership Information</legend>
						<label for="email">E-Mail:</label>
						<input type="email" name="email" id="email" title="Fill your email address here" autofocus required><br>
						<label for="first_name">First Name:</label>
						<input type="text" name="first_name" id="first_name" title="Enter your first name" required><br>
						<label for="last_name">Last Name:</label>
						<input type="text" name="last_name" id="last_name" title="Enter your last name" required><br>
						<label for="address">Address:</label>
						<input type="text" name="address" id="address" title="Enter you full address" ><br>
						<label for="city">City:</label>
						<input type="text" name="city" id="city" title="Enter your city name" required><br>
						<label for="province">Province:</label>
						<input type="text" name="province" id="province" maxlength="2" placeholder="2-character code" title="Enter your province using 2 characters" required><br>
						<label for="postal_code">Postal Code:</label>
						<input type="text" name="postal_code" id="postal_code" required placeholder="Must be 6 characters long"
							   pattern="[a-zA-Z0-9]{6}" title="Must be 6 alphanumeric characters long"><br>
						<label for="phone">Phone Number:</label>
						<input type="tel" name="phone" id="phone" placeholder="999-999-9999"
							   pattern="\d{3}[\-]\d{3}[\-]\d{4}" title="Must be 999-999-999 format"><br>
					</fieldset>
					
					<!-- Second part order info -->
					<fieldset id="order_info">
						<legend>Ordering Information</legend>
						<label for="party">Party:</label>
						<select name="party" id="party">
							<option value="ff">Fang-tastic Feast</option>
							<option value="fn">Fright Night</option>
							<option value="gno">Ghouls' Night Out</option>
							<option value="mm">Monster Mash</option>
						</select><br>
						<label for="order_type">Order Type:</label>
						<select name="order_type" id="order_type">
							<option value="mp">Member Package</option>
							<option value="dp">Donor Package</option>
							<option value="st">Single Tickets</option>
						</select><br>
						<label for="num_tickets">Number of Tickets:</label>
						<input type="number" name="num_tickets" id="num_tickets" placeholder="Number of Single Tickets"><br>
					</fieldset>
					
					<!-- third one payment method -->
					<fieldset id="pymt_mehtod">
						<legend>Payment Method</legend>
						<label id="pymt_mthd" class="radio-inline"><input type="radio" id="billme" name="pymt_mthd" value="billme">Bill Me</label>
						<label id="pymt_mthd" class="radio-inline"><input type="radio" id="cc" name="pymt_mthd" value="cc">Credit Card</label>
					</fieldset>
					
					<!-- Last one payment infoo -->
					<fieldset id="pymt_info">
						<legend>Credit Card Information</legend>
						<label for="card_type">Card Type:</label>
						<select name="card_type" id="card_type">
							<option value="v">Visa</option>
							<option value="mc">Master Card</option>
							<option value="d">Discover</option>
						</select><br>
						<label for="card_num">Card Number:</label>
						<input type="tel" name="card_num" id="card_num" required placeholder="16 digits" maxlength="16"
							    title="Credit card number"><br>
						<label for="exp_date">Expiration Date:</label>
						<select name="month" id="month">
							<option value="jan">January</option>
							<option value="feb">Februaury</option>
							<option value="march">March</option>
							<option value="april">April</option>
							<option value="may">May</option>
							<option value="june">June</option>
							<option value="july">July</option>
							<option value="aug">August</option>
							<option value="sept">September</option>
							<option value="oct">October</option>
							<option value="nov">November</option>
							<option value="dec">December</option>
						</select>
						<select name="year" id="year">
							<option value="15">2015</option>
							<option value="16">2016</option>
							<option value="17">2017</option>
							<option value="18">2018</option>
							<option value="19">2019</option>
						</select>
					</fieldset>
					
					<!-- Finally submission or resetting the form -->
					<fieldset id="submit_buttons">
						<legend>Submit Your Order</legend>
						<label>&nbsp;</label>
						<input type="submit" id="submit" value="Submit">
						<input type="reset" id="reset" value="Reset Fields">
					</fieldset>
				</form>
			</section>
		</main>

		<!-- footer starts -->
		<footer>
			<p>&copy; 2020 Gursimran Singh</p>
		</footer>
	</body>
</html>
