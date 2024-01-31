## Assignmnets Lessons 1 to 5
[html assignments lesson 1 to 5](https://elzero.org/html-assignments-lesson-from-1-to-5/)

### Assignment_01
HTML = stands for **HyperText Markup Language**
  markup language is a system based on elements such as keywords, names and tags.
___

### Assignment_02
*   قم بإنشاء صفحة كاملة فيها جميع العناصر التالية html, head, body
*   قم بإنشاء عنوان للصفحة بإسم My First Page
*   قم بوضع وصف الصفحة الذي يظهر في المتصفحات This Is Description For My First Page
*   قم بوضع العنصر الذي يتم كتابة CSS Code داخله ويمكن تركه فارغا
*   قم بوضع العنصر الذي يتم كتابة JavaScript Code داخله ويمكن تركه فارغا
*   قم بوضع العنصر المسؤول عن إستدعاء ملف CSS خارجي
*   قم بكتابة نص This Is My First Page بحيث يظهر داخل الصفحة

**Solution**

```html
<!DOCTPYE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="description" content="This Is Description For My First Page" />
    <meta name="author" content="Mustafa S. Ramadan" />
    <title>My First Page</title>
    <style></style>
    <script></script>
    <link rel="stylesheet" href=""/>
  </head>
  <body>
    This Is My First Page
  </body>
</html>
```
___

### Assignment_03
* هل ما يتم كتابته داخل ال Head يظهر داخل الصفحة أم لا؟
* هل عنصر Title له قفلة أم لا ؟
* هل عنصر Meta له قفلة أم لا ؟
* هل ما يتم وضعه داخل ال Description في عنصر ال Meta يظهر في الصفحة أم لا ؟

 [01] => **No**
 [02] => **Yes**
 [03] => **No**
 [04] => **No**

___

### Assignment_04

* قم بكتابة 4 عناصر Meta داخل ال Head مع شرح كل فائدة كل واحد فيهم عن طريق Multiple Line Comment

```html
<!-- Example -->
<meta name="description" content="My first web page project(Description)" />
<meta name="keywords" content="HTML, CSS, JavaScript" /><!-- for SEO -->
<meta name="copyright" content="Your Company Or your Brand Name" />
<meta name="author" content="Mustafa Ramadan" />
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" /> <!-- for all media and phone, pc, laptop, and ipad -->
```
___

## Model Answer
___
```html
<html> <!--Hypertext Markup Language-->
  <head> <!--هذا الكود لا يظهر فى الصفحة بل يستخدم فلى تنظيم الصفحة من الخارج-->
    <meta charset="UTF-8" /> <!--ترميز الموقع وهذا الترميز العلامى الذى يدعم كل اللغات و كل الأحرف-->
    <title>My Frist Page</title> <!--عنوان الموقع-->
    <meta name="description" content="This Is Description For My First Page" /> <!--هذا هو وصف الصفحة-->
    <meta name="copyright" content="Your Company Or Brand Name" /> <!--هذا حقوق نشر وطبع الموقع-->
    <meta name="author" content="Yousef" /> <!--هذا اسم مؤلف الموقع-->
    <style></style> <!--CSS هذا هو الكود الخاص باستدعاء اوامر-->
    <script></script> <!--Java Script هذا الكود الخاص باستدعاء اوامر -->
    <link rel="" href="" /> <!--CSS هذا الكود خاص باستدعاءادوات -->
  </head>
  <body> <!--هذا الكود الخاص بكل شىء يظهر فى الموقع-->
    This Is My First Page
  </body>
</html>
```
___