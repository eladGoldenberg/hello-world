# hello-world
hello world first project learning github
just making my first commit!

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Object-oriented JavaScript example</title>
  </head>

  <body>
    <div>
      <label for="jscode">Enter code:</label>
      <input type="text" id="jscode">
      <button>Submit code</button>
    </div>

    <p></p>
  </body>

    <script>
      function Person(first, last, age, gender, interests) {
  this.name = {
    first,
    last
  };
  this.age = age;
  this.gender = gender;
  this.interests = interests;
  this.bio = function() {
    alert(this.name.first + ' ' + this.name.last + ' is ' + this.age + ' years old. He likes ' + this.interests[0] + ' and ' + this.interests[1] + '.');
  };
  this.greeting = function() {
    alert('Hi! I\'m ' + this.name.first + '.');
  };
}
      var person1 = new Person('Bob', 'Smith', 32, 'male', ['music', 'skiing']);
    </script>
</html>
