# SMS-Booking
SMS booking System with Twilio and Node.js


## Build a complete SMS booking system using Twilio and Node.Js that receives and send messages to create a new appointment &nbsp;


[Learn more about Twilio here](www.twilio.com/referral/eCplne)&nbsp;

Twilio the world's leading cloud communications platform as a service (CPaaS) that enables you to develop SMS solutions, WhatsApp, Voice, Video, email, and even IoT. Twilio powers communications for more than 190,000 businesses and enables nearly 932 billion human interactions every year.
This course will leverage some of those capabilities to create a fully functional SMS booking system. Here is how it works, the customer interested in booking an appointment send an SMS to a Twilio number; our Node.JS backend application understand the message and send an SMS back to the customer saying:

Hi, do you want to book an appointment to:

\*see the gym

\*book a personal trainer

\*book a massage

After that, we wait for a user reply, such as:

I want to book a massage

After that, our Node application will send an SMS to the user asking:

What date do you want to see the masseur

The customer will reply with a preferred day, such as:

Monday, please

In this case, we will reply with the valid times available on Monday

Do you want to book it on Monday: 10 am, 11 am, 1 pm or 4 pm

After the customer selects the best time for the booking, they will reply saying:

At 11 am is good for me

After collecting all the data, the NodeJS application will send a confirmation to the customer saying:

Your appointment is booked to see the masseur on Monday at 11 am. See you than


