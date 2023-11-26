# WHAT IS QUIZZICAL ?


Introducing Quizzical, the web-based quiz game that challenges your knowledge and keeps you on your toes! Join the fun and see if you have what it takes to be a trivia champion. Get ready to quiz, compete, and unravel fascinating facts! 


# Features of the quiz app


- Home page/quiz page


- Quiz has questions and any question with answers, any answer you press on is saved as your answer.


- When you finish the quiz, you get a score and you see which questions you answered correctly, and if you answered incorrectly the correct answer is displayed. Also the "check answers" button switches to the "play again" button, so you can start a new quiz.



# How I Created The App


- I used useEffect() hook, to put API data into state and deal with side effects


- I used useState() hook, to updating state objects with nested arrays of objects


- I used conditional rendering to conditionally display the homepage/quiz page and also for buttons


- I used *Nanoid* dependency to have a unique id to keep track of all questions and answers.


- I used *He* dependency to decode html entities into readable text. This was necessary because the API data for the questions and answers had html entities. 


- I created a pixel perfect design from the mock up I received in a Figma file. I also made sure the design was responsive for any screen size.




# What I learned


- I strengthened my fundamental React knowledge with this project.


## How to run ?
    

      npm install
      npm start



# SCREENSHOTS 


Main Screen 


![Screenshot 2023-11-26 212353](https://github.com/Sandhiya-S5303/ReactApp-Quzzical/assets/110396890/4fb3e3f1-7eb0-4927-855a-89336bc87876)





Quiz Page


![Screenshot 2023-11-26 212504](https://github.com/Sandhiya-S5303/ReactApp-Quzzical/assets/110396890/55c8c125-fe64-4fe9-a74b-a0e4eb0c3ef1)




Quiz Page - After Answered


![Screenshot 2023-11-26 212339](https://github.com/Sandhiya-S5303/ReactApp-Quzzical/assets/110396890/7e1f9712-40ca-4c36-a7f2-677451b2ad1c)



