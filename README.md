# Html
Phoenix Bangla form
<html>
<head>
<script type="text/javascript" src="validate.js"></script>
</head>
<body>
<form action="#" name="phoenix bangla Registration" onsubmit="return(validate());">
    
    <table cellpadding="2" width="20%" bgcolor="99FFFF" align="center"
	cellspacing="2">

	<tr>
		<td colspan=2>
		<center><font size=4><b>phoenix bangla Registration Form</b></font></center>
		</td>
	</tr>

	<tr>
		<td>Name</td>
		<td><input type=text name=textnames id="textname" size="30"></td>
	</tr>

	<tr>
		<td>Father Name</td>
		<td><input type="text" name="fathername" id="fathername"
			size="30"></td>
	</tr>
	<tr>
		<td>Postal Address</td>
		<td><input type="text" name="paddress" id="paddress" size="30"></td>
	</tr>

	<tr>
		<td>Personal Address</td>
		<td><input type="text" name="personaladdress"
			id="personaladdress" size="30"></td>
	</tr>

	<tr>
		<td>Sex</td>
		<td><input type="radio" name="sex" value="male" size="10">Male
		<input type="radio" name="sex" value="Female" size="10">Female</td>
	</tr>

	<tr>
		<td>Country</td>
		<td><select name="Country">
			 <option value="-1" selected>select..</option>
			<option value="Bangladesh">Bangladesh</option>
			
		</select></td>
	</tr>

	<tr>
		<td>Division</td>
		<td><select name="Division">
			<option value="-1" selected>select..</option>
			<option value="Dhaka">Dhaka</option>
			<option value="Chattogram">Chattogram</option>
			<option value="Kulna">Kulna</option>
			<option value="Barisal">Barisal</option>
			<option value="Sylhet">Sylhet</option>
			<option value="Rajshahi">Rajshahi</option>
			<option value="Rangpur">Rangpur</option>
			<<option value="Mymensingh">Mymensingh</option>
		</select></td>
	</tr>

	<tr>
		<td>District</td>
		<td><select name="District">
			<option value="-1" selected>select..</option>
			<option value="Comilla">Comilla</option>
			<option value="Chandpur">Chandpur</option>
			<option value="Bandarban">Bandarban</option>
			<option value="Brahmanbaria">Brahmanbaria</option>
			<option value="Chittagong">Chittagong</option>
			<option value="Fani">Fani</option>
			<option value="Coxbazar">Coxbazar</option>
			<option value="Khagrachhari">Khagrachhari</option>
			<option value="Noakhali">Noakhali</option>
			<option value="Lakshmipur">Lakshmipur</option>
			<option value="Rangamati">Rangamati</option>
		</select></td>

	</tr>

	<tr>
		<td>Upazila</td>
		<td><select Name="Upazila">
			<option value="-1" selected>select..</option>
			<option value="Debidwer">Debidwer</option>
			<option value="Barura">Barura</option>
			<option value="Brahmanpara">Brahmanpara</option>
			<option value="Chandina">Chandina</option>
			<option value="Chauddagram">Chauddagram</option>
			<option value="Daudkandi">Daudkandi</option>
			<option value="Homna">Homna</option>
			<option value="Laksam">Laksam</option>
			<option value="Muradnagar">Muradnagar</option>
			<option value="Nangalkot">Nangalkot</option>
			<option value="Adarsha sadar">Adarsha Sadar Comilla</option>
			<option value="Meghna">Meghna</option>
			<option value="Monohargonj">Monohargonj</option>
			<option value="Sadar South Conilla">Sadar South Conilla</option>
			<option value="Titas">Titas</option>
			<option value="Burichang">Burichang</option>
			<option value="Lalmai">Lalmai</option>
		</select></td>
	</tr>
	<tr>
	<td>Village</td>
	<td><select Name="Village">
	  <option value="-1" Selected >Select..</option>
	<option value="Shuhilpur">Shuhilpur</option>
	<option value="Barera">Barera</option>
	<option value="Bataghashi">Bataghasi</option>
	<option value="Joag">Joag</option>
	<option value="Borcarai">Borcarai</option>
	<option value="Madhaiya">Madhaiya</option>
	<option value="Dollainowabpur">Dollainowabpur</option>
	<option value="Mohochail">Mohochail</option>
	<option value="Gollai">Gollai</option>
	<option value="Keronkhal">Keronkhal</option>
	<option value="Maijkhar">Maijkhar</option>
	<option value="Etberpur">Etberpur</option>
	<<option value="Borcoit">Borcoit</option>
	</select></td></tr>
	<tr>
		<td>ZipCode</td>
		<td><input type="text" name="Zipcode" id="Zipcode" size="30"></td>

	</tr>
	<tr>
		<td>Email</td>
		<td><input type="text" name="email" id="email" size="30"></td>
	</tr>

	<tr>
		<td>DOB</td>
		<td><input type="text" name="dob" id="dob" size="30"></td>
	</tr>

	<tr>
		<td>MobileNo</td>
		<td><input type="text" name="mobileno" id="mobileno" size="30"></td>
	</tr>
	<tr>
	      <td><input type="reset"></td>
		<td colspan="2"><input type="submit" value="Submit Form" /></td>
	</tr>
</table>
</form>
</body>
</html>
