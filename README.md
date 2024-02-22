# Odin's Express Local Library
A local library mockup made with [the MDN tutorial on express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website), as part of the Odin Project Course.

This project uses my own implementation of a .properties file to configure the database access and protect my information, so you're required to make your own 'database.properties' file in the root folder and fill it with your mongo DB connection string

In the glitch preview, I had to change it to use the environment variables as a .properties file would be visible to all, as you can see [here](https://glitch.com/edit/#!/famous-longing-waxflower), but it would work in a more private service hosting it, I just used Glitch to follow the tutorial, so I had to change it.

Also, according to glitch specifications, I had to downgrade node to its 16.14.2 version, but the project was developed to work with node v18.17.1, which wouldn't be accepted by glitch.

You can click [here](https://famous-longing-waxflower.glitch.me/catalog/authors) for a live preview.
