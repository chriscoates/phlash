# Phlash
![icon](http://i.imgur.com/Hpd3YgW.png) ![main](http://i.imgur.com/0BaY523.png) ![phlash](http://i.imgur.com/3P3he6l.png)

Phlash is a photo-messaging iPhone app that encourages spontaneity. Swipe right to capture an image and immediately send it to your phollowers. Swipe left to see phlashes sent by the people you're phollowing. No liking, commenting, sharing - see the phlash while it lasts!

## Authors

Phlash is the idea of a group of [Makers](http://www.makersacademy.com/) as its final project. The Kings and Queen of Phlash are:

 * [Chris Coates](https://github.com/chriscoates)
 * [Sergio Enrech Trillo](https://github.com/tigretoncio)
 * [Ollie Haydon-Mulligan](https://github.com/ollieh-m)
 * [Amy Nicholson](https://github.com/missamynicholson)

## Usage

The code is available to download from this repo, and as of 24-June-16 the app has been approved by Apple, so it is now ready for Beta testing. If you would like to beta test the app, please send and email to phlashapp@gmail.com or [check here.](https://phlash.herokuapp.com/)

## Technologies

Phlash has been developed for Apple devices, (iOS 9.0+), using XCode 7.3.1 and Swift 2.2. The backend service is provided by Parse and uses CloudCode, implemented in JavaScript, to secure user data and exchanges.  

The app has been also tested on IoS device as old as 7.0, although some compatibility issues have been experienced when retrieving pictures. For best user experience iOS 9.0 is recommended.

## Challenges

This is an amazing team. Not having enough with being challenged during 4 months coding like crazy in Ruby and Javascript, the PHLASH team decided they wanted to know how to develop a *"Phlashy app"* to show how much they could learn in very little time, (exactly 12 days), so they could share pics of [Dougal the Poodle](http://i.imgur.com/0pCDeFB.png?1), [Mabel](http://i.imgur.com/ZI8mXE7.jpg), the notorious [Sergio's neighbour cat](http://i.imgur.com/e6TL1Sr.png), or even [the mother duck-er](http://i.imgur.com/aTSMhz9.png)

None of the team knew about Swift before the start of the project, although Amy was a bit familiar with Xcode.  To make matters even more interesting, some of the members hadn't used a Mac in their lives before this project! (Sergio, we know who you are!)

We took a day to evaluate different mobile technologies, and we decided to go for Swift. Then, the challenge was to learn enough Swift and relevant tools (XCode and Parse) to create our app, and do it fast.

Another challenge was to decide features we wanted for the app, and oversee the deployment using Agile practices. We heavily relied on [Github](https://github.com) and [Waffle](https://waffle.io) to project manage the app development.

Also using a TDD philosophy was challenging as we needed to understand the programming language and its test framework in order to create relevant tests driving the app development, for that we spent another 2 days making a "spike". TDD-ing in XCode was another interesting challenge, but that's probably another story and we could write a trilogy with it...

## User Stories
```
As a phalsh user
So that I can use the app
I want to be able to signup
```
```
As a phalsh user
So that I can user the app again and again
I want to be able to login
```
```
As a phalsh user
So that no one can send a phlash on my behalf
I want to be able to logout
```
```
As a phalsh user
So that I can send a phlash to my followers
I want to take a photo
```
```
As a friendly phlashee
So that I can view someone's phlashes
I want to be able to phollow them
```
```
As a phlashee
So that I can see a phlash from someone I'm phollowing
I want to be able to view their photo
```
```
As a phalsh user
so that I can know who is phollowing me
I want to get a notification when somenone starts phollowing me
```
```
As a phalsh user
so that I can know when my friend creates a phlash
I want to get a notification when someone I am phollowing phlashes
```
```
As a phalsh user
So that I can protect my modesty
I want to limit how long my phollowers see my phlash
```
```
As a phalsh user
So that I can see my phollowers’ phlashes
I want to get a notification when someone I’m phollowing creates a phlash
```
```
As a phalsh user
So that I can view less phlashes
I want to be able to unphollow a phlash user
```
```
As a phalsh user
So that I don't get locked out of my account
I want to be able reset my password
```
```
As a phalsh user
So that I can communicate fully
I want to add a caption to the phlashes I create
```
```
As a phalsh user
So that I can be in the know
I want to know if there are pending phlashes for me to view
```
```
As a phalsh user
So I know who the phlashes belong to
I want to know the sender of each phlash
```
```
As a phalsh user
So that I enjoy using the app
I want the phollow page to be animated when it appears/disappears
```
```
As a phalsh user
So that I accurately guided through the app
I want to have alerts with info on main events
```
```
As a developer
So that no malicious users access the backend functionality
I want to move some of the Parse calls up into Cloud Coded
```
```
As a developer
So that the app has sensible limits
I want to have authentication text field validations for usernames, emails and passwords
```
```
As a developer
So that my app has sensible limits
I want to ensure that caption does not exceed the limits and fits nicely in the screen
```
```
As a phalsh user
So that I can create a meme style phlash
I want to be able to position my text in the taken phlash
```
```
As a phalsh user
In order to increase the app usability
I want the keyboard to be dismissed from the Auth view in the relevant ways
```
```
As a developer
So that I have cracking app
I want to present the sender label in a cracking way
```
```
As a developer
So that my application is efficient in database queries
I want to check the database only if there is not photos locally to show
```
```
As a user
So that I want to use the app over and over
I want to have a fancy app design
```
```
As a developer
So that my user can't misuse the app
I want to temporarily disable buttons and swipes after use to prevent double tapping/swiping
```
```
As a developer
So that my app works smoothly
I want to validate the user I am trying to phollow exists before adding the relationship to the database
```
```  
As a developer
So that users use the app appropriately
I want to ensure I can't phollow someone twice
```  
```
As a phalsh user
So that I know how to use Phlash
I want to be able to access a help screen with instructions
```
```
As a phalsh user
So I only see unique images
I want to see all the new images of my phollowees since the last time I checked them
```  
```
As a phalsh user
So that I can send my selfies
I want to be able to choose between front or rear camera to take my phlash
```  
```
As a developer
So that all the usernames of phollowees are standard
I want to validate that field and ensure no capital letters, less than 15 chars and no symbols are allowed
```  
```
As a phalsh user
So that I can edit my list of people I follow
I want to be able to unphollow a person
```  
```
As a developer
So that the app is appealing
I want to have a phlashy design
```  
```
As a developer
So that my app is widely distributed
I want my app to be run in many different iOS versions, (from 7.0 to 9.0)
```
```
As a developer
So that I can type instantly
I want the keyboard to start with lower cases
```

## To Do
- Manage list of Phollowers
- Create videos
- Geolocalise phlashers and show them in a map

## Detailed plan
Our detailed plan is [here](https://www.youtube.com/watch?v=LfmrHTdXgK4).
(probably the best detailed plan ever, don't miss it :))
