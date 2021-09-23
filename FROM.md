<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form</title>
</head>
<body>
  <caption><h2> USER FROM </h2> </caption>
    <form action="results.html" method="GET">
        <div>
          <label for="name">FIRST NAME</label>
          <input type="text" name="name" id="name" required>
        </div>
        <div>
          <label for="name">PASSWORD</label>
          <input type="text" name="name" id="name" required>
        </div>
        <div>
          GENDER
          <div>
            <label for="male">Male</label>
            <input type="radio" name="gender" id="male" value="male">
          </div>
          <div>
            <label for="female">Female</label>
            <input type="radio" name="gender" id="female" value="female">
          </div>
          <div>
            <label for="bio">ADDRESS</label>
            <textarea id="bio" name="bio"></textarea>
          </div>
        <div>
          <label for="date">D,O.B</label> 
          <input type="date" name="date" id="date" min="2019-06-10">
        </div>
        <div>
          SELECT GAMES
          <div>
            <label for="hockey">Hockey</label>
            <input type="checkbox" name="hockey" id="hockey">
          </div>
          <div>
            <label for="football">Footbal</label>
            <input type="checkbox" name="footbal" id="footbal">
          </div>
          <div>
            <label for="cricket">Cricket</label>
            <input type="checkbox" name="cricket" id="cricket">
          </div>
          <div>
            <label for=volleyball">VolleyBall</label>
            <input type="checkbox" name="volleyball" id="volleyball">
          </div>
          <div>
            MARITAL STATUS
            <div>
              <label for="married">Married</label>
              <input type="checkbox" name="married" id="married">
            </div>
            <div>
              <label for="unmarried">Unmarried</label>
              <input type="checkbox" name="unmarried" id="unmarried">
            </div>
          <label for="I accept this agrement">I accept this agrement</label>
          <input type="checkbox" name="I accept this agrement" id="I accept this agrement">
        </div>
        <button type="reset">Reset</button>
        <button type="submit">Submit</button>
      </form>
</body>
</html>
