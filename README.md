# Security Knowlunch



## Tech talk

Ein Slidedeck mit Remark.js.

`index.html` beinhaltet alle Inhalte in einem Textarea-Element, das Remark ausliest und als Slides darstellt. Die Inhalte können in Markdown geschrieben werden.

Remark selbst liegt in `scripts/remark.min.js`, Version 0.14 minified und der einfachheit haber direkt eingecheckt.
Remark [hat sehr gute Dokumentation](https://github.com/gnab/remark/wiki).

Das Styling der Slides wird in `styles/main.css` definiert. Diese sind zusätzlich zu dem Styling, das mit Remark kommt.

Das Setup ist komplett statisch und kann einfach von einem Webserver serviert werden.
Lokal reicht es die index.html entweder direkt im Bowser zu öffnen oder einen lokalen Webserver laufen zu lassen. (zB [http-server](https://www.npmjs.com/package/http-server) oder `$ python -m SimpleHTTPServer 8000`)
Nach einer Änderung in Inhalt oder Styling einfach Seite neu laden :)
