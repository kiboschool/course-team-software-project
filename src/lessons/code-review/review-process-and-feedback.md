# Conducting Code Reviews

## The process of conducting a code review

The process of conducting a code review can be broken down into the following steps:

**Author creates a change list (CL)** - The author creates a change list (CL) that contains the code changes that they want to submit to the codebase. The change list ould be written as the description of a pull request or as a separate document.

**Reviewer reviews the CL** - The reviewer reviews the CL and provides feedback on the code changes. The reviewer can either approve the CL or request changes.

**Author addresses the feedback** - The author addresses the feedback provided by the reviewer and makes the necessary changes to the CL and then resubmits it for review. This process continues until the reviewer approves the CL.

**Reviewer approves the CL (LGTM)** - The reviewer approves the CL and merges it into the codebase.

## Provide Constructive Feedback

while reviewing code, you check for bugs, security issues, and other potential problems as we discussed in the previous lesson. It is expected that you will find issues with the code, and you should provide feedback to the author of the code to help them improve the quality of their code. Providing feedback is an important part of the code review process, but it is important to provide feedback in a constructive manner.

Feedback should be clear and actionable, with suggestions for potential solutions. Unconstructive feedback is vague, unhelpful, and often critical without offering any suggestions for improvement. Here are some examples of unconstructive feedback that should be avoided during a code review:

"This code is terrible. What were you thinking when you wrote this?"

"I could write better code in my sleep. This is a waste of my time."

"This is a rookie mistake. You should know better."

"I don't like this. Change it."

"This is just wrong. Fix it."

Here are some examples of constructive feedback that can be provided during a code review:

"The variable names in this function are not descriptive enough. Could we rename it to something more descriptive, like userInput?"

"I noticed that this function doesn't have any error handling. Would it be possible to add some error handling code to prevent unexpected behavior?"

"I think this code could be simplified by using a built-in function instead of manually looping through the array. Have you considered using Array.filter() instead?"

"The logic in this code block seems a bit convoluted. Shall we consider breaking it up into smaller functions for better readability and maintainability?"

"I noticed a potential security issue with this code. What about implmeting validation here to prevent injection attacks?"

## Focus on the code and not the coder

Notice that, in the previous examples, I don't use "you" or frame the feedback as a command . Instead, Using "we", passive voice, or a request tone can help to avoid personal attacks and make the feedback more constructive.

## You aren't always right

Sometimes, you will be wrong. It's important to be open to feedback and willing to consider alternative solutions or approaches to problems. Talking the previous note into consideration will allow the author ti push back politely. Code reviews provide an opportunity for team members to learn from each other and improve their skills, so embrace the opportunity to collaborate and grow as a team.

## Collaborate on Solutions

Encourage team members to collaborate on potential solutions to problems identified during the code review. This can help to build a sense of trust and collaboration within the team, and can lead to better solutions overall.

## Review Code Regularly

Conduct code reviews regularly. This can help to catch bugs early and prevent technical debt from accumulating over time.

## Offer Praise

Do not forget to praise the author for the good parts of the code. This will help to build a sense of trust and collaboration within the team, and can lead to better solutions overall. Specially if this is something that have been improved from previous code reviews.
