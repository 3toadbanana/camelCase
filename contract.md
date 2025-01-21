# Nutrition Insights

**Team Members:** David Song, Adit Garg, Ahmed Khalili, Beshir Said  
**Instructor:** Jean Salac  
**Course:** CS 257  
**Date:** Jan 20, 2025  

---

## Working Title
Nutrition Insights

---

## Team Goals
For the final project, we want to make a functioning, aesthetic website that showcases nutritional data. In the bigger picture, we want to get a clear understanding of real-world programming while honing key skills such as team collaboration, multi-language coding, meaningful documentation, and applied ethical reasoning.

---

## Team Strengths

### Overall Strengths
Our group has members who have previously worked with Flask, including a member experienced in building and deploying a dataset-backed website. We have good communication, with clearly agreed-upon modes of contact and meeting times. Below are some individual strengths we bring to the group.

### Individual Strengths
- **Adit:** Has worked with Flask before, with experiences in multiple languages. As a prospective CS Major, he is motivated and engaged with this project.
- **David:** POSC major. Strong writing background. Familiar with applied ethics in real-world situations. Although relatively less experienced in CS, this factor can allow for him to have a closer consumer perspective for the final product. Experienced with keeping meeting notes, organizing meetings, and streamlining/delegating work within a group.
- **Beshir:** As a CS major, I have worked on CS projects and have experience in multiple languages and using GitHub. I enjoy these types of projects, which keeps me motivated for the task.
- **Taha:** Have worked in CS-related team projects for website development, familiar with several languages, passionate about CS, good communication, and motivating other members.

---

## Our Strengths

### Delegation Strategy
Overall, our group has members who have previously worked with Flask, with a member experienced with building as well as deploying a dataset-backed website. We have good communication, with clearly agreed upon modes of contact and meeting times. Below are some individual strengths we bring to the group. 
- Members experienced with HTML will handle HTML components.
- Members proficient with Flask will manage Flask components.

While we do not plan for a rotating role system, we are open to reassigning roles upon consensus based on project needs.

### Roles
- **David:** Sets meeting agenda and schedules extra meeting times.
- **Adit:** Designated debugging, check for final testing of code.
- **Beshir:** Build initial tests, notify parts of code built.
- **Taha:** Be on time with your part of the work and for meetings.

---

## Team Expectations

The primary mode of general communication will be through group text, with emails (calendar invites) as the mode to set up meetings. We will update each other on the status of our delegated work, checking the group text at least once every weekday. The meetings will be once a week on Wednesday 8pm for 1 hour on Zoom.  If a teammate misses four meetings, including being late for more than 30 minutes, we will contact Jean as necessary. 
As a team we believe respectful communication looks like a give and take between listening and speaking. We will listen actively with each other, and wait our turn to give our feedback. When we disagree, we will understand that it is part of the process of creating something better. If conversations get too heated, we will take a couple minutes off the zoom call to cool down. Satisfactory participation to us is broad, as direct coding is not the only method of contributing meaningfully. We believe feedback, active listening, and research are all meaningful contributions team members could make. As for time contributions, we expect each member to contribute at least 10 hours outside of class to follow this project per week (or the equivalent amount of work done). We are happy to help out if a member is struggling, but it is up to the responsibility of the member to reach out and communicate to the rest of the team. If there is a member that can not meet these work contribution standards, we will give 2 warnings, then proceed to contacting Jean. 
We will make decisions through consensus, and if there is a disagreement that can not be resolved through just convincing, we will go with majority rule. 
A general rule for delegation will be efficiency and proficiency. We have members who are already familiar with Flask, HTML, and other things necessary for this project. We will delegate the tasks accordingly to make sure we keep our workflow quick and efficient. For tasks that nobody is familiar with, we will first go with volunteers, then into rock paper scissors. 

---

## Dataset Information

### Summary
The dataset is a JSON file, containing information on different nutrients of different food items, such as protein, carbs, energy, total fat, sodium, calcium, etc. Since it is a JSON file, it is easy to isolate and access individual headers of different nutrients. 
The dataset was processed from a larger dataset that had some superfluous and unnecessary information. 

### Metadata (current dataset is a modified version of the below)
- **URL:** https://fdc.nal.usda.gov/download-datasets
- **Date Downloaded:** 20th Jan, 2025
- **Authorship:** USDA
- **Exact Name & Version:** FNDDS 2021-2023
- **Terms of Use:** Public Domain
- **Suggested Citation:** 

---

## User Interactions
### Interaction 1
A user could input a list of food they ate for a meal, selecting from a dropdown menu of sorts. They would would then get a nutritional label of the estimated nutritional value of the food that they ate. This nutritional value will be based on our dataset and the serving sizes. 
- **Potential Users:** Health-conscious users and users who want some insight into their dietary value.
- **Interaction Mechanism:** Search & Dropdown. Users will type out what they want to input, picking the closest match from our database from a dropdown list.
- **Potential Benefits:** Users will learn about what they are eating and potentially make changes in their diet to get more well-rounded nutrition from their food.
- **Potential Harms:** Our database is not exhaustive, which may result in some inaccurate information. Users becoming too conscious of their nutrition may create an unhealthy relationships with food.
### Interaction 2
A user could search up a product and use a filter such as “lowest calorie” or “contains above ___ calcium” to get a result.
- **Potential Users:** Health-conscious users, users with diet restrictions, dietitians.
- **Interaction Mechanism:** Search & Filter. Users can search specific food items and apply filters for nutritional content.
- **Potential Benefits:** Users gain a better understanding of the nutritional content of different foods, which can lead to more informed decisions about what to eat. With filters, users can find foods that fit their specific health or dietary goals, such as weight loss or increasing certain nutrients. By enabling users to make better dietary choices, they could improve their health outcomes.
- **Potential Harms:** Too many filters or choices could overwhelm users, especially those who are not familiar with nutrition science. If the data provided is inaccurate or outdated, users might make poor dietary choices that negatively impact their health. Some users might develop unhealthy relationships with food, such as disordered eating, anxiety about food choices, or obsessing over nutrient content.

### Interaction 3
A user could generate reports on nutrition trends to improve health plans.
- **Potential Users:** Health professionals.
- **Interaction Mechanism:** Generate reports on patterns.
- **Potential Benefits:** Helps professionals guide clients better.
- **Potential Harms:** Misleading trends may cause poor advice.

### Interaction 4
A user could use a dashboard to view food trends for menu planning.
- **Potential Users:** Restaurant managers.
- **Interaction Mechanism:** Dashboard showing trends.
- **Potential Benefits:** Helps create better menus.
- **Potential Harms:** Ignoring uncommon diets.
