# Apninotes
notes
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>payment form</title>
</head>
<body>
  <<form action="">
    <h1>payment form</h1>
    <p>required fileds are followed by *</p>
    <h2>contract information </h2>
    <p>Name: * <input type="text" name="name" required></p>
    <fieldset>
      <legend>Gender *</legend>
    <p>
      Male <input type="radio" name="gender" id="Male " />
         Female <input type="radio" name="gender" id="female" />
    </p>
    </fieldset>
    <p>address: <textarea name="address" id="address" cols="100" rows="8"></textarea> </p>
    <p>Email: <input type="email" name="email" id="email"></p>
    <p>Pinecode:<input type="number" name="pinecode" id="pinecode"></p>
    <h2>payment information</h2>
    <p>
      <select name="card type" id="card type">
        <option value="">---select your card type---</option>
        <option value="visa">visa</option>
        <option value="rupay">rupay</option>
        <option value="phonepey"phonepey </option></option>
      </select>
    </p>
    <p>
      Card Number: <input type="number"name="card Number"id="card Number">
    </p>
    <p>
      Expiration date: <input type="date"name="exp_date"id="exp_date">
    </p>
    <p>cvv <input type="password" name="cvv" id="cvv"></p>
    <input type="submit"value="pay now">
  </form>
</body>
</html>
