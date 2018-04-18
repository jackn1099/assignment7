# assignment7

Vunerability 1 - User Enumeration:
  Typing in a username that exists responds with text saying password is incorrect for that username.
  Allows to focus on just the    password box.
Vunerability 2 - XSS:
  After signing in as an admin, typing <script>alert("1")</script> into the post box causes an alert box to pop up
Vunerability 3 - Buffer Overflow
  After signing in as an admin, typing <a title='x onmouseover=alert(unescape(/hello%20world/.source))
  style=position:absolute;left;0;top;0;width;5000px;height;5000px followed but 64kb of text results in a buffer overflow with a popup box
  saying hello world
