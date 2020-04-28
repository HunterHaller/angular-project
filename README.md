# Creative Project: AngularJS

This is an project exploring the use of AngularJS. This tech is not as modern or advanced as its newer sibling, Angular, but I didn't realize the difference before I started learning AngularJS and didn't have time to switch.

The project is a simple quiz, inspired by a flood of quizzes going around the internet from uQuiz. It demonstrates AngularJS's capabilities from creating dynamic pages and Single-Page Applications.  The page uses multiple loaded pages to create different views without reloading the page. It also has divs that only spawn when inputs have been filled and also fill in parts of text based on that input.

Where this ended up going wrong was that I wanted to have the results page be unique based on the answers up that point, but AngularJS does not allow for $scope to persist across views, so all the info is lost as the quiz progresses and nothing is saved by the results page. I'm sure that there is a way to accomplish this, but I didn't find it this time.
