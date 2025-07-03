# SalesLift
Turn your website into a 24/7 sales engine.  
**Launch in days, see revenue next week.**

## Why SalesLift?
- **Clear ROI:** Pages optimized to capture leads and convert traffic.  
- **No jargon:** Built for owners, not developers.  
- **Fast launch:** From zero to live in < 72 hours.

## Getting Started
1. Clone this repo.
2. Run `npm install && npm run dev`.
3. Edit `index.html`, push, and profit.


## env variables
# Follow this url to create your reCAPTCHA https://www.google.com/recaptcha/admin/create
RECAPTCHA_SECRET_KEY=<YOUR_RECAPTCHA_KEY>

# Namecheap Private Email SMTP. Ask chat gpt for help creating a Namecheap account buying a domain and getting private email 2 months free. Ask for help setting up DNS records and MX records for SMTP. Keep SMTP_HOST and SMTP_PORT the same as below. 
SMTP_HOST=mail.privateemail.com
SMTP_PORT=587
SMTP_USER=<YOU@YOURDOMAIN.COM>
SMTP_PASS=<YOUR_EMAIL_PASSWORD>

# Vite Vanilla Server
# Type this into the terminal, it updates your server with changes you've made to your files. 
npm run build
# I prefer preview but choose either one, they start your server and allow you to connect from any IP.
npm run dev -- --host 0.0.0.0 --port 5173
npm run preview -- --host 0.0.0.0 --port 4173


# Depending on your choice above, replace your vm's external ip below and then paste the full https url into the search bar after you've started your server. 
http://<YOUR_VIRTUAL_MACHINE_EXTERNAL_IP>:5173
http://<YOUR_VIRTUAL_MACHINE_EXTERNAL_IP>:4173

#reCAPTCHA
SITE_KEY=<YOUR_RECAPTCHA_SITE_KEY> 
SECRET_KET=<YOUR_RECAPTCHA_SECRET_KEY>


#Inside of index.htmll 
replace <YOUR_RECAPTCHA_SITE_KEY> with the value of SITE_KEY

#Inside of api/contact.js
replace <YOU@YOURDOMAIN.COM> with the value of SMTP_USER


#logo
paste your public/logo.svg file into chat gpt and ask it to generate a logo of your choice. 

# HELP
Reach out to me on telegram or instagram if you need help

