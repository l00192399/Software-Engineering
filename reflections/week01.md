Software isn't just code on its own; it's a full package or "configuration" that combines the actual programs, the data, and all the supporting documentation.
Engineering adds structure, predictability, and discipline to that package. 

one example of a success i have personally experienced is using chatgpt to help me understand programming problems. when i get stuck om java or python code, i can explain what i am trying to do and get an explanation that usually helps me understand the problem. i think the developers did well by making the ai able to explain things in different ways instead of just giving an answer.
one failure i have experienced is when ai gives me code that looks correct but does not actually work when i run it. this has happened to me when working on college assignments, where i have had to go back and explain the error before getting a working solution. i think the developers could improve this by having the ai test or verify the code more thoroughly before giving it to the user, especially when it involves specific libraries or versions.

 ## The Four Process Activities: RetailSync Case Study

Kickoff
Specification: Missing – No written requirements were created.
Development: Present – The developer started designing the database.
Validation: Missing – No validation was done at this stage.
Evolution: Missing – No process for handling future changes was planned.

Development
Specification: Weak – The developers relied on their understanding instead of clear requirements.
Development: Weak – Developers worked separately with no coding standards or code reviews.
Validation: Missing – Warehouse staff were not involved and there was no proper testing.
Evolution: Weak – Changes were not being properly considered during development.

A Change of Plan
Specification: Weak – The second warehouse requirement was only mentioned informally.
Development: Present but weak – The team patched the new requirements onto the existing system.
Validation: Missing – The existing design was not properly reviewed against the new requirement.
Evolution: Weak – The system was changed, but the change was not properly managed.

Testing
Specification: Weak – There were no written test cases.
Development: Present – The team fixed crashes they found themselves.
Validation: Weak – Testing only lasted two days and warehouse staff were not involved.
Evolution: Missing – No proper plan for improving the system based on testing was used.

Go-Live
Specification: Weak – Real warehouse needs had not been properly captured.
Development: Present but unsuccessful – The system was running but had serious problems.
Validation: Missing – The problems were only discovered after real users started using it.
Evolution: Present but reactive – The team had to make further fixes after the system was pulled from use.

Biggest Failure
I think the biggest failure was the lack of proper specification at the beginning. The team never created written requirements and did not properly involve the warehouse staff. Because of this, the developers misunderstood how the warehouse actually worked. This caused problems later, including the stock-transfer screens not matching the real process. The missing requirements also made the change for the second warehouse harder to handle. Overall, a better specification at the start could have prevented several of the problems that appeared later.

## Researching a Software Failure

Ariane 5 Flight 501 failed on 4 June 1996, around 37 seconds after launch. The failure was caused by software in the rocket's inertial reference system. The Ariane 5 reused software from the Ariane 4, but the Ariane 5 had a different flight path and produced higher horizontal velocity values. This caused a value stored as a 64-bit floating-point number to be converted into a 16-bit signed integer. The value was too large, causing an integer overflow and triggering a hardware exception. This caused both inertial reference systems to shut down. The flight computer then interpreted diagnostic data as flight data, causing the rocket to veer off course and eventually self-destruct. The failure resulted in the loss of more than $370 million.

This relates to evolving requirements, because software designed for Ariane 4 was reused in Ariane 5 without accounting for the differences in their flight paths and expected values.

Source: https://en.wikipedia.org/wiki/Ariane_flight_V88
