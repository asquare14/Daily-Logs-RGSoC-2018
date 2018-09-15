This page covers the main features of the app.

# User Account Creation

Visit if me homepage: http://www.if-me.org/

![](https://github.com/julianguyen/ifme/blob/master/public/wiki_images/landing-page.png)

Hit "Join" button on the menu found on the top-left corner
Option to sign up with Google account credentials is also available

# Admin Account Creation 
(For development environment only)
1. Go to terminal and type `rails console`
2. `id = 2 (id of user you want to make admin)`
3. `u = User.find(id)`
4. `u.admin = true`
5. `u.save`

This should make the user an admin and give the user admin privileges.

# Nav menu
Moments - A Moment is an event and situation that affects your mental health. It can be positive or negative. Think of it as a journal entry or a status update. You can tag it with Strategies, Categories, and Moods. You can also choose which allies can view and comment. You can also make it only visible to you.

Moods - A Mood is a tag describing your state of mind, feelings, and emotions.

Categories - A Category is a tag that can represent the people, places, and things that are important to you.

Strategies - A Strategy is an activity, train of thought, or form or self-care that helps you cope or focus on recovery. You can tag it with Categories. You can also choose which allies can view and comment. You can also make it only visible to you. Shared Strategies will be visible to all allies specified, which means you can tag your Moments with their Strategies!

Medications - The Medications feature allows you to log the prescription drugs you are taking. You can also log your symptoms.

Groups - A Group offers support, mentorship, and discussions on mental health. You can create Groups and your allies have the option of joining. You can only join groups that are created by your allies. As a Group leader, you can create Meetings. Meetings have a location and time. The location can be a physical place or a Google Hangout URL. Meetings also allow for comments. If you are a Group leader, you cannot leave a group unless there is another leader. Groups can only be deleted when you are the only member.

Allies - Loved ones who are able to interact with your Moments and Strategies. You can also form groups with them.

Admin Dashboard - After User reports an Ally. Admin receives this report. Admin can either ignore report and do nothing, or email the User and inquire more. After emailing User, admin can email the reported Ally and inquire as well. Based on inquiry, the admin can delete Ally account. 

![](https://github.com/aSquare14/Daily-Logs-RGSoC-2018/blob/master/Selection_001.png)

# Moments

Moments Menu drops down to two sub-categories

![](https://github.com/julianguyen/ifme/blob/master/public/wiki_images/moments-dropdown.png)

Add category by clicking on symbol highlighted below

![](https://github.com/julianguyen/ifme/blob/master/public/wiki_images/add-category.png)

# Medications

Keep track of your medication, add comments, and set a reminder for refill dates

![](https://github.com/julianguyen/ifme/blob/master/public/wiki_images/medications-form.png)

Confirmation page

![](https://github.com/julianguyen/ifme/blob/master/public/wiki_images/medications-confirmation.png)

# Strategies

![](https://github.com/julianguyen/ifme/blob/master/public/wiki_images/strategy.png)

# Groups
![](https://github.com/julianguyen/ifme/blob/master/public/wiki_images/groups.png)

# Allies
![](https://github.com/julianguyen/ifme/blob/master/public/wiki_images/allies.png)
Search for Allies to help you

# Account Modification

![](https://github.com/julianguyen/ifme/blob/master/public/wiki_images/account-dropdown.png)

If me logo drops down to allow you to modify account or sign out

# Admin Dashboard
![](https://github.com/aSquare14/Daily-Logs-RGSoC-2018/blob/master/Selection_004.png)
Search for Allies to help you



