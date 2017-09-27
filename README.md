# Route to success 
### From an idea to a fully working product - agile project management guide/vision

This project is for sketching out somekind of succesful project management guide/instruction/template/cheatsheet/process/way of doing things from start to finish, you name it. At least for me it has always been kinda hard to know how to start a project, what are the first steps to take, how to proceed with a plan, what agile actually is, how to deal with the customer, how to finish the final and product and deliver it to production. The coding part which lies somewhere in the middle is the most "easiest" part I think. But come up with somekind of plan and actually know what we're doing/we're are we going is the trickiest part. 

This thing is going to evolve a lot, hopefully as time passes, while I can find good resources, have aha moments, and have a nice talks with people. Hopefully I can come with somekind of easy to digest, high level concept that I can use and share in future endeavours.

<hr />
This first draft is heavily based on to this wonderful article about creating a JS app from a scratch:
<https://medium.com/ladies-storm-hackathons/how-we-built-our-first-full-stack-javascript-web-app-in-three-weeks-8a4668dbd67c>
<hr />

### Step 1: Ideate
- What we exactly want to build
    - Post it brainstorming strategy
        - Scribble out as many ideas as we can, even stupid ones
            - Brains keep moving
            - Voicing ideas out of fear
    - Sort ideas in categories
        - You will find themes
            - From here create user stories
                - Those are descriptions of features we wanted to have
                    - From end-user perspective
            - Maybe first epics then user stories?

### Step 2: Wireframe UX/UI
- Draw ra basic view of the app
- Incorporate user stories so you can understand how the views work

### Step 3: Choose a data structure and type of database
- Based on wireframes and user stories, create domain model, a list of entities and their attributes
- Form relationships between the models/entities

### Step 4: Set up Github and an agile workflow
- Stay organised, practice agile development
- Set up Github repo, prevent merging to master
    - Force reviewing each other's code
- Create agile board
    - List user stories
    - List bugs we need to fix
- Create git branches from user stories/features
    - Maybe too big branches?
- Hold stand-up meeting of previous day's progress and any blockers we're encountering
    - This meeting often decided the day's flow
        - Who is pair programming, who is working issue solo
- Define priorities
- Make efficient progress
    - No interpersonal conflict
- Create CI/CD? Travis CI?
- Language support?

### Step 5: Choose & download boilerplate
- Choose frameworks, tools for the project
    - Try not to reinvent the wheel

### Step 6: Write back-end API routes
- Implement connection from API to the DB

### Step 7: Build a proof of concept
- Create prototype of the most difficult fundamental features of the app
    - Demonstrates that the app can actually be done

### Step 8: Code out the features
- Implement the functionality of the app
    - From wireframe
    - From user stories
    - Both front-end and back-end
- Example features:
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
- Don't forget to do tests!
    - Unit tests
    - Integration tests
    - End to end tests
- It's coding time!

### Step 9: Choose and code the design scheme
- When the MVP of the functionality is done, clean it up and make it pretty
- It's time to make the app look cool

### Step: 10 Find and squash bugs
- Simulate every user flow
- Fix bugs
- Might not be the most systematic phase
    - Kanban?

### Step 11: Deploy the live app

## Tips
- If possible always try to work something/progress and then gain feedback. It’s better to have something to work with and make better than a blank paper
