# 🥘 ["ReDI to Find"](https://reditofind.netlify.app/)

This was a final project at ReDI School's React Course. The goal of this project is to create a React App that helps Berliners 🇩🇪 connect to local restaurants that are open during the pandemic. Students are implementing and practicing the concepts that they've been learning during the semester including: routing, local & global state management, hooks, lifecycles & styling.

## 💁🏻‍♀️ Features

- [x] Users are able to view the list of all restaurants that are returned from the API
- [x] Users are able to check restaurants with specific categories/tags
- [x] Users are able to use filters(service type, cuisine, dietary cuisine)
- [x] Users are able to click a restaurant card on the restaurant listing's page to check the details

## 📃 Project Status

This project is currently deployed via Netlify.

![mockup image of the project](https://i.imgur.com/4c9jweN.jpg)

## ☑️ Installation and Setup Instructions

Clone down this repository. You will need `node` and `npm` installed globally on your machine.

to install dependencies

```
npm install
```

to run the application

```
npm start
```

to visit the App:

```
https://reditofind.netlify.app/
```

## ⚒️ Technologies

- framework: React.js
- routing: React Router
- global state management: Context API
- data fetching: RESTful API
- styling: Styled Component

## 💡 Reflection

It was my first time trying dynamic routing and there was an error that I didn't expect. Later I found out it is something called  ['race condition'](https://sebastienlorber.com/handling-api-request-race-conditions-in-react). Even though I somehow managed to fix it within the timeline, I could not understand both the error and the solution and I felt very frustrated. Then I had a feedback session with one of my React teachers, told him about the issue and he gave me another solution, which is actually almost the same as the one I fixed with, then suddenly everything made total sense and felt natural. It was one of the powerful 'A-ha!' moments 🌼 and I loved it.

Another obstacle was about dropdown buttons. I was aware of the possible styling limitation to use plain HTML `<select>` tag, so I tried to make 'customized' dropdown buttons, which turned out to be a big mistake. First of all, it took a lot of time, and second of all, it was difficult to integrate with onClickOutside. After I spent the whole day struggling, I found out the easy way: react-dropdown. I deleted all the redundancies right after and started fresh again with the beautiful, smart, and easy dropdowns.
  
I remember the first class of the React course. Even though I tried to be positive, I could not help but feel nervous and insecure. It seemed like I understood only 30-40% of the class and had no idea how to catch up on the curriculum. But I am a persistent person. Yes, I sometimes tend to be anxious but I am no quitter. I joined the mentoring program, did a lot of extra self-learning, reviewed all the classes. Even when all my teammates left the team due to their personal matters at the beginning, I successfully finished the project within the given timeline. I got good feedback from the teachers, had a chance to give a presentation at a ReDI School's Big Demo Day. I represented the course, gave a demonstration of the project, and shared my thoughts. I am no the most generous person to myself but I want to say I did great for the past four months and am so proud of myself.
<br />

✍🏼 READ MORE HERE: [7 Things I've Learned During the Time at a Coding Bootcamp](https://medium.com/p/7-things-ive-learned-during-the-time-at-a-coding-bootcamp-d402f4504e4a?source=email-5afa1b1ccaf0--writer.postDistributed&sk=7ccc18a87c1049b9088274404eb8288a)
