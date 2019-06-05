# Testing Types

sources:
- https://glossary.istqb.org/en/search/
- https://arborosa.org/2015/07/21/test-levels-really/
- https://arborosa.org/2015/07/31/regression-testing/
- https://arborosa.org/2015/07/15/a-collection-of-quality-characteristics/
- https://arborosa.org/2015/08/16/test-types-a/
- https://arborosa.org/2016/01/20/test-types-b-c/
- https://arborosa.org/2016/01/26/test-types-d-e-f/
- https://arborosa.org/2016/02/14/test-types-g-h-i/
- https://arborosa.org/2016/04/13/test-types-j-k-lm/
- https://arborosa.org/2016/06/08/test-types-n-o-p/



## Misc
regression
alpha, beta, (gamma) testing
a/b testing
fuzz testing
mutation testing


## Approach
static (Testing a work product without code being executed.), dynamic (Testing that involves the execution of the software of a component or system.
), documentation, monitoring
manual, automated
whitebox, black-box (specification-based testing), grey-box
positive, negative

### Scripted vs exploratory
- scripted testing: Testing (manual or automated) that follows a test script.
- session-based testing: An approach to testing in which test activities are planned as uninterrupted sessions of test design and execution, often used in conjunction with exploratory testing.
- Experience-based testing: Testing based on the tester's experience, knowledge and intuition.
- Exploratory testing

### Model source
- Model-based testing: Testing based on or involving models.
- requirements-based testing: An approach to testing in which test cases are designed based on test objectives and test conditions derived from requirements, e.g., tests that exercise specific functions or probe non-functional attributes such as reliability or usability.
- risk-based testing: Testing in which the management, selection, prioritization, and use of testing activities and resources are based on corresponding risk types and risk levels.



## SDLC
- agile testing
- acceptance testing
	- regulatory acceptance testing: Acceptance testing conducted to verify whether a system conforms to relevant laws, policies and regulations.
	- standard-compliant testing: Testing that complies to a set of requirements defined by a standard, e.g., an industry testing standard or a standard for testing safety-critical systems.
	- user acceptance testing: Acceptance testing conducted in a real or simulated operational environment by intended users focusing their needs, requirements and business processes.
	- operational acceptance testing (production acceptance testing): Operational testing in the acceptance test phase, typically performed in a (simulated) operational environment by operations and/or systems administration staff focusing on operational aspects, e.g., recoverability, resource-behavior, installability and technical compliance.
	- Contractual acceptance testing: Acceptance testing conducted to verify whether a system satisfies its contractual requirements.
	- functional acceptance testing



## Who with whom?
- pair testing, mob testing
- developer testing
- crowd testing: An approach to testing in which testing is distributed to a large group of testers.



## Quality Characteristics
- functional and non-functional
- performance testing, load testing, stress testing
- accessiblity, accuracy, compliance (conformance testing, regulation testing, standards testing), endurance, installability, interoperability, maintainability, portability, recoverability, reliability, robustness, scalability, security, suitability, usability



## Architecture
### Scope
- unit, component, module, system, full-stack, end-to-end
- integration, unit integration, component integration, system integration, pairwise integration, hardware-software integration, neighborhood integration, big bangg, bottom up, incremental
- api, ui
 
### Seam
unit, api, cli, gui

### Device
browser, mobile, tablet, desktop



## Say what?
- Confirmation testing (re-testing): Dynamic testing conducted after fixing defects with the objective to confirm that failures caused by those defects do not occur anymore.
- Exhaustive testing (complete testing): A test approach in which the test suite comprises all combinations of input values and preconditions.
- Failover testing: Testing by simulating failure modes or actually causing failures in a controlled environment. Following a failure, the failover mechanism is tested to ensure that data is not lost or corrupted and that any agreed service levels are maintained (e.g., function availability or response times).
- Field testing: A type of testing conducted to evaluate the system behavior under productive connectivity conditions in the field.
- Invalid testing: Testing using input values that should be rejected by the component or system.
- operational testing: Testing conducted to evaluate a component or system in its operational environment.
- maintenance testing: Testing the changes to an operational system or the impact of a changed environment to an operational system.



## Out of scope
- test techniques, e.g. modified condition / decision testing