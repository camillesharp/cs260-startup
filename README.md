# cs260-startup
My startup project for CS 260

## Elevator Pitch 
Finding and hiring talent shouldn't be complicated. Our streamlined job board makes it easier than ever for businesses to post jobs and for job seekers to apply with just a few clicks. No clutter, no confusion—just fast, effective connections between employers and candidates. Simplify your hiring process today with our intuitive platform. 

## Key Features 
* Secure login over HTTPS
* Profile creation
* Ability to post job positions
* Ability to view job postings
* Chat box for communication
* All data is persistantly stored

## Technologies
* HTML - Use HTML to structure the content on the application. There will be four HTML pages including the profile, feed, profile 
creation, and login. 
* CSS - Styling for the application that creates dynamic sizing and creates a visually appealing website. 
* React - Provides login, updating job posts, creating profiles, used for making basic website components. 
* Service - Retrieving job posts, submitting job posts, retriving profile information 
* DB/Login - Stores profile accounts, store job post information. Can't post job unless authenticated. 
* WebSocket - Used to create a chat feature for users to communicate. 
   
## Design
![image](startup.jpg)

## IP address and Server Setup
I successfully set up my server configurations and assigned it an elastic IP address. I also was able to remote shell into my server. 

## Amazon Root Services - Route 53
I successfully purchased a domain name. It is project-260-camille. I was able to connect my IP address to the domain name.

## HTTPS, TLS, and Web Certificates 
Using Vim I was able to ssh into my server and create a secure domain.

# HTML Original Deliverable 
I created the four main pages of my application. I used several different HTML tags. I learned a lot about how to use GitHub. I also learned how to deploy to my server. 

# HTML Deliverable (Rewritten)
For this deliverable I built out the structure of my application using HTML.

 HTML pages - Four HTML pages that represent the ability to login, look at feed, edit their profile, and chat with others.
 Links - The login page automatically links to the feed page. The other pages are linked in the Nav bar.
 Text - Example feed is given in Lorem Ipsum.
 Images - Placeholders for images were added.
 DB/Login - Input box and submit button for login. Profile information is also kept on Database.
 WebSocket - Placeholders for the chat section were added.
