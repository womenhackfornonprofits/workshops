Workshop Plan

"Create a Simple Website in CSS/HTML and deploy to Amazon S3"

[[TOC]]

## 1. What is HTML?

**HTML - HyperText Markup Language** is the standard language used to create web pages. Web browsers can read **HTML** files and render them into visible web pages.

HTML documents are described by **HTML tags, **these are enclosed in angular brackets <>.

HTML tags can be considered to be "keywords" that the browser can understand and render/draw in the browser appropriately when viewing the page. 

Each browser has default ways of interpreting each element, these can later be "styled" to look how you prefer with the help of CSS, which will be explained a little further on.

## 2. HTML Basics 

We will create a very basic HTML page that will load and simply display "Hello World". It will look like this:

![image alt text](image_0.png)

1. The **DOCTYPE** is a declaration and tells the browser which *'language'* we are talking in so it knows how to render it.

2. The text between **<html>** and **</html>** describes an HTML document

3. The text between **<head>** and **</head>** provides information about the document

4. The text between **<title>** and **</title>** provides a title for the document

5. The text between **<body>** and **</body>** describes the visible page content

6. The text between **<h1>** and **</h1>** describes a heading

7. The text between **<p>** and **</p>** describes a paragraph

## 3. Create a Simple HTML Page

