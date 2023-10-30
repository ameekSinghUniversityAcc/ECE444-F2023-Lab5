# ECE444-F2023-Lab5

## Unit testing commits to web-app
- https://github.com/ECE444-2023Fall/project-1-web-application-design-group11-webwizards/blob/main/react-frontend/src/CreateFlyer/components/dialog/index.spec.js#L1-L65
- https://github.com/ECE444-2023Fall/project-1-web-application-design-group11-webwizards/blob/main/react-frontend/src/CreateFlyer/index.spec.js#L1-L18
#### Note: The command to run these tests was determined using: https://github.com/ECE444-2023Fall/project-1-web-application-design-group11-webwizards/blob/e771eb49fdc5d038db7d49ec3c399080a2e4a968/README.md?plain=1#L40


## Pros and Cons of TDD
### Pros
- Helps ensure that test cases (user journeys) do not get missed when writing code. When writing code, I often find myself forgetting/ignoring certain user scenarios. By having the tests written in advance, I can make sure that the code does not miss key user scenarios.

**Note:** The following pros are based on the "What can TDD do? - Benefits" in the Lab 5 slides (see: https://q.utoronto.ca/courses/324733/files/folder/Lab/Slides?preview=28310824

- Ensures that code we put out is free of errors. When working on big changes, there is some scope for unexpected behaviors to creep in. The tests help prevent this scenario, since we can be confident that the code is free of errors.
- Allocates appropriate time for writing tests. I've personally noticed a tendency in myself to quickly write tests for faster deployment. In TDD, this is avoided since the tests are written before the code.

### Cons
- Slows development time: The time that I would've put towards developing a particular project, is now split between writing functional code and writing tests. Therefore, I belive it can slow down time to production.

**Note:** The following con is based on my understanding of the "Final Comments" in the lab 5 slides (see: https://q.utoronto.ca/courses/324733/files/folder/Lab/Slides?preview=28310824

- Tests can fail easily if not written well: If the test is not written well, we might see a possibility where the test could pass when it should not, or can easily be made to fail by unrelated changes.