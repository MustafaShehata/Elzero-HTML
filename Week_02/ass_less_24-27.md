# Week_02

## Lessons_From_24_to_27

### Assignment_01

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Assignment_01_less_24_27_Form_Part_One</title>
  </head>
  <body>
    <form action="test.py" method="POST">
      <div>
        <label>Username</label>
        <br />
        <input type="text" required placeholder="Username" name="user" />
      </div>
      <hr />
      <div>
        <label>Password</label>
        <br />
        <input
          type="password"
          placeholder="Write a complex Password"
          name="pass"
        />
      </div>
      <hr />
      <div>
        <label>Mobile</label>
        <br />
        <input
          type="text"
          placeholder="Enter a city code + number"
          name="mobile"
        />
      </div>
      <hr />
      <div>
        <label>Email</label>
        <br />
        <input
          type="email"
          required
          placeholder="Enter an available email"
          name="mail"
        />
      </div>
      <hr />
      <div>
        <label>Subject</label>
        <br />
        <input
          type="text"
          placeholder="Enter a subject from your list"
          name="subject"
        />
      </div>
      <hr />
      <input
        type="hidden"
        value="Data of this form should be store in hidden input"
      />
      <input type="submit" value="Send Data" />
      <input type="reset" value="Empty Form" />
    </form>
  </body>
</html>
```

### Assignment_02

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Assignment_02_less_24_27_Form_Part_One</title>
  </head>
  <body>
    <form action="">
      <input type="range" min="100" max="500" step="50" value="400" />
    </form>
  </body>
</html>
```
