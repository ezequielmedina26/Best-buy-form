<!doctype html>
<html>
	<head>
	 <title>Forms</title>
	 </head>
<body style="background-color:aqua">

	<form action="http://www.example.com/subscribe.php" method="get">
	
	<img src="best-buy-logo.jpg" height="60" width="60">
	
<p>Username:
<input type="text" name="username" size="15" maxlength="30" />
</p>

<p>password: 
	<input type="password" name="password" size="15" maxlength="30" />
</p>
	<p>why did you choose best buy?</p>
	<textarea name="comments" cols="20" rows="4">Enter your comment</textarea>
	
	<p>please select your Working skills:
	<br />
	<input type="radio" name="genre" value=assistant Manager" checked="checked"/>assistant Manager
	<input type="radio" name="genre" value=Technician" checked="checked"/>Technician
	<input type="radio" name="genre" value=Cashier" checked="checked"/>Cashier
	</p>
	
	<p>Please select your favorite music services (s):
	<br />
	<input type="radio" name="service" value=itunes" checked="checked"/>Itunes
	<input type="radio" name="service" value=lastfm" checked="checked"/>Last.fm
	<input type="radio" name="service" value=spotify" checked="checked"/>Spotify
	</p>
	
	<p>Which devices do you listen to music on?</p>
	<select name="devices">
		<option value="ipod">ipod</option>
		<option value="radio">radio</option>
		<option value="computer">Computer</option>
	</select>

<p>Which is the most product in the instrument department? you can only select more than one option
holding down shift control on a pc or command key on mac while selecting these
options.</p>

	<select name="instruments" size="3" multiple="multiple">
		<option value="guitar" selected="selected">Guitar</option>
		<option value="drums">drums</option>
		<option value="keyboard" selected="selected">Keyboard</option>
		<option value="bass">Bass</option>
		<option value="microphone" selected="selected">microphone</option>
		<option value="Trumpet">Trumpet</option>
	</select>
		
	<p>which of the following positions would you choose? you cane select more than one option
holding down shift control on a pc or command key on mac while selecting these
options.</p>
	
<select name="Power" size="3" multiple="multiple">	
	<option value="Game assistant" selected="Game assistant">Cryomancer</option> 
	<option value="Phone technician">Phone technician</option>
	<option value="cashier" selected="cashier">cashier</option>
	<option value="store manager">store manager</option>
</select>
	
	<p>please select your favorite tv channel:
	<br />
	<input type="radio" name="sport" value=CW11" checked="checked"/>CW11
	<input type="radio" name="sport" value=TBS" checked="checked"/>TBS
	<input type="radio" name="sport" value=Fox" checked="checked"/>Fox
	<input type="radio" name="sport" value=other" checked="checked"/>other
	</p>
	
	<img src="Channels.png" height="60" width="60">
	
	<p>What was your best accomplishment?</p>
	<textarea name="comments" cols="20" rows="4">Enter your comment</textarea>
	
	<p>What device do you watch t.v on?</p>
	<select name="devices">
		<option value="Sony">Sony</option>
		<option value="Vizio">Vizio</option>
		<option value="philips">philips</option>
	</select>
	
	<img src="samsung-tv-front.jpg" height="60" width="60">
	
			<p>how many pounds can you lift? (s):
	</select>
	<br />
	<input type="radio" name="animal" value=30-50Lbs" checked="checked"/>30-50Lbs
	<input type="radio" name="animal" value=50-80lbs" checked="checked"/>50-80lbs
	<input type="radio" name="animal" value=80-100 or overlbs" checked="checked"/>80-100 or overlbs
	</p>
		
		
	</select>
	
	<p>How many years of working skills you have (s):
	<br />
	<input type="radio" name="insect" value=1-2Years" checked="checked"/>1-2Years
	<input type="radio" name="insect" value=3-4Years" checked="checked"/>3-4Years
	<input type="radio" name="insect" value=5-or more" checked="checked"/>5-or more
	</p>
	
	<p>Please select your Age (s):
	<br />
	<input type="radio" name="Comic book logos" value=17 or under" checked="checked"/>17 or under
	<input type="radio" name="Comic book logos" value=18-21" checked="checked"/>18-21
	<input type="radio" name="Comic book logos" value=22 to over" checked="checked"/>22 to over
	</p>
	
	<p>Select your favorite part of working (s):
	<br />
	<input type="radio" name="character" value=Getting paid" checked="checked"/>Getting paid
	<input type="radio" name="character" value=Greeting the customers" checked="checked"/>Greeting the customers
	<input type="radio" name="character" value=Learning" checked="checked"/>Learning
	</p>

	<p>Choose of the following devices you use? you cane select more than one option
holding down shift control on a pc or command key on mac while selecting these
options.</p>

	<select name="Devices" size="3" multiple="multiple">
		<option value="Iphone" selected="selected">Iphone</option>
		<option value="Android">Android</option>
		<option value="Nokia" selected="selected">Nokia</option>
		<option value="Obama Phone">Obama Phone</option>
	</select>
	
	<img src="Mobile-Phone.jpg" height="60" width="60">
	
	<p>tell us what can you offer to our company and why we should hire you?</p>
	<textarea name="comments" cols="20" rows="4">Enter your comment</textarea>
	
	<p>Your education background:
<input type="text" name="Your education background" size="15" maxlength="30" /> 
</p>
	
	<p>Phone number:
<input type="text" name="Phone number" size="15" maxlength="30" /> 
</p>
	
	<p>Address:
<input type="text" name="Address" size="15" maxlength="30" />
</p>
	
	<p>Put attachment of your resume:
<input type="text" name="Put attachment of your resume" size="15" maxlength="30" />
</p>

<p>Zip code:
<input type="text" name="Zip code" size="15" maxlength="30" />
</p>

<p>Your Signature:
<input type="text" name="Your Signature" size="15" maxlength="30" />
</p>

<div>12312 Best buy<br>
	Best buy,CA 93923<br>
	1-888-555-5555
	<br><br>
</div>

<div>
<small><i>Copyright &copy; 2015 Best Buy<br>
<a href="mailto:BestbuySells@gmail.com"
BestbuySells@gmail.com</a>
</i></small>
</div>

</form>
</body>
</html>
