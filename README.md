# A Developers Guide To Galaxy Of Success
### From an idea to a fully working product - agile project management guide/vision

This project is for sketching out somekind of succesful project management guide/instruction/template/cheatsheet/process/way of doing things from start to finish, you name it. At least for me it has always been kinda hard to know how to start a project, what are the first steps to take, how to proceed with a plan, what agile actually is, how to deal with the customer, how to finish the final and product and deliver it to production. The coding part which lies somewhere in the middle is the most "easiest" part I think. But come up with somekind of plan and actually know what we're doing/we're are we going is the trickiest part. 

This thing is going to evolve a lot, hopefully as time passes, while I can find good resources, have aha moments, and have a nice talks with people. Hopefully I can come with somekind of easy to digest, high level concept that I can use and share in future endeavours.

<hr />
This first draft is heavily based on to this wonderful article about creating a JS app from a scratch:
<https://medium.com/ladies-storm-hackathons/how-we-built-our-first-full-stack-javascript-web-app-in-three-weeks-8a4668dbd67c>
<hr />
## Table of contents
* [Step 1: Ideate/brainstorming/QA](#step1) 
* [Step 2: User stories (the features)](#step2)
* [Step 3: Domain model (the business)](#step3)
* [Step 4: Wireframe UX/UI](#step4)
* [Step 5: Build a proof of concept (POC)](#step5)
* [Step 6: Set up version control](#step6)
* [Step 7: Embrace agile workflow](#step7)
* [Step 8: CI/CD pipeline & environments](#step8)
* [Step 9: Choose & download boilerplate](#step9)
* [Step 10: Code out the features](#step11)
* [Step 11: Choose and code the design scheme](#step12)
* [Step 12: Find and squash bugs](#step13)
* [Step 13: Deploy the live app](#step14)
<hr />
<a name="step1" />
### Step 1: Ideate/brainstorming/QA
- Question: What we exactly want to build?
    - It's the most difficult question
        - You have to remind this for yourself for the whole project lifetime
    - These are the requirements/specs
        - Things that everybody are asking
- Question: To whom you're building the app?
    - Hackathon, home project, no specific idea yet?
        - Gather ideas you’re excited about
        - Maybe a past app you've been thrilled about?
        - Post it brainstorming strategy
            - Scribble out as many ideas as you can
            - Even ”stupid” ones
                - Brains keep moving
                - Voicing ideas out of fear
                - Never fear opening your mouth to say something
        - Sort ideas to categories
            - You will find themes
            - Find connections between them and you may have an high level idea of the app?
    - Real customer
        - Has some kind of vision?
        - Have a QA meeting
            - What the customer really wants?
                - Usually they don't know it
                    - Only a big picture
            - Listen to the customer and write down features
                - Gain user stories/use cases
                - Ask question, a lot
                - Propose your own thoughts also
            - Listen to the nouns customer is using
                - You might find domain entities
            - Ask what are the most important features they want to have on it?
                - Plan MVP
                    - Maybe not in the first QA
            - Repeat

<a name="step2" />
### Step 2: User stories (the features)
- Write down user stories
    - These are the features of the application
- Naturally the first ones might be epics (long user stories)
    - Try to crush em` down
        - Put user stories under epics
        
<a name="step3" />
### Step 3: Domain model (the business)
- Based on user stories, create domain model
    - A list of entities and their attributes
- Find and form relationships between the entities
- Find business rules

<a name="step4" />
### Step 4: Wireframe UX/UI
- Draw raw basic view(s) of the app
- Incorporate user stories so you can understand how the views work
- If possible, make friends with a designer or hire one or ask your boss to hire one

<a name="step5" />
### Step 5: Build a proof of concept (POC)
- Create proof of concept of the most difficult fundamental features of the app
    - This demonstrates that the it can actually be done

<a name="step6" />
### Step 6: Set up version control
- Set up Github/etc. repo for the code
    - Prevent merging to master
    - Force reviewing each other's code
        - Code review
    - Create git branches from user stories
    
<a name="step7" />
### Step 7: Embrace agile workflow
- Stay organised by practicing agile development
    - Scrum
        - If you know what to do next two weeks
    - Kanban
        - You're not sure what is coming up
- No need to follow any strict style of doing things
- Create agile board
    - A real whiteboard
    - Use tools if necessary
- Create backlog
    - List milestones (sprints, MVP, production ready etc.)
    - List themes (A collection of related user stories)
    - List epics (large user story)
    - List user stories
        - Tasks underneath them
            - In Github you can list tasks to do with checkboxes
        - Split user story for frontend and backend
    - List bugs
    - Other things to do
- Have an "icebox"
        - A column for future features, wacky ideas
- Hold stand-up meetings
    - Have discussion about
        - Previous day's progress
        - Encountered blockers
        - What to do next
- Prioritise prioritise!
    - It's important to proceed with the most important things

<a name="step8" />
### Step 8: CI/CD pipeline & environments
- Have CI/CD pipeline right from the start
    - Automatic builds
        - Tests
        - Code analysis
        - Deployments
- Create dev/staging environments where you can demo your progress with the app

<a name="step9" />
### Step 9: Tools & frameworks
- Choose tools & frameworks for the project
    - Try not to reinvent the wheel

<a name="step10" />
### Step 11: Code out the features
- It's coding time!
- Start implementing the functionality of the app
    - Pick a user story
    - User wireframe/design as your guide
    - If any questions, collaborate with the customer
- Don't forget to do tests!
    - TDD, BDD
    - Unit tests
    - Integration tests
    - End to end tests

<a name="step11" />
### Step 11: Language support, texts, content
    - Who decides the UI texts
        - Labels
        - Warning
        - Alerts
        - Content in general
    - Centralised lang file?
    - Create a service?

<a name="step12" />
### Step 12: Choose and code the design scheme
- When the MVP of the functionality is done, clean it up and make it look nice!

<a name="step13" />
### Step 13: Finalizing
- Fix bugs
- Try to simulate every user flow
- Might not be the most systematic phase
    - Switch to Kanban?

<a name="step14" />
### Step 14: Deploy the live app

## Tips
- If possible always try to work something/progress and then gain feedback. It’s better to have something to work with and make better than a blank paper
- You cannot refactor if there is no tests
    - Fear of braking up things
    - This would be ideal
- Unawarness is your worst enemy
- Embrace: app first, tech second

### Recources
- Example user stories:
    - ability to create new goals, milestones, and checkins
    - ability to delete goals, milestones, and checkins
    - ability to change a timeline’s name, color, and details
    - ability to zoom in on timelines
    - ability to add links to resources
    - ability to upload media
    - ability to bubble up resources and media from milestones and checkins to their associated goals
    - rich text editor integration
    - user signup / authentication / OAuth
    - popover to view timeline options
    - loading screens
