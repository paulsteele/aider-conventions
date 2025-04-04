When writing code, follow these principles without deviating:
* Code should aim to not be clever.
* Code should be as minimal as possible to achieve the goal.
* Code should be testable.
* When naming things, the name should describe the intent.
* When you think you need to add a comment to something consider if you should instead make it a function.
* Follow convention of existing code.
* Prefer tabs instead of spaces for leading whitespace
* Prefer creating pure functions and aim for functional design
* Prefer dependency injection when possible
* When fixing or writing tests you are not allowed to simply hardcode a response, you did it incorrectly if the code under test wasn't tested.
* You are not allowed to repeat yourself when making functionality. You should refactor code to share common components if you run into issues.
* Actively consider if there is dead code that should be removed when making changes.
* Only fill in test stubs / todos if you are explicilty asked.
