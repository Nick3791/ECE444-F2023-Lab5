# ECE444-F2023-Lab5

This is the repository for lab 5 of the UofT course ECE444.

Part of the code written here is taken directly from the TDD tutorial for Flask here: https://github.com/mjhea0/flaskr-tdd

## Link to the Unit Test for Lab 5 from my group project's Repo:
https://github.com/ECE444-2023Fall/project-1-web-application-design-group18-ctrlaltdefeat/blob/dd24ba03597471c33d1b7694b5a06c6d2fe08132/web_app/tests/events_test.py#L21C1-L47 

## What are the pros and cons of TDD?

#### Pros
- By writing the tests first, application code next, you're guaranteeing that the application is testable.
- Overall higher code quality for the application because all functions that are written must pass, i.e. it's less likely to commit functionality or features that don't work.
- Also improves code quality because developers are forced to think about interfaces before coding up the functionality, this should likely result in cleaner, simpler interfaces for functionality.
- Facilitates better teamwork. Once features are complete, it should be easier for teammates to extend or add new features because any extensions or new code would have to not only pass the new tests but also the old ones written by the original feature contributor.
- Potentially leads to less fear of making changes and more confidence that the code works.
- Easier debugging. Catching the bugs during the testing phase while the functionality is still being developed is better than being caught later on in the development process.
- Leads to better documentation. Tests can provide additional understanding of how functions are supposed to be used (i.e. examples of functions being called) and what kinds of outputs are expected.
#### Cons
- Requires spending time developing the tests. Since some projects can have fixed schedules, putting the priority on writing tests first may put more pressure on developers to finish features in time.
- Tests written while following TDD are likely only written to test the intended/expected behaviour of a function and may miss out on the side effects of a function. Sometimes those functional side effects are unintended and hence likely won't be picked up by these tests. We may even get the wrong impression that there is no issue with the function because all the tests pass.
