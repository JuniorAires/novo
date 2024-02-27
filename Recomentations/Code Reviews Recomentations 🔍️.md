# Code Reviews Recomentations 🔍️

## Best Practices for Code Review

The first aspect of a good code review is to focus on the human side before the code. Below is a list of behaviors to pay attention to when reviewing someone else's code:

### Number of Reviewers (1 or 2):

By default and according to our team's configuration, we have defined that there should be 1 or a maximum of 2 reviewers involved in the development of the project to be reviewed.

### About the Reviewer

-   When providing suggestions, try to formulate sentences from a personal point of view:
    
    _e.g.,_ 

> "I suggest that...", "I think...", "To me, this point...

"
    
-   Always, ALWAYS, the review is about the code, never about the author:
    
    _e.g.,_ 

> ❌ "You are implementing it wrong..."
> 
> 
> 
> ✅ "The code is implementing it wrong..."

    
-   Ask questions about points that are not clear or offer suggestions through questions. Through the answers, we can better understand the decision for a certain point of the code.
    
-   Make comments through Observations, Impacts, and Requests:
    
    _e.g.,_ 

> **Observation:** "This implementation is repeated in another context, it could be reused."
>     **Impact:** "This implementation makes the understanding of the real purpose of the method not so clear to me."
   **Request:** "For this scenario, I suggest using X design pattern, for N reasons."

    
-   Understand that there are different solutions to the same problem.
    
-   Distinguish between best practices and personal preference.
    
-   Praise the code when necessary, even if it needs some adjustments.
    
-   Always ask yourself if your statement is true, necessary, and kind.
    
-   Value the effort the author made in writing the code.
    

### About the Author's Role in the Code Review

-   As the author, you should have humility to listen about your work.
    
-   It is normal to have failures, or to have better implementations, or to forget some detail.
    
-   Do not take criticism personally, you are not your code.
    
-   You and the reviewer are on the same team.
    
-   We are always biased by our own code. Be open to external opinions.
    

### Code

When reviewing code, it is good to have a checklist of what needs to be evaluated. Checking all aspects of the code at once can be exhausting and prone to errors. It is good to focus on one topic and validate all content from that perspective.

-  [ ] Do I understand what the code does?
    
-   [ ] Does the code fulfill all implementation requirements?
    
-  [ ] Does the code do what I expect it to do?
    
-   Using templates for Pull Requests, is it easy to analyze what that PR should solve?
    
-   Is the description of the PR/commit in line with what the code executes?
    
-   Pay attention to syntax, are there any code smells?
    
-   Pay attention if exception handling has been done.
    
-   Pay attention to the correct use of design patterns and over-engineering.
