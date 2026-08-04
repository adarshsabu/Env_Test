# SW-HW Integration Testing Pull Request Review Checklist

## PR reviewed and approved by:

[Review Checklist Usage Guidelines](https://asc.bmwgroup.net/wiki/x/9PkyNg)

## Formal test case quality criteria

1. Does the test case follow the ITF rules? See [04.02.xx How to write an ITF test case](https://asc.bmwgroup.net/wiki/x/nHscKw),  [04.02.xx How to write an ITF test case-Rules](https://asc.bmwgroup.net/wiki/x/nHscKw/#id-04.02.xxHowtowriteanITFtestcase-Rules)
   - [ ] OK:
   - [ ] NOK / NA : [enter text here]
2. Does the test case follow the "ITF Assertion and Expectation" guidelines? See [04.02.xx How to write an ITF test case](https://asc.bmwgroup.net/wiki/x/nHscKw), [04.02.xx How to write an ITF testcase-ITFAssertion and Expectation](https://asc.bmwgroup.net/wiki/x/nHscKw/#id-04.02.xxHowtowriteanITFtestcase-ITFAssertionandExpectation)
   - [ ] OK:
   - [ ] NOK / NA : [enter text here]
3. Are test case annotations complete and correct?
   1. Does the test case contain all the mandatory fields for metadata and extended metadata? See [04.02.xx How to write an ITF test case](https://asc.bmwgroup.net/wiki/x/nHscKw), [04.02.xx How to write an ITF testcase-Metadata information](https://asc.bmwgroup.net/wiki/x/nHscKw/#id-04.02.xxHowtowriteanITFtestcase-Metadatainformation)(Will be removed once linting check is enabled for all the fields, check only partially )
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   2. Is the Metadata and extended metadata of the test case is correct?
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   3. Does the description clearly state the objective of the test case.
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   4. Is the Status of the TC set to one of the expected values? See [04.02.xx How to write an ITF test case](https://asc.bmwgroup.net/wiki/x/nHscKw), [04.02.xx How to write an ITF testcase-Values in IPNextProject](https://asc.bmwgroup.net/wiki/x/nHscKw/#id-04.02.xxHowtowriteanITFtestcase-ValuesinIPNextProject)
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   5. Is the ASIL level set according to the requirements in "verifies" field? (the ASIL level of the test specification is the higher ASIL level of the requirements in "verifies" field)
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]

## Test case implementation appropriateness

   1. Does the test case specify the input/outputs, expected results and pass/fail criteria?
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   2. Does the test case implementation really verify what is specified in the test case description?
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   3. Does the test case implementation really verify the requirements given into the "verifies" field?
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   4. Is the test case implementation efficient with respect to execution time?
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   5. Is the test case implementation free from coding errors?
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   6. Does the test case implementation comply with relevant coding guidelines? See [04.02.xx How to write an ITF test case](https://asc.bmwgroup.net/wiki/x/nHscKw)
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   7. Does the test case contain all precondition steps in the setup phase of the test case specification? (everything not directly related to the test itself but necessary to start the test should be in the setup)
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
   8. Does the test case contain all the tier-down steps to remove/clean-up all the persistent changes done in the test case?
      - [ ] OK:
      - [ ] NOK / NA : [enter text here]
  
<!-- END_INTEGRATION_CHECKLIST -->
---
