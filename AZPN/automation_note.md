Notes

### **1. Overview**
- **BDD (Behavior-Driven Development):** Technique focusing on collaboration and understanding behaviors from a business perspective.
- **TDD (Test-Driven Development):** Technique emphasizing writing tests before code to ensure code correctness and simplicity.
- **ATDD (Acceptance Test-Driven Development)** is a software development methodology that extends the principles of TDD and BDD.
 Certainly! Here’s a merged overview of BDD, TDD, and ATDD in plain text:

TDD > BDD > ATDD

---


**TDD (Test-Driven Development):** 
- **Focus:** Unit testing and code correctness.
- **Test Scope:** Typically focuses on individual functions or methods.
- **Purpose:** Write tests before the actual code. Plain testing
- **Cycle:** Red-Green-Refactor (Fail-Test-Code-Refactor).
  - **Red:** Write a failing test.
  - **Green:** Write code to pass the test.
  - **Refactor:** Improve the code while keeping all tests green.
- **Tools & Frameworks:** JUnit, NUnit, pytest.
  - **JUnit:** A framework for writing and running tests in Java. For TDD for Java apps.
  - **NUnit:** A framework for .NET languages like C#. To write and execute tests in .NET environments.
  - **Pytest:** A  framework for Python. For TDD in Python projects.

**BDD (Behavior-Driven Development):**
- **Focus:** Behavior of the apps and its interaction with users or other systems.
- **Test Scope:** Write scenarios in a natural language (Gherkin) format before coding. Often involving multiple components or features.
- **Purpose:** Aligns development with business needs through teamwork and clear communication among devs, testers, and stakeholders.
- **Cycle:** Mostly, includes writing scenarios, coding to meet them, and refining the code.
- **Language:** Uses plain language for test scenarios (e.g., Given-When-Then with Gherkin).
- **Software Tools:** Cucumber, SpecFlow, JBehave. --> NO SON Frameworks
  - **Gherkin:** Gherkin is the plain language for writing BDD test scenarios 
  - **Cucumber:** BDD tool for various languages, using Gherkin.
  - **SpecFlow:** BDD tool for .NET using Gherkin.
  - **JBehave:** BDD framework for Java using Gherkin.

---
> **Summary:** TDD and BDD: Basically the team gathers up with devs, coders etc and check which scenarios can be automated, and then apply TDD. --> Es lo que ya hacía de testar simplemente

> - **Workflow:** 
> 1. **BDD:** The team collaborates to define scenarios (expected behaviors).
> 2. **Step Def:** After that, developers or testers create step defs to implement and automate the scenarios.
> 3. **Automation:** Use the step definitions for automation.
> 4. **TDD:** Write unit tests to ensure functionality meets the scenarios.

---
---

**ATDD (Acceptance Test-Driven Development):**
- **Focus:**  Ensures the software meets business requirements by defining and validating acceptance criteria before development.
- **Test Scope:** Defines and verifies high-level acceptance criteria to ensure the software meets business needs.
 - **Purpose:** Ensures software meets business requirements by writing acceptance tests before development.
- **Cycle:** 
  - **Define Criteria:** Collaborate with stakeholders to establish acceptance criteria.
  - **Write Acceptance Tests:** Create acceptance tests based on the criteria.
  - **Develop Code:** Implement code to pass the tests.
  - **Test and Refactor:** Check that the code meets the criteria and refine as needed.
- **Tools:** Often uses Cucumber,  (acceptance testing), SpecFlow.

---
---

**Benefits:**
- **BDD:** Enhances collaboration and understanding of requirements.
- **TDD:** Promotes simpler design and ensures code reliability.
- **ATDD:** Aligns development with business goals and improves communication.

**Common Practices:**
- **BDD:** Write scenarios in plain language; involve all stakeholders.
- **TDD:** Follow the Red-Green-Refactor cycle; focus on incremental changes.
- **ATDD:** Collaborate on acceptance criteria; ensure all requirements are tested.

**Additional Concepts:**
- **CI/CD:** Automates integration and deployment.
- **Exploratory Testing:** Unscripted testing to find unexpected issues.

