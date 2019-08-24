---
layout: post
title:  "The Software architect absence."
date:   2019-08-30 21:00:00
tags: architect
comments: true
author: maviteixeira
preview: In a serious organization you need to have some base standards, code quality bar and measurements. This applies, of course, to the projects internal communication
image: https://maviteixeira.github.io/images/we_just_need_to_find_her.png
---

- Test induce damage
- Beware of mocks
- Behavior tests vs unit tests
- Testing implementation, problems in the long run (unit)
- Measures using unit tests and behavior (time to run, lines of code, refactoring effort)
- Honeycumb test

links:
https://phauer.com/2019/focus-integration-tests-mock-based-tests/
https://labs.spotify.com/2018/01/11/testing-of-microservices/
https://medium.com/@copyconstruct/testing-microservices-the-sane-way-9bb31d158c16
https://www.testcontainers.org
https://www.simpleorientedarchitecture.com/test-strategy-for-continuous-delivery/
https://www.joecolantonio.com/testing-pyramid/

- General
    - What is the main goal of testing ? Quality ? Design ? Refactor security ?
    - Integation tests > less pressure in design > bad design > hard to write tests and increase mistakes
    - Context independency.
    - Design by contract (interface)
    - State based test (add someone in the list and check if its there)
    - Collaboration test
    - Contract tests ? (Someone implement the interface correctly)
    - Code coverage vs business coverage
    - Why, What, How and Where



- Integrations tests definitions:
    - When it fails i cannot point directly to the problem
    - Refactor friendly
    - Its not that clear where the problem really is
    - Integrated tests are a scam ? 
    - Relation between integrations tests and design problems, lack of pressure in the design. (dependency)
    - Integrations tests make bad designer easier ?
    - Aspirins to cause more headache
    - Should test behavior and not specific paths

- Unit tests definitions:
    - Instead of unit can we called isolated tests ?
    - All tests can pass but we could find a bug.
    - Contribute to better design ? This have some point.
    - Mock is really bad ? Stunt doubles
    - Stub is hardcoded response for some tests.
    - Testing the implementation details and this make code hard to refactoring


Zero, One, Many, Lots and Ops

https://www.youtube.com/watch?v=CHDZpFU33KQ