<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Apply for Financing | TrueNorth Auto Sales</title>
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header>
    <h1>Apply for Financing</h1>
  </header>

  <form action="send-email.php" method="POST" enctype="multipart/form-data" class="credit-form">
    <h2>Personal Info</h2>
    <input type="text" name="fullName" placeholder="Full Name" required>
    <input type="email" name="email" placeholder="Email Address" required>
    <input type="tel" name="phone" placeholder="Phone Number" required>
    <input type="text" name="dob" placeholder="Date of Birth">

    <h2>Address Info</h2>
    <input type="text" name="address" placeholder="Street Address">
    <input type="text" name="city" placeholder="City">
    <input type="text" name="postal" placeholder="Postal Code">

    <h2>Employment Info</h2>
    <input type="text" name="employer" placeholder="Employer Name">
    <input type="text" name="jobTitle" placeholder="Job Title">
    <input type="number" name="income" placeholder="Monthly Income">
    <input type="text" name="employmentDuration" placeholder="Time at Job">

    <h2>Vehicle Interest</h2>
    <input type="text" name="vehicle" placeholder="Vehicle Interested In">
    <textarea name="tradeIn" placeholder="Do you have a trade-in? Details here..."></textarea>

    <h2>Upload ID</h2>
    <input type="file" name="idUpload" accept=".jpg,.jpeg,.png,.pdf">

    <label>
      <input type="checkbox" name="consent" required>
      I authorize TrueNorth Auto Sales to contact me and access my credit if necessary.
    </label>

    <button type="submit">Submit Application</button>
  </form>
</body>
</html>
