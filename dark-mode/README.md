# Dark Mode
**3 einfache Wege für einen *Dark-Mode* einer Webseite**

* **Basic**
Mit einem Media Query `@media (prefers-color-scheme: dark) { ... }` auf eine vom Browser angeforderte Version reagieren.
***Demo*** https://code.jens-strack.de/dark-mode/basic.html
  
* **Toggle Button mit Javascript**
Per Button Klick wird dem HTML Tag `<html>` entweder eine Klasse zugewiesen oder entfernt `class="dark"`.
Im CSS kann durch `.dark .deine-css-klasse` das Layout für den *Dark-Mode* angepasst werden.
**Demo:** https://code.jens-strack.de/dark-mode/javascript-toggle.html
  

* **Toggle Button mit Javascript und Local Storage**
In dieser Version wird der Zusatnd zusätzlich im Local Storage gespeichert. Wird der aktive Zustand des *Dark-Mode* im Local Storage gespeichert und die Webseite später neu geladen, wird die Webseite im *Dark-Mode* geladen.
**Demo:** https://code.jens-strack.de/dark-mode/javascript-toggle-local-storage.html
