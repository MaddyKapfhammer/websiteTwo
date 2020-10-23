+++
author = "Madelyn Kapfhammer"
title = "Making a Website is Hard"
date = "2020-10-21"
description = "But eventually you'll figure it out"
tags = [
    "website",
    "hugo",
    "html",
    "css",
]
+++

I think as a computer science major it is a rite of passage to struggle when trying to make a customized website. As a computer science major and the _daughter_ of a computer science _professor_ it's even more of a custom to one day decide that the best way to spend your time is creating a website from scratch. Of course, in my second semester of my first year of college I decided to begin the journey of website generation. It lasted about six hours on a Saturday and then I gave up. Maybe the inspiration wasn't there, maybe it was too hard, I really don't remember. Two years later I'm decided that **I'm doing it**. On October 15, 2020 I resolved that my website needed to grace the internet, and here I am. However, I didn't really think it would be this hard...

I don't know why I thought that I would be different from everyone else who has tried to make a website before, but wow, I have enjoyed my series of struggles in my week of trying out web development. `Hugo` makes things easy by providing **so many** themes to choose from when creating a website. Unfortunately, it doesn't always work the first time around. Here is what I've learned so you don't have to.

### What you should know about making your website:

- Please please please check how mobile ready the template you are interested in is

  I think I had a list of ten themes that I _loved_ and almost all of them weren't mobile ready: something that was important to me, and should be important to you too.
  - You can do this through developer tools! If you use Google Chrome it's easy!

      Use the keystroke `Ctrl+Shift+I`

      OR

      1. Select the three dots in the upper right hand corner of your browser
      2. Select the `more tools` option
      3. Select the `developer tools` option

    The developer tools will open, allowing you to resize your screen! Test how reactive the theme you are interested in is to different screen sizes.

- Knowledge of `html` and `css` are __semi-important__

  I started on my website journey with little-to-no knowledge of `html` and `css`, which made it difficult for me to understand how to customize the themes that I chose. So much so, that I had to switch my theme choice about halfway through developing my website

  - Check out the `style.css` file before you clone a theme and make sure you can understand the basics!
  
  - When editing your `style.css` file, ensure that you make a new, custom `css` file in your folder! Most themes' GitHub repositiories will give information on how to do this!

  - Developer tools are also super helpful when trying to change fonts, colors, padding and more!

      Use the keystroke `Ctrl+Shift+I` to open developer tools! Or follow the steps above!

      1. With developer tools open, click whatever object you are interested in changing (i.e. heading font, paragraph text, images)
      2. Developer tools will give all information about that object, including, possibly most importantly **the file and line where the attributes of the object are located**
      3. With the object information, change your `css` file where necessary

- Use localhost when you're first making changes

  The beauty of using `Hugo` is that the changes you make can first be run locally, before deploying your website! I created my entire website, first without connecting it to my domain. This helped ensure that all bugs were removed before I deployed!

  - Most theme templates give specific instructions on how they can be run in the terminal. Most `Hugo` sites use the command `hugo serve`, easy and simple to remember!
  - Running `hugo serve` or your theme's equivalent command will generate a localhost, where your website is generated for your viewing pleasure

    ```
    ^Cmkapfhammer@kallistos:~/website/website2/websiteTwo/quickstart$ hugo serve
    Start building sites …

                    | EN  
    -------------------+-----
    Pages            | 54  
    Paginator pages  |  0  
    Non-page files   | 33  
    Static files     | 10  
    Processed images |  0  
    Aliases          | 15  
    Sitemaps         |  1  
    Cleaned          |  0  

    Built in 249 ms
    Watching for changes in /home/mkapfhammer/website/website2/websiteTwo/quickstart/{archetypes,assets,content,data,layouts,static,themes}
    Watching for config changes in /home/mkapfhammer/website/website2/websiteTwo/quickstart/config.toml
    Environment: "development"
    Serving pages from memory
    Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
    Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
    Press Ctrl+C to stop
    ```
  
  - Any change that you make in your repository, will update on localhost, as soon as the changes are **saved**

    ```
    Change detected, rebuilding site.
    2020-10-22 20:48:03.870 -0400
    Source changed "/home/mkapfhammer/website/website2/websiteTwo/quickstart/content/post/making-website.md": WRITE
    Total in 16 ms
    ```

  - Stop running your localhost at any time with the command `Ctrl+C`

- Even with the learning curve that web development can throw at you, HAVE FUN

    In between classes, studying, and papers, I have been working non-stop on this website. Even in the frustrating parts, where nothing worked, I pushed through the difficulties to get to the wonderful website that you are now seeing before you. It **takes time** to make a website, _don't give up_!
