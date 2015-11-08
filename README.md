# webmatrix-warp-framework-customizer-fix
Add the web.config file to the root of your website if using wordpress.

Else:


```html     
<staticContent>
    <mimeMap fileExtension=".json" mimeType="application/json" />
</staticContent>
```


Needs to go in between the '''<system.webServer>''' element


