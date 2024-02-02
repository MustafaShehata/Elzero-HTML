# WEEK (2)

## Assignment Lessons 15 to 18

### Assignment_01
* Help
- Search for "width attribute" for table
- Search for "rowspan" for doing merging two rows
- You can add a image from placeholder
---
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Table Assignment</title>
</head>
<body>
  <table border="1px" style="width:100%;padding:4px">
    <caption>Members Data</caption>
    <thead>
      <tr>
        <th>Group</th>
        <th>Avatar</th>
        <th>Name</th>
        <th>Email</th>
        <th>Character</th>
        <th>Profile</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="2">Ninja</td>
        <td><img src="https://via.placeholder.com/40x40/F00/FFF"/></td>
        <td>Osama<br/>Mohamed</td>
        <td>o1@nn.sa<hr>o2@nn.sa</td>
        <td>&copy;</td>
        <td><a href="#" target="_blank"/>Profile</a></td>
      </tr>
      <tr>
        <td><img src="https://via.placeholder.com/40x40/00F/FFF"/></td>
        <td>Shady<br>Nabil</td>
        <td>s@nn.sa</td>
        <td>&trade;</td>
        <td><a href="#" target="_blank">Profile</a></td>
      </tr>
      <tr>
        <td>Monster</td>
        <td><img src="https://via.placeholder.com/40x40/000/FFF"></td>
        <td>Mohamed<br>Ibrahim</td>
        <td>m@nn.sa</td>
        <td>&reg;</td>
        <td><a href="#" target="_blank">Profile</a></td>
      </tr>
    </tbody>
    <tfoot>
      <td colspan="5">Total Members</td>
      <td>3</td>
    </tfoot>
  </table>
</body>
```
---
### Assignment_02
* إبحث عن خواص الجدول مثل cellspacing, cellpadding
* عندما تتعلم CSS ستقوم بعمل هذه الخواص بدون إستخدامها ك Attribute


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8"/>
    <title>week_02_assign_02</title>
    <style>
    </style>
  </head>
  <body>
    <table  border="1px" cellspacing="0" cellpadding="30px">
      <caption>Table Caption</caption>
      <thead>
        <tr>
          <th>Date</th>
          <th>Name</th>
          <th>Points</th>
        </tr>
      </thead>
      <tbody>
      <tr>
        <td rowspan="4">Month</td>
        <td>Osama Mohamed</td>
        <td>100</td>
      </tr>
      <tr>
        <td>Sayed Mohamed</td>
        <td>100</td>
      </tr>
      <tr>
        <td>Ahmed Mohamed</td>
        <td>100</td>
      </tr>
      <tr>
        <td>Eman Mohamed</td>
        <td>100</td>
      </tr>
      </tbody>
    </table>
  </body>
</html>
```

### Assignment_03

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>week_02_assign_03</title>
  </head>
  <body>
    <table border="1px">
      <caption>
        Complex Table
      </caption>
      <thead>
        <tr>
          <th>Year</th>
          <th>Group</th>
          <th>Language</th>
          <th>Done</th>
          <th>Passed</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td rowspan="5">2022</td>
          <td rowspan="2">Elzero</td>
          <td>HTML</td>
          <td colspan="2">Yes</td>
        </tr>
        <tr>
          <td>CSS</td>
          <td colspan="2">Yes</td>
        </tr>
        <tr>
          <td rowspan="3">Heroes</td>
          <td>JS</td>
          <td>Yes</td>
          <td>No</td>
        </tr>
        <tr>
          <td>PHP</td>
          <td colspan="2">Yes</td>
        </tr>
        <tr>
          <td>Python</td>
          <td>No</td>
          <td>No</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```

Assignment link: https://elzero.org/html-assignments-lesson-from-15-to-18/

**اللهم علمنا ما ينفعنا وانفعنا بما علمتنا انك انت العليم الحكيم**
