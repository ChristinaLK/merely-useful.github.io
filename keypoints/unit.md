-   Testing can only ever show that software has flaws, not that it is correct.
-   Its real purpose is to convince people (including yourself) that software is correct enough, and to make tolerances on 'enough' explicit.
-   A test runner finds and runs tests written in a prescribed fashion and reports their results.
-   A unit test can pass (work as expected), fail (meaning the software under test is flawed), or produce an error (meaning the test itself is flawed).
-   A fixture is the data or other input that a test is run on.
-   Every unit test should be independent of every other to keep results comprehensible and reliable.
-   Programmers should check that their software fails when and as it is supposed to in order to avoid silent errors.
-   Write test doubles to replace unpredictable inputs such as random numbers or the current date or time with a predictable value.
-   Use string I/O doubles when testing file input and output.
-   Use a coverage tool to check how well tests have exercised code.
