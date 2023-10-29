# ECE444-F2023-Lab5

## Unit testing commits to web-app
- https://github.com/ECE444-2023Fall/project-1-web-application-design-group11-webwizards/blob/main/react-frontend/src/CreateFlyer/components/dialog/index.spec.js#L1-L65
- https://github.com/ECE444-2023Fall/project-1-web-application-design-group11-webwizards/blob/main/react-frontend/src/CreateFlyer/index.spec.js#L1-L18

## Pros and Cons of TDD
#### Note: The following information is based on the lab 5 slides (see: https://q.utoronto.ca/courses/324733/files/folder/Lab/Slides?preview=28310824)
### Pros
- Helps ensure that test cases (user journeys) do not get missed when writing code. When writing code, we often find ourselves forgetting/ignoring certain user scenarios. By having the tests written in advance, we make sure that the code does not miss key user scenarios.
- Ensures that code we put out is free of errors. When working on big PRs, there is some scope for unexpected behaviors to creep in. The tests help prevent this scenario, since we can be confident that the code is free of errors.
- Allocates appropriate time for writing tests. I've personally noticed a tendency in myself to quickly write tests for faster deployment. In TDD, this is avoided since the tests are written before the code.

### Cons
- Slows development time: The time that we would've put towards developing a particular project, is now split between writing functional code and writing tests. Therefore, it can slow down time to production.
- Tests can be moody if not written well: If the test is not written well, we might see a possibility where tiny (non-breaking) changes can break the test.