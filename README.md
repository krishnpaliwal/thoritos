<!DOCTYPE html>
<html>
<head>
<title>Add Listing</title>
</head>
<body>
<h1>Add Listing</h1>
<form action="/add-listing" method="post">
<input type="text" name="owner_name" placeholder="Owner Name">
<input type="text" name="business_name" placeholder="Business Name">
<input type="text" name="entity_name" placeholder="Entity Name">
<input type="email" name="email" placeholder="Email">
<input type="tel" name="contact_number" placeholder="Contact Number">
<input type="text" name="industry" placeholder="Industry">
<input type="number" name="asking_price" placeholder="Asking Price">
<input type="number" name="annual_revenue" placeholder="Annual Revenue">
<input type="number" name="net_profit" placeholder="Net Profit">
<textarea name="description" placeholder="Description"></textarea>
<input type="file" name="pitch_deck">
<input type="checkbox" name="raise_funds"> I want to raise funds
<button type="submit">Submit</button>
</form>
</body>
</html>
