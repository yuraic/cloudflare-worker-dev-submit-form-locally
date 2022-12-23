# cloudflare-worker-dev-submit-form-locally

This is just a basic example on how to go about CORS headers if you want to submit a web form from local file or localhost (127.0.0.1) to Cloudflare Worked in **dev** **mode**.

## Instructions

Prerequisite. 

- You need to have Cloudflare Wrangler2 installed, [https://github.com/cloudflare/wrangler2](https://github.com/cloudflare/wrangler2). 

- (Optional) You need to have NodeJS installed.

  

You can invoke this webpage on **localhost** or from a **local** file. It will work both ways!!

#### Local file

1. Run wragnler worker from the **package root folder**, wrangler dev; Must be running at http://127.0.0.1:8787 (if it is not, make appropriate changes in the html code of *submit_form.html*)
2. Open *submit_form.html* in browser from the **src/webpage** folder
3. Submit form and Enjoy!

#### localhost

1. Install simple NodeJS web-server from here https://www.npmjs.com/package/http-server.
   Namely, `npm install http-server`.
2. Run webserver from the **src/webpage** folder, `npx http-server .`
3. Run wragnler worker from the **package root folder**, `wrangler dev`; Must be running at http://127.0.0.1:8787 (if it is not, make appropriate changes in the html code of *submit_form.html*)
4. Open in browser, http://127.0.0.1:8080/submit_form.html or whatever your local ip and port are.
5. Submit form and Enjoy!



### Contact me

Ping me if there is any problem with the code. Hopefully I'll have time to help :)





