# Teach-Yourself-Day
This is my Repo for my teach-yourself-day at GA.

Why did you choose this subject?
- I chose this subject by looking on indeed.com and trying to see trends of skills Jr. Developers must have. Jenkins was one 
  of the most popular that I saw.
  
  What problem does it solve?
  - Jenkins solves problems with moving from development stage to production stage in half the time.
  
  What are the alternatives?
  - There are alternatives to Continous Integration (CI) one example would be called "Nightly build and Integration" this is     where you wait till a certain time (usually at night) to integrate all the changes and run your code to make sure it is     not broken or have bugs.
  
 What is it similar to, if anything?
 - Jenkins is similar to Bamboo, BuildBot, Apache_Gump and Travis CI. These are all CI tools for different programming          languages.
 
 What is your opinion on the technology after having built something with it?
 - My first impresstion is that this tool can be very useful but my only concern would be to understand how Jenkins worls      outside of Java.
 

To understand Jenkins you must first understand how we Integrate our code currently...

   As developers we usually write code and submit it into a repo. Imagine if multiple developers are submitting to the same repo it can get very difficult... Even more imagine if one developer is in India and another in Canada and you are here in DC and all of you are working on the same repo. You will most likely run into Delays in testing, integration issues andthere would most likely be bugs in your code if you guys arent careful enough. Because of the difficulties of communication youare left in what I would consider devolpment hell, as everyone will most likely be pointing finger at each other because of the issues.The bottom-line is that whatever project you are working on will be DELAYED!

  Jenkins is a Continous Integration Tool (CI) and I like to think of it as a seperate branch where you are able to continously commit any of your changes to a server where it will be tested. This will allow you to be able to continue working... knowing that your code works and wont have to wait till someone that may not be on your time schedule commit and possibly mess up the build. Also this saves you time by not having to run your test locally which will take up a lot of time as well.
    
  Jenkins is currently open source, meaning there is and will be constant updates and it will continue to get even better in the future. Jenkins was initially created to be compatitible with code being writted in "Java".I have found out that there is a way to use Jenkins with other programming languages (ex. Node.js) but that will require plugins and in some cases running Jenkins on different cloud servers. Jenkins currently does NOT allow multiple programming languages at once... So if you are writing Java every developler on that Jenkins repo must write Java with you. The only workaround is to have multiple versions of Jenkins running for every language build you would want to have.

