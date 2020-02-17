# Devating : Back-end

## Project Overview

Do you think pair programming can be romantic? YES!! We’re introducing the next generation of pair programming - a new level of connection. Devating is a matching dating app for developers based on their coding preferences, where there are no pair partners left behind. This is the back-end planning and you can view the front-end planning [here](https://github.com/jadekang0611/devating-frontend/tree/master)

## Team Members:
- Scrum Master: Jade Kang (certified)
- Project Manager: Daisy Yau
- UI Designer: Sage Kearney
- QA Engineer: Abdul James

## Table of Contents:
- [User Stories](https://github.com/jadekang0611/devating-backend#user-stories)
- [Wireframes](https://github.com/jadekang0611/devating-backend#wireframes)
- [Planning](https://github.com/jadekang0611/devating-backend#planning)
- [Technologies](https://github.com/jadekang0611/devating-backend#technologies)
- [Installation](https://github.com/jadekang0611/devating-backend#installation)
- [Usage](https://github.com/jadekang0611/devating-backend#usage)
- [Testing](https://github.com/jadekang0611/devating-backend#testing)
- [UX Modifications/Hurdles/Unsolved problems](https://github.com/jadekang0611/devating-backend#ux-modificationshurdlesunsolved-problems)
- [Future Add-ons](https://github.com/jadekang0611/devating-backend#future-add-ons)
- [Contribution Guidelines](https://github.com/jadekang0611/devating-backend#contribution-guidelines)
- [Credits](https://github.com/jadekang0611/devating-backend#credits)

## User Stories:

**Our Users:**
- Age: 20 - 50
- Gender neutral
- Flirty & fun, yet mature
- Typically anti-social, keep to themselves

**Why are they using our app?**
- They want to meet people like them, think the same way, have similar experiences 
- Want to destress from a long day of coding
- Find a new ‘pair partner’
- Meeting them(our users) where they are- on the computer! -easy access

**How can our app give our users the best experience?**
- They want to feel accepted- don’t feel guilty for being a nerd aka loving coding
- Mainstreamed/efficient/quick set up
- Bug free
- Super user friendly, easy to use
- #Nostrainonthebrain
- Image front and center with name, age, job title
- Mobile: swipe functionality?
- Browser: buttons (see Jade for button idea later) 
- Simple, concise summary/profile thingy
- No strings attached coding

**What are they doing in our app? What is their main activity?**
- Meet someone new with same interests
- Browsing, looking for a loving (friendly) pair programmer.
- Reading about other people.

**Ultimate goal**
- Meet somebody & be completely yourself, guilt free, with that person! No need to hide behind your code :) No commiting out! Build a coding relationship. 

## Wireframes:

![devating-wireframe](https://user-images.githubusercontent.com/58707118/74559862-53700c80-4f33-11ea-9172-fe1e3ccd1c62.png)

## Planning:
We review our [Trello Board](https://trello.com/b/K0hAl5co/devating) during daily standup. The board includes project tasks for front-end, back-end, and testing.

We've mainly used the Feature Branch workflow model for back-end. We've collaborated using VS Liveshare creating a development branch then once everything is finalized, we've merged to master branch for heroku deployment.

**Back-end Model**
![Devating Backend](https://user-images.githubusercontent.com/58707118/74598527-13974b00-5041-11ea-8277-b2bfc6f1ed5c.jpg)

```
UserSchema: {
 image: String,
 email: String,
 name: String,
 age: Number,
 gender: String,
 favoriteActivities: [String],
 favoriteCoding: [String],
 genderInterest: String,
 keep: [],
 password: String,
 passwordConfirm: String
}
```

**Bronze version**
- [x] CRUD
    - [x] Create new user account : userController
    - [x] Read user matches based on favorite activities and favorite coding language : matchController
    - [x] Update user matches to user set : matchController
    - [x] Update user information : userController
    - [x] Delete match from user set : matchController
    - [x] Delete user : userController
- [x] One Schema
- [x] Testing: Mocha & Chai

**Silver version**
- [ ] Styling
- [ ] Additional Schema for User Profile page

**Gold version**
- [ ] User Authentication
- [ ] User interaction - to be able to see accepted matches on user dashboard
- [ ] Feature to allow user to have calendar access to book a day for a date


## Technologies:
- Axios
- Node
- Express
- Mongoose API
- MongoDB
- Supertest, Mocha & Chai


## Installation:

## Usage:

## Testing:

## UX Modifications/Hurdles/Unsolved problems:

## Future Add-ons:

## Contribution Guidelines:

## Credits: