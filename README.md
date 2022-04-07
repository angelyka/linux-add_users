# linux-add_users
From our Lab Activity in AWS re/Start where we were asked to add new users using Linux CLI.

===============================

**Scenario**

New week, same deal. Mr. X has come to you this week with a new set of requirements with a little bit more difficulty but with the same Friday paid vacation. He may get into some trouble giving all these paid vacation days. Who cares? The beach was amazing. In continuation of the Linux setup, Mr. X needs to set up some basic user information for the company. He has a list of each section as well as who needs to be admins.

**Objectives**

In this lab, you will:
- Create new users with a default password
- Create groups and assign the appropriate users

**Exercise 1: Create Users**

Back to the grind, your first task of the week is to create new users based on the user sheet that Mr. X provided. Ensure you spell the userid correctly so they can use default credentials to log in.

**TODO**
1. Create users in the CentOS from the list shown in the figure.

![List of Users](https://i.imgur.com/8m3JLlYl.png)

**Additional Challenges**
- When you create each user, add comments about the user’s role and set non-manager personnel to have an expiration date two years from the date of creation.
- Use the useradd command only once per user created without using passwd.

**Exercise 2: Create Groups**

Mr. X thinks you may have some great potential but wants to see more action. He wants you to create the following groups:

   - Sales
   - HR
   - Finance
   - Personnel
   - CEO
   - Shipping
   - Managers

When created, add the proper users to the proper groups based on the list provided in the figure for exercise 1.

**TODO**

Create all the groups and add the appropriate users to them. Watch out! Managers are personnel, but not all personnel are managers. Some users will belong to multiple groups.

