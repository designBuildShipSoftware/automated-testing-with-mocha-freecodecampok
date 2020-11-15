<h1>Automated Testing with Mocha :coffee:</h1>

<br>

Mocha is a JavaScript test framework for Node.js programs, featuring browser support, asynchronous testing, test coverage reports, and use of any assertion library. See https://en.wikipedia.org/wiki/Mocha_(JavaScript_framework)

---

<h3>BDD vs TDD</h3>

**TDD** is **Test Driven Development**. This means writing a test that fails because the specified functionality doesn't exist, then writing the simplest code that can make the test pass, then refactoring to remove duplication, etc. You repeat this Red-Green-Refactor loop over and over until you have a complete feature.

**BDD** is **Behavior Driven Development**. This means creating an executable specification that fails because the feature doesn't exist, then writing the simplest code that can make the spec pass. You repeat this until a release candidate is ready to ship.

Those seem pretty similar, right? They are. The key difference is the scope. TDD is a development practice while BDD is a team methodology. In TDD, the developers write the tests while in BDD the automated specifications are created by users or testers (with developers wiring them to the code under test.) For small, co-located, developer-centric teams, TDD and BDD are effectively the same.

See https://www.pluralsight.com/blog/software-development/tdd-vs-bdd

---

Understanding **code quality** before working on a code project is like building a house :house_with_garden: (project) on a quality foundation so that the big bad wolf :wolf: can't blow it down. 

To start learning about code quality, you may check out https://javascript.info/code-quality
