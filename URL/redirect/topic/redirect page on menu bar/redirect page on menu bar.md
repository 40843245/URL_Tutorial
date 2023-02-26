# Redirect page on menu bar
In this article, I will teach tou how to 

auto add an option on menu bar when right click of the link.

It is very simple.

Step 1:

Create a new file with a .htaccess extension in the root directory of your website. If you already have an .htaccess file, skip this step. 

Step 2:
Open the .htaccess file and add the following code:

Redirect 301 /redirect-url /destination-url

where

    /redirect-url refers the url redirected from.

    /destination-url refers the url redirected to.

Step 3:

Save the .htaccess file and upload it to the root directory of your website.

Step 4:

You complete.

## Ref

The solution of the question of chatGPT.

    How to get the url will auto-redirect to with specified url?
    
chatGPT is available at

    https://openai.com/blog/chatgpt/


    
Alternatively, you can add a URL that auto-redirects to a specified URL using a meta refresh redirect in your .html file.

Step 1:

Create a new HTML file and save it as .html.

Step 2:

Add the following statement to your HTML file:

    <meta http-equiv="refresh" content="0; url=destination-url">
            
Step 3:

Replace "destination-url" with the URL you want to redirect to.


Step 4:

You complete.

Just to open the .html with webbrowser.

It should automatically redirect to the "destination-url."


Here are a template

    <html>
        <head>
            <meta http-equiv="refresh" content="0; url=destination-url">
            <!--      Design your page         -->
        </head>
        <body>
        </body>
     </html>
