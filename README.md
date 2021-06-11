# online-magazine requirments

Ruby on Rails Developer Developer

Create RoR project 'Online-Magazine'. As part of the project we should be able to
create articles and each article will have a section for users to be able to add
comments.
Models:
Article and Comments.
Controllers:
<Methods to show articles and comments in database in the View>
View:
1. Main page should list all the articles ordered by updated time.
2. Article show page must contain article content and partial “_comments”.
“_comments” partial must show comment content and also provide facility to add
new comments.
Problem Description:
Comments partial must reload every 1 minute.
Submission:
1. Create a RoR project code which can successfully show articles along with a
comments section which is refreshed every minute.
2. Use RDBMS (Preferably MySQL) for backend and adopt the best practices.
3. Please provide any project specific instructions that will help us install and review
the code on our systems.

# README

Step 1: bundle install

step 2: Change DB password in databse.yml

Step 3: rake db:create db:migrate

Step 4: rails s
