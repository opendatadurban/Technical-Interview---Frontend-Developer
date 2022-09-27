# Open Cities Lab
## _Technical Interview - Frontend Developer._

You are given the task to solve the artwork photo frame challenge. 
To submit your solution, you can either:
- email us your solution in a zipped folder, or
- push onto GitHub and send us a link to your repo.


## Objective
This practical assessment is intended to show us that:
- You have the ability to write clear documentation.
- Code and component reuse/extensibility.
- The tools of choice to solve the problem.
- You understand the requirements from the information provided.

The assessment takes around 3 days. We will set up another session to go through what you have done.

## Background

You bought a smart frame that can connect to the internet, and you want to use it to show artwork in your house.

Using Javascript or Typescript as the frontend, your task is to create an inter-active website that displays artwork that you pull from the Metropolitan Museum’s API. You can choose any framework to help you build the website.

## Assignment
- The website should change artworks every 10 seconds
- When tapping on an artwork, display additional information about the artwork
-- When displaying the art information, the timer should stop
- Build the frontend with the templating language that is included with the framework. If you’re not using a framework, or the framework does not include a templating language, you are free to use any library of your choice
- Make it responsive using your best judgement.

## MetMuseum API

- For this challenge, you should use the Object and Objects endpoints. They are both listed at https://metmuseum.github.io/. The Objects can be used to get valid Objects IDs to use in the Object endpoint.
- You can also go beyond and use the Departments and Search endpoints to make the artworks selected more thematic, but this is optional.

## Evaluation Criteria
- JavaScript/ES6 best practices
- We’re looking for you to produce working code, with enough room to demonstrate how to structure components in a small program
- Completeness: did you complete the features?
- Correctness: does the functionality act in sensible, thought-out ways?
- Maintainability: is it written in a clean, maintainable way?
- Testing: is the system adequately tested?
- Beware of failed requests to the API. What should the page show if the request fails?
- When to download the next image? Should I download after the timer or during the timer?
- Be careful with the image display and its resolution
