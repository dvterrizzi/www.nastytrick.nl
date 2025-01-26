# www.nastytrick.nl
Nasty Trick website ported to static pages.
It only uses pure HTML and CSS without any JavaScript or back-end server/database.

# Bulid
Because it's a static website, there is no need to build anything.

The`app.css` file that's being used was built using sass.
To build it, use the scss compiler to compile the `scss/app.scss` file.
This file uses the other scss files for seperation of concerns:

```
sass scss/app.scss app.css --watch
```

# Hosting
Automatic CI/CD has been set up with GitHub pages using the master branch, and linked to the domain using DNS records.
There is only production. 
