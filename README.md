# Foodiebear Pet Feeder (Part III. Alexa Skill)

## 1. Project Overview
Foodiebear PetFeeder helps pet owners to stay connected with their loved ones whenever, wherever. This project includes a DIY pet feeder powered by raspberry pi, a MERN web app powered by Azure cloud platform, and an Alexa skill powered by AWS. Whether your pets need to be fed breakfast before you wake up, dinner while you're working late, or simply a treat when you are busy in the house, you should stay tuned to this awesome project :dog::cat::panda_face:

To learn more about this project, please read the initial product plan [here](https://gist.github.com/rinostar/a79a67ce073be1d7e5be2e4a55bb714e) or the final architecture diagram below:

<br />![Foodiebear](https://user-images.githubusercontent.com/52188117/72955297-63148f00-3d93-11ea-8377-74b722fa7012.png)

## 2. Repo Description
This is the Alexa Skill part of the FoodieBear Pet Feeder project. This repo contains the python code for Lambda function and resources to use Alexa Developer Console.

## 3. Getting Started

### a). Alexa Developer Console:
https://developer.amazon.com/alexa/console/ask
<br />NOTE: Be sure to use the same email address for your developer console and your alexa. After deployment within the console, the new Alexa skill will be available on your Alexa device automatically. Thanks, Alexa.

### b). Code for Lambda Function:
Please refer to the "foodiebear_lambda.py" file in this repo
<br />NOTE: Be sure to update the web address to your Azure app on line 54 `$ r = requests.get("https://foodiebear.azurewebsites.net/api/feed")` 

## 4. Other Repos:
* Part I. Hardware & Raspberry Pi: https://github.com/rinostar/capstone_petfeeder
* Part II. Web App & Azure Cloud: https://github.com/rinostar/capstone-petfeeder-app

## 5. Author & Contact
Github: [@rinostar](https://github.com/rinostar)
<br />Email: codingrinostar@gmail.com

## 6. Acknowledgments
In addition to authors of the links mentioned above, I want to thank: 
* [diy petfeeder](https://www.youtube.com/channel/UCnDOhfA1Y8OODhTrmgLJAcg) on Youtube for the inspiration,
* [redklouds](https://github.com/redklouds) on Github for the collaboration, 
* and [Ada](https://adadevelopersacademy.org/) community for the support.

Thank you! Until next time 🌟
