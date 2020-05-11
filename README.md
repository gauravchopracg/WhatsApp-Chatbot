This project aims to illustrate how to build a chatbot for WhatsApp using the Twilio API for WhatsApp and the Flask framework for Python.

![recognized_example.png](https://github.com/gauravchopracg/WhatsApp-Chatbot/blob/master/Output/example.png)

## Requirements

The following installation has been tested on MacOSX 10.13.6 and Ubuntu 16.04.

This project requires **Python 3**, a smartphone with an active phone number and WhatsApp installed, a [Twilio account](http://www.twilio.com/referral/7fB3Je) and the following Python libraries installed(plus a few others depending on task):

- [Flask](https://palletsprojects.com/p/flask/)
- [ngork](https://ngrok.com/)

1. Clone the repo

```bash
git clone https://github.com/gauravchopracg/WhatsApp-Chatbot.git
cd WhatsApp-Chatbot/
```

2. Install Dependencies
```bash
pip install -r requirements.txt
```

3. Configure the Twilio WhatsApp Sandbox
From your [Twilio Console](https://www.twilio.com/console), select Programmable SMS and then click on WhatsApp. Now, from your smartphone send a WhatsApp message with the given code to the number assigned to your account.
![recognized a3Dg7ccP5QFcnxWM6N0kmUDk7VqvuL5M538UfEg-yxMc2r.width-500.png](https://twilio-cms-prod.s3.amazonaws.com/images/a3Dg7ccP5QFcnxWM6N0kmUDk7VqvuL5M538UfEg-yxMc2r.width-500.png)

4. Testing the Chatbot
```bash
$ python bot.py
 * Serving Flask app "bot" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
Open a second terminal window and run ngrok http 500 from the folder where you have downloaded [ngrok](https://ngrok.com/)