1. Install Sublime [http://www.sublimetext.com/](http://www.sublimetext.com/) or use your preferred text editor

2. Create a new folder in your "Documents" folder for this workshop, let’s call it “website”.

3. Now open the text editor and type out the example code from earlier:![image alt text](image_1.png)

4. Save this file as **index.html , **you can press **_Cmd+S _***(Mac)*** **or **_Ctrl+S_** (WIndows)

    1. **index.html **is a special name and this is a file that the server will look for by default when a certain url is requested (link e.g. [http://website.com](http://website.com)).

    2. Each simple website is basically a "directory" of files, the** index.html **is the first file the web browser will access and from here you can specify how to reach other files via writing hyperlinks.

    3. The default file can be configured to be called something else if required, but for the purpose of this workshop we will only concentrate on simple defaults.

5. Open your web browser, then press **_Ctrl + O_** (Windows) or **_Cmd + O_** (Mac) to open the file we have just created. You should see **"Hello World"** and the text you added as the paragraph.

### What is HTML5 and how is it different?

HTML5 is simply a newer version that is supported by most  modern browsers. HTML5 introduced some more awesome elements/tags we can use: such as <canvas>, <video>, <audio>, <footer> and many more to bring the HTML language more in-line with modern times. 

### HTML Exercises

We can add more to the page at this stage or later, here is a list of html and new html5  tags you can use: [http://www.htmldog.com/references/html/tags/](http://www.htmldog.com/references/html/tags/)

**Exercises**:

1. Add an **image <img>:**

    1. Type out the following and modify the src to point to an image you like: 

![image alt text](image_2.png)

    2. width="100" height="90" are optional, play around with the numbers.

    3. More info - [http://www.htmldog.com/references/html/tags/img/](http://www.htmldog.com/references/html/tags/img/)

2. Add a **link <a> **to your favourite website:

    4. Type out the following and modify it to link to point  your favourite website:

![image alt text](image_3.png)

    5. More info - [http://www.w3schools.com/html/html_links.asp](http://www.w3schools.com/html/html_links.asp)

3. Add a **footer <footer> **(these usually sit at the bottom of the page, but sometimes have to be styled to stay at the bottom if there is not enough content to fill the page):

    6. Type out the following and modify it to say anything you want:

 ![image alt text](image_4.png)

    7. Now try to add a link within the footer to [http://www.lyst.com](http://www.lyst.com)

    8. More info - [http://www.htmldog.com/references/html/tags/footer/](http://www.htmldog.com/references/html/tags/footer/)

4. Add a **comment**, which says "This is my first website!":

    9. Type out the following and modify it to say anything you want:

![image alt text](image_5.png)

    10. More info - [http://www.tutorialspoint.com/html/html_comments.htm](http://www.tutorialspoint.com/html/html_comments.htm)

5. Add an **unordered list** of 3 things you love (use previous examples to get the format right):

    11. Unordered list is started using the tag **<ul> **and** **closed using **</ul>**

    12. Within the list declaration mentioned above you can add in list items, these are defined by: **<li> </li>**

    13. You can have as many list items in the unordered list as you want

    14. Within each item you can add other elements, such as: paragraph, link, images, another list.

    15. Play around with this one, it is very useful especially for menus

    16. More info - [http://www.htmldog.com/references/html/tags/ul/](http://www.htmldog.com/references/html/tags/ul/)

**Further reading:**

1. [https://developer.mozilla.org/en-US/Learn/HTML/HTML_tags](https://developer.mozilla.org/en-US/Learn/HTML/HTML_tags)

2. [https://www.codecademy.com/courses/web-beginner-en-HZA3b/0/1?curriculum_id=50579fb998b470000202dc8b](https://www.codecademy.com/courses/web-beginner-en-HZA3b/0/1?curriculum_id=50579fb998b470000202dc8b)

3. [http://www.tutorialspoint.com/html/](http://www.tutorialspoint.com/html/)

4. [http://codepen.io/pen/](http://codepen.io/pen/) 

## 4. What is CSS?

#### Overview

Cascading Style Sheets (**CSS**) is a style sheet language used for describing what the html elements should "look like". It is used to describe whether an html element should be of certain height, width, if the text should be bold, text colour etc. We will try this shortly.

CSS allows us to separate the document **structure** from document **appearance**, it also allows certain styles to be re-used. For example if all buttons should look the same, it allows us to style them once and not repeat ourselves

#### Terminology

This is a **rule**:

![image alt text](image_6.png)

* This rule starts with **h1**, which is a **selector**.

* The part inside the curly braces is the declaration.

* **color** is a **property**

* **red** is a **value**.

* **color: red;**  is a **property-value**** **pair 

* The **semicolon** after the **property-value**** **pair separates it from other **property-value** pairs in the same declaration, example:

![image alt text](image_7.png)

We will refer to those definitions throughout this class.

When the browser reads the CSS file, it finds each **selector** and works out if it applies to any elements in the HTML.

If it does, it uses the **properties** within the matching rule.

A **style sheet** consists of a list of rules. 

Each **rule** or rule-set consists of one or more **_selectors. _**

**Selectors** allow you to **SELECT** all elements that match:

* a certain tag name e.g. **<h1>**

* In addition to tag names, you can use **attribute values **in selectors and for example select all items that are h1 but have a class .**red (More info on classes later)**

## 5. CSS Basics

### 1. Create a stylesheet

1. Create a new file in the same folder as the i**ndex.html** and name it **style.css**

2. Type out the code below and save in in your **style.css** file:

![image alt text](image_8.png)

Here you created a **rule** that says: 
*All ***_h1_*** elements have these properties:*

1. * text alignment is ***_center_*** *

2. *the text colour is ***_red._**

*Now use the example above to do the same for ***_p_*** element. (clue: create a new rule and  replace ***_h1_*** with ***_p_***)*

### 2. Link the HTML and CSS

Now that we have our first stylesheet, we can tell the html document we created to use that stylesheet to tell the browser what the page should look like.

1. Add the following line in your **index.html** file underneath the **<title> **tag:	

![image alt text](image_9.png)

2. Reload the file in the browser or open it again: Open your web browser, then press **_Ctrl + O_** (Windows) or **_Cmd + O_** (Mac) to open the file we have just updated. You should see "Hello World" and the text you added in the paragraph with the added style.

## 6. Basic CSS Properties

**color**

*Description:** *this is the text colour, this is used to style elements that have text e.g. **h1, p, h2**

*Example***: color: white;**

**background-color**

*Description:* this is used to define the background color of a particular element.

*Example*: **background-color: blue;**

**font-size**

*Description:* this is used to set the size of a font in px or other units

*Example*: **font-size: 16px;**

More info: [Css font size units](http://kyleschaeffer.com/development/css-font-size-em-vs-px-vs-pt-vs/)

**background-image**

**	***Description:*** **this is used to set an image as a background of an element.

	*Example*: **background-image: url(http://examplelink.com);**

	

**text-align**

*Description:*** **this is used to align text.

	*Example*: **text-align: left;**

	

**padding**

*Description:*** **sets the padding of the element. See the [Box Model](#heading=h.7b5to2451tud) Picture below for 

an explanation of what padding is and how it will affect the look of the element.

	*Example*: **padding: 10px 10px 10px 10px;**

**padding: 10px;**

**margin**

*Description:*** **this is used to set the margin of the element. See the [Box Model](#heading=h.7b5to2451tud) 

Picture below for an explanation of what padding is and how it will affect the 

look of the element.

	*Example*: **margin: 10px;**

### CSS Box Model

In a document, each element is represented as a rectangular box

This model describes the content of the space taken by an element. Each box has four edges:

1. the **margin** edge

2. **border** edge

3. **padding** edge

4. **content** edge (in blue)

![image alt text](image_10.png)

**References:**

1. [List of css properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Properties_Reference)

2. [Css Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model#padding)

### CSS Exercises

1. Try out all the properties from the [Basic Properties](#heading=h.m72qoeu0wzrr) section and see what they all do.

2. You can also style the **<body>** element, try setting a background image on the **<body>** element and see what that does.

3. Make an image to also be a link, ie make the image clickable that will take you to a different website.* Tip: you can add some elements inside of other elements,try and add an image within the link.*

4. Align Left or Center all the text on the page

## 7. Creating a free account on Amazon S3

1. Go to [https://aws.amazon.com/s3/](https://aws.amazon.com/s3/)

2. Click on "Try Amazon S3 for Free":

![image alt text](image_11.png)

3. Enter your email address or Phone Number and select  "I am  New User" and click “Sign in using our secure server”

![image alt text](image_12.png)

5. Fill Out required info

![image alt text](image_13.png)

6. Fill out credit card info

7. Confirm your identity via a call

![image alt text](image_14.png)

## 8. Creating a bucket on S3 to host our website 

1. Sign in to the amazon console on [https://aws.amazon.com/s3/](https://aws.amazon.com/s3/)

2. Click on **S3**

![image alt text](image_15.png)

3. Click "Create a new Bucket"

![image alt text](image_16.png)

4. Fill out the bucket name *(example yourname.com)*

## 9. Upload your basic website

1. Click into the bucket

2. Select "Actions" →  “Upload”![image alt text](image_17.png)

3. Click "Set Details" → “Set permissions”

4. Tick "Make everything Public" ![image alt text](image_18.png)

5. Click "Start Upload"

6. Select the file index.html and click "Properties"

7. Click on the Link ![image alt text](image_19.png)

8. This is now your first website LIVE on the internet! It is now accessible via this link at any time.

## 10. Extra reading and tutorials/exercises

1. [Mobile Web Development Course](https://www.udacity.com/course/mobile-web-development--cs256)

2. [Pages sites servers and search engines](https://developer.mozilla.org/en-US/Learn/Pages_sites_servers_and_search_engines)

3. [http://caniuse.com/](http://caniuse.com/) - find out if the tag you would like to use is supported on a particuar browser and which versions.

## 9. Creating all the relevant users/permissions on IAM

1. Sign in to the amazon console on [https://console.aws.amazon.com/console/home?nc2=h_m_mc](https://console.aws.amazon.com/console/home?nc2=h_m_mc)

2. Click on **Identity & Access Management**![image alt text](image_20.png)

3. Click on **User** on the left hand-side menu                     ![image alt text](image_21.png)

4. Click **Create New User**![image alt text](image_22.png)

5. Enter username **testuser **![image alt text](image_23.png)

6. Click **Create
**

7. Download the credentials. These will include User Name, Access Key Id, Secret Access Key.* Keep these secret as they are tied to your account and can be used for malicious purposes if not kept safely. Remember that your account is tied to your credit card.                       *![image alt text](image_24.png)*
*

8. You should now see your user created in the user dashboard![image alt text](image_25.png)

9. Click your newly created user **testuser
**

10. Click on **Permissions → Attach Policy**![image alt text](image_26.png)

11. Select **AmazonS3FullAccess → Attach Policy** ![image alt text](image_27.png)

12. Done ![image alt text](image_28.png)

## 10. Install Grunt 

1. Grunt and Grunt plugins are installed and managed via [npm](https://npmjs.org/), the [Node.js](http://nodejs.org/) package manager. → [https://nodejs.org/en/](https://nodejs.org/en/) 

2. Open your preferred terminal or install [https://www.iterm2.com/](https://www.iterm2.com/)

If you have not used command line terminal before here is a few basic commands:

**ls** 

*Description:* Lists the names of the files in the working directory. 

For more complete information use **ls –alF**

**cd directoryname**

*Description:* Changes the working directory to the one you named.

**cd ..**

*Description:*  Brings you up one directory level.

**cd**

*Description:* Returns you to your home directory.

**pwd**	

*Description:*  Displays the pathname of the current directory.

**mkdir newdirectoryname**

*Description:* Makes a new directory

3. Install **Grunt**, instructions below will install grunt client globally on your machine, if you already have Grunt installed skip this step. For a more detailed explanation see the [official website](http://gruntjs.com/getting-started): ![image alt text](image_29.png)

4. Now we will install **Grunt** locally specifically for this project. Go to your project folder **workshop:** in the terminal type out the below command to get to the project folder (if you have saved the workshop folder elsewhere adjust the path):                                                                   ![image alt text](image_30.png)** 
**

5. In your terminal type out npm init and follow the instructions ![image alt text](image_31.png)

## 11. Install Grunt AWS Plugin 

Grunt uses different plugins to perform certain tasks, in order to deploy to Amazon S3 we will use the following plugin: [https://github.com/MathieuLoutre/grunt-aws-s3](https://github.com/MathieuLoutre/grunt-aws-s3)

1. In your workshop folder we can install this task using the command below: ![image alt text](image_32.png)

2. We now have the plugin installed and we can configure grunt to use this task to deploy our project without having to manually upload the files every time.

3. In order for us to use this plugin  and deploy to S3 in the command line we need to create a file called **s3settings.json,** here we will keep all the login details and bucket information. 
*This file MUST be kept secret, do not commit it to github or any other version control. It should be excluded in .gitignore file if you are using git. It is important to take care as if these details are made public your account may be accessed and used by someone else, leaving you with a bill to pay*: ![image alt text](image_33.png)

The **key** and **secret** are available in the user credentials file you downloaded earlier when creating an IAM **testuser**.
**Bucket** must be exactly what you called the bucket on Amazon S3 and the same for **region**.

4. The second file we need to create is** Gruntfile.js** this is a default file Grunt will look for locally within the project folder. Here is where we configure the 

5. Using your text editor or command line, create a new file within the **workshop** folder called **Gruntfile.js, **the content of it should be the following: ![image alt text](image_34.png)

Full [code to copy is here](http://pastebin.com/vm7zmcWV).

Here we have configured the plugin to upload to Amazon S3 all files in the folder **deploy, **so we would now have to create this folder within the project and copy any files we want uploaded.

We have also created a task called **deploy** which can be run in command line within the project folder to upload all files within deploy folder to Amazon S3, to the bucket specified in the **s3settings.json** file.

## 11. Use Grunt to deploy to S3

1. Go to the project folder in the terminal

2. you can now run the deploy command by typing: ![image alt text](image_35.png)

## 12. Windows specific alterations

1. Use Command Prompt as command line

2. Grunt install → [http://www.codebelt.com/javascript/install-grunt-js-on-windows/](http://www.codebelt.com/javascript/install-grunt-js-on-windows/)

3. Windows command line commands → [http://ss64.com/nt/](http://ss64.com/nt/)

4. Install Grunt, more instructions → [http://foundation.zurb.com/forum/posts/11597-how-to-install-grunt-and-libsass-on-windows](http://foundation.zurb.com/forum/posts/11597-how-to-install-grunt-and-libsass-on-windows)

