# cutetherapy
A service to automatically send pictures of dogs/cats/foxes/memes over SMS and Email. 

## Group Members
- Shane LeBlanc
- 
- 
- 

## Project plan
Allow users to enter their phone number or email address and then select what images they would 
like to recieve via checkboxes and dropdowns from Dog.ceo API and thecatapi.com API (and other 
APIs if possible). The user can then select an interval and then automatically have this picture 
sent to them. 

## Project specifications
- Mailgun API or Postfix mail server
- Textbelt SMS server, Twilio API or other SMS API
- Django for web framework
- PostgreSQL for database (users, settings)
- Dokku container / NGINX web server on VPS 

## Challenges and Unknowns 
- What will the picture size and file size be? Will we run into problems with file size limits? 
How will it look? 
- Are we sure the images from the databases will be cute? How cute should they be, precisely? 
The cuteness should exceed a minimum threshold of induced happiness upon viewing, preferably. 
- The APIs will give back data in JSON and XML. Use python libraries to parse. 
- Will SMS APIs be free, and if not, how realistic is the TextBelt free server? 
- How to prevent abuse? 

## Group roles 
### Shane LeBlanc - Back-end & API Engineer 

 
