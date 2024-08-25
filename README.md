# birthday

<form name="myForm" action="https://niteshuday.github.io/birthday/" onsubmit="return validateForm()">
Name: <input type="text" name="n">
<input type="submit" value="Submit">
</form>
<script>
function validateForm() {
  let x = document.forms["myForm"]["n"].value;
  if (x == "") {
    alert("Name must be filled out");
    return false;
  }
}
</script>
