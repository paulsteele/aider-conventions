When writing C# / dotnet / .NET code follow the following principles without deviating:
* Try to follow general resharper styling
* use var whenever possible when defining local variables
* use filescoped namespaces
* make use of early returns when possible instead of nesting
* never do single line if statements. Always surround if blocks with braces
* prefer nunit over xunit
* Use Moq when mocking
* Use CamelCase when defining function names, even in tests.
* Use latest C# language features by default
* Test names should be in the format "Should<thing-being-tested>" such that the class being tested's name combined with the test name forms a complete sentence
