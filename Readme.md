##KonamiJS

This is a small JavaScript library, that allow you to easily trigger an action on your page, when the user performs the well-known Konami-Code (up, up, down, down, left, right, left, right, b, a).


####Usage

Include the library before your main script. To execute some JS when the code is performed, use :
```
Konami.onCodePerform = function() {
  //Place your code here
}
```