# Test caddy

What to do to test that:

- Download the version of caddy you wanna test for linux amd64
- Put a copy inside the `proxy` folder named `caddy`
- Put a copy inside the `ws` folder named `caddy`
- Run `docker-compose up` to start the two containers
- Access the external ip of the container with port 8000 on the browser.
- Look in the web console of the browser; there should be a message received saying `Message`
