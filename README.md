# webpack-workshop
webpack easy workshop

## Step 1
écrire dans le fichier entry.js

```javascript
document.write("le fichier content.js nous est bien compilé");
```

écrire dans index.html 
```
<html>
    <head>
        <meta charset="utf-8">
    </head>
    <body>
        <script type="text/javascript" src="bundle.js" charset="utf-8"></script>
    </body>
</html>
```

puis lancer la compilation webpack avec l'invité de commande

<pre>
webpack ./entry.js bundle.js
</pre>

