# Introduction
Hi! This is my attempt to create a beautiful CV in a Python/Django framework.
I have discovered that many sites that allow for cool CV creation are too simple / pricey when it comes to 
creating CV's with anything more than coloured text on a fancy background. Other sites will host a webpage
for you with graphics and interactive elements, but you cannot really present a website when applying for 
jobs as HR usually likes to have a stack of printed PDFs to choose from when looking for a new employee. And when 
there is a necessity to show certain developer skills in your CV - its best shown by using these skills, 
not by typing it out. 

Updating CV to your recent changes, highlighting most developed skills, keeping track of your history and being
up-to-date is also difficult if you would have to be getting back to old word or LaTEX files, or using the service
that made your CV website all over again. And I have not yet found any platform to do this kind of things for free.

### Problems:

- Not easy to update
- Keep website and pdf always relevant
- No ways of customizing, but always keeping track of all data
- Customization is pricey / hosting costs $$$ per month
- Have to start from the beginning with every CV iteration

### Goals:
- Learn Django framework and put it to use to achieve a decent-looking web CV
- Create a website that spits out a printable pdf version at a push of a button
- Have a platform to note projects and achievements and to keep track of these
- Create PDF CV from website data
- Make the website public
- Create tools to easily update information and highlight relevant information on the website
- Get a job

### Additional goals:
- Make the website interactive
- Very cool modern design
- Mobile adaptation 
- Access via QR
- QR Visit card
- Allow for subsection selection to target different job profiles
- Add a generic blog and notification board for latest projects / achievements 
- Create a knowledge-sharing page to post tutorials and other useful articles for myself and others
- Integrate WebGL + WebXR (*https://www.w3.org/TR/webxr/*) / 
iOS ARKit (*https://developer.apple.com/augmented-reality/arkit/*) for interactive browsing and virtual office

# Usage
While the project is in development, there would be not much to see here. I will try to do my best to 
keep this section updated.

## Local deployment
1. Clone the git repository  
    `git clone https://github.com/Ivansstyle/djangoCVWebsite.git && cd djangoCVWebsite`
2. Create virtual environment  
   `python3 -m venv ./venv/`
3. Activate virtual environment  
`source ./venv/bin/activate`

4. Install django and pillow  
`pip install -r requirements.txt` or `pip install django Pillow django-ckeditor`

*not yet discovered*

## Server deployment 
*not yet discovered*

## Adding and removing info
*not yet implemented*

---

### References
I am following the video from FreeCodeCamp.com (*https://www.youtube.com/watch?v=0oSsLbh_Kv4*) 19:00  
Resume template from I Did Coding (*https://github.com/bobby-didcoding/didcoding_resume_template*)