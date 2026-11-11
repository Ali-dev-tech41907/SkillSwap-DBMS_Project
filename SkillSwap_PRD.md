# SkillSwap -- Product Requirements Document (PRD)

**Project:** SkillSwap -- Student Skill Exchange Platform\
**Document Type:** Product Requirements Document\
**Version:** 1.1 -- Simple Version

## 1. Project Overview

SkillSwap is a platform where people teach skills they already know and
learn new skills from others. Instead of paying money, users exchange
their knowledge.

**Example:** Ali can teach Python and wants to learn Photoshop. Sara can
teach Photoshop and wants to learn Python. SkillSwap helps them find
each other and arrange an exchange.

The platform is intended for people around the world, not only students
of one university. The current academic version will run locally on a
computer.

## 2. Problem the Project Will Solve

People may find it difficult to: - Afford courses or private lessons. -
Find someone who can teach a skill they want to learn. - Find learners
who want the skills they can teach. - Organize learning requests,
session times, and feedback in one place.

SkillSwap provides one organized place to find suitable learning
partners and exchange skills.

## 3. Project Aim and Objectives

**Main aim:** Make learning easier and more affordable by allowing
people to exchange skills without paying each other.

The project aims to: - Let users create accounts and profiles. - Let
users list skills they can teach and want to learn. - Suggest people
with matching learning and teaching needs. - Support exchange requests
and responses. - Help users arrange learning sessions. - Allow feedback
after sessions. - Send notifications about important activities.

## 4. Target Users

SkillSwap is for students, beginners, professionals, hobbyists, and
anyone interested in sharing knowledge. It is not limited to one
university or location. A user can be both a teacher and a learner.

## 5. How the System Will Work

1.  A user registers and signs in.
2.  The user adds skills they can teach.
3.  The user adds skills they want to learn.
4.  SkillSwap suggests people with complementary skills.
5.  The user views a suggested person's profile and sends a request.
6.  The other person accepts or declines.
7.  If accepted, both users arrange a learning session.
8.  After the session, users can provide feedback.

A strong match means each person can teach something the other person
wants to learn.

## 6. Main Features

-   **Accounts and profiles:** Register, sign in, sign out, and update
    profile information.
-   **Teaching skills:** Add skills the user can teach and indicate a
    skill level.
-   **Learning interests:** Add skills the user wants to learn and a
    desired level.
-   **Skill matching:** Suggest users with reciprocal learning and
    teaching needs.
-   **Exchange requests:** Send, receive, accept, decline, and track
    requests.
-   **Availability and sessions:** Share available times and arrange
    sessions after acceptance.
-   **Reviews:** Rate and comment on a completed learning session.
-   **Notifications:** Receive updates about requests and sessions.
-   **Reports and administration:** Report inappropriate behaviour for
    administrator review.

## 7. Situations the System Should Handle

  -----------------------------------------------------------------------
  Situation                           Expected Result
  ----------------------------------- -----------------------------------
  A user registers with valid details The account is created.

  An email is already registered      An error message is shown.

  A user has not added skills         The system asks them to add skills
                                      before matching.

  Two users have reciprocal skill     The system suggests them as a
  needs                               match.

  No suitable match is found          A no-match message is shown.

  A user sends a request              The other user can view it.

  A request is accepted or declined   Its status is updated.

  A session is cancelled              Users can see the updated status.

  A session is completed              Users can provide feedback.

  A user submits a report             It is available for administrator
                                      review.
  -----------------------------------------------------------------------

## 8. Project Scope

### Included

-   Registration and login
-   User profiles
-   Teaching and learning skills
-   Skill categories and matching
-   Exchange requests
-   Availability and session management
-   Reviews and ratings
-   Notifications
-   Basic reporting and administration

### Not Included in the Current Version

-   Online payments or money transfers
-   Paid courses or subscriptions
-   Built-in video or audio calls
-   Automatic session recording
-   Android or iOS mobile applications
-   Professional certificates or degrees
-   Guaranteed identity or skill verification
-   Public deployment for the current demonstration

## 9. What SkillSwap Will NOT Do

SkillSwap will not charge users, guarantee a match, guarantee that a
request will be accepted, or guarantee that users attend sessions. It
will not verify every claimed skill, provide official qualifications,
replace formal education, or host live video lessons in the current
version.

## 10. Basic Quality Requirements

-   The website should be simple and easy to use.
-   Forms should explain what information is required.
-   Clear success and error messages should be displayed.
-   Account features should require sign-in.
-   Users should not be able to change another person's account.
-   Passwords and private information should be protected.
-   Common features should work smoothly during the demonstration.
-   The website should work in a modern desktop browser.

## 11. Assumptions and Limitations

-   Users are responsible for providing accurate skill information.
-   Users arrange suitable session times with each other.
-   A suggested match is not a confirmed exchange.
-   The academic prototype will run locally on a computer.
-   Global public access would require future online hosting and
    additional support.

## 12. Project Success Criteria

The project will be successful if users can: 1. Register, sign in, and
manage their profiles. 2. Add teaching skills and learning interests. 3.
Receive reciprocal skill-match suggestions. 4. Send, accept, and decline
exchange requests. 5. Arrange and view learning sessions. 6. Give
feedback after completed sessions. 7. Receive notifications. 8. Submit
reports for review. 9. See clear messages when an action fails or no
match is available.

## 13. Future Improvements

Possible future features include public online access, mobile
applications, video meeting support, more matching options such as
language and time zone, improved user verification, and additional
languages. These are not part of the current academic version.

## 14. Conclusion

SkillSwap helps people learn from one another by exchanging skills
instead of paying money. Users can share what they know, find people who
can teach what they want to learn, arrange sessions, and provide
feedback.

The current project will demonstrate this process as a local academic
prototype. Its goal is to make peer-to-peer learning more organized,
accessible, and useful.
