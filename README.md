# what2eat

"what2eat" (stylized in all lowercase, with "to" stylized as the number 2 to make the name of the application both easy to remember and unique) is a very simple food application that is designed to give users an idea of what they want to eat. This project is being done in accordance with Saint Leo University's Mobile Application Design class.

# Detailed Description

This section will serve to better explain the application and how it will work, or at least the design plans for this application. While I would like for this application to be fairly advanced in what it searches, including being able to pinpoint restaurants, grocery stores, and fresh markets near the user using a GPS system, I do not currently have the technological know-how to make this happen. For that reason, this application will suggest different foods and where one might be able to find them. For example, if the application determines the user wants a burger, it will suggest buying the ingredients for that meal from a nearby fresh market, grocery store, or suggest going to a fast-food restaurant such as McDonald's, which can be found in most locations.

# How It Works

How this application will work is retrieving a food suggestion based on a few different options that will be given to the user. Each of these options will be explained below. It should be noted that while this application is still in these early stages, each option will only support a few possible choices, even though the user will be able to enter in their own data in each field.

// Option 1 - Preferences 

This option refers to what the user likes to eat in general, such as their favorite foods, or things that they never get tired of. While the application serves to present new options, this can help in knowing the general flavors that the user likes to eat.

Preferences will only have a few options in this stage of the application:

- Pizza - related to "Italian food"
- Burgers - related to "American food"
- Noodles - related to "Chinese food"
- BBQ - related to "Southern food"
- Seafood - related to "Japanese food"

Each of these relations will help determine what kind of food the application retrieves. These relations will be explained more later on and will exist within a database. These relations are the backbone of the application and control how it works.

// Option 2 - Cravings

Cravings are what sorts of flavors sound good. This is sort of hard to explain, but it becomes much clearer when one sees a sample database. This option serves to narrow down what the user might be interested in eating.

[Spicy]
- if "Chinese food" then "Kung Pao Chicken" or "Spicy Fried Rice"
- if "American food" then "Jalapeno Cheeseburger" or "Stuffed Peppers"
- if "Italian food" then "Penne Arrabbiata" or "Caprese Salad"
- if "Southern food" then "Ghoulash" or "Spicy Collards"
- if "Japanese food" then "Japanese curry" or "Spicy tofu"

[Sweet]
- if "Chinese food" then
- if "American food" then
- if "Italian food" then
- if "Southern food" then
- if "Japanese food" then

[Sour]
- if "Chinese food" then
- if "American food" then
- if "Italian food" then
- if "Southern food" then
- if "Japanese food" then

[Exotic]
- if "Chinese food" then
- if "American food" then
- if "Italian food" then
- if "Southern food" then
- if "Japanese food" then

// Option 3 - Allergies

Allergies are perhaps the most important option. Simply put, this option will eliminate any food options that would possibly set off that person's allergies, or at least provide a warning that they may contain allergians if they are cooked in a certain way or obtained from a restaurant.

# The Problem Being Addressed 

The problem this application aims to address is that many people cannot decide what they want to eat. Maybe they wish to try something new, or they are simply just unable to pick between the options they have available to them. This application will help with that by obtaining a list of options that would help the user pick what they wanted to eat.
     
# Platform

This application is being developed for Android.
      
# Front/Back end support

The front end of the application will likely use multiple design and markup languages in order to make it more presentable, including HTML, CSS, and JavaScript. It will also require web performance and browser compatibility, and all of this will need to be tested for usability and accessibility before the publishing of the application.

The back end of the application will most likely be written in a language such as Python or Java for a couple examples of ones that may be used for this. Python is currently preferrable. This portion of the application will also need to address network scalability and availability, as well as database management, transformation, and backup. Possible, the back end of the application also needs to include GPS.
     
# Functionality

This application is not currently being designed to support GPS, though this is the intended future for the application. Currently, it is a simple search application that suggests a variety of generic dishes to the user. The application currently goes out of its way to mention certain brands, as those may not be currently available to the user. For this reason, when considering functionality, the application does not actually give the user a precise suggestion but rather an idea for a suggestion. For example, it will not mention TGI Friday’s, but it will mention a cheeseburger, with a list of possible ingredients. These ingredients are also currently not named by brand, as the user may not have those brands available to them and may prefer an alternative anyways.

Until GPS is implemented, this is mostly a gimmicky application that serves to waste some time and have fun doing so and will get downloads from this idea. It may help somebody actually get an idea for what they want to eat but will not be able to do a great job of this until GPS is implemented.
      
# Design (wireframes)

Located within a seperate post.
