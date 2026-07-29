# SW-HW Developer Testing Pull Request Review Checklist

## PR reviewed and approved by:

[Review Checklist Guidelines](https://cc-github.bmwgroup.net/swh/safe-posix-platform/blob/master/platform/aas/docs/guides/05_contributers_guide/inspections/assets/test_inspection.md)

## General test case quality criteria

1. Are test case annotations (ASIL, Priority, TestType, Verifies, Description, DerivationTechnique) complete, plausible and comprehensible?
   - [ ] OK:
   - [ ] NOK / NA : [enter text here]
2. If non-trivial: are prerequisites and expected results defined?
   - [ ] OK:
   - [ ] NOK / NA : [enter text here]
3. In case the test modifies the default state of the ECU: does the test contain a teardown function? (Any action shall have an effect on the overall state of the DUT.)
   - [ ] OK:
   - [ ] NOK / NA : [enter text here]
4. Is the specified test type (Requirements-based test, Interface test, Fault injection test, Resource usage evaluation, Verification of the control flow and data flow) adequate for testing as specified in the test case description?
   - [ ] Requirements-based test
      1. Is the ASIL set correctly? (set the highest ASIL of all referenced requirements)
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
      2. Are all requirements which are tested according to the test description traced to the test case? (attribute Verifies)
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
      3. Referring test case changes - is the test description still up-to-date with respect to the requirement(s)?
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
      4. If referenced requirement has separate verification criteria: is the test case consistent with the verification criteria?
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
   - [ ] Interface test
      1. Is the test case traced to detailed design/ architectural design? (attribute Verifies)
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
      2. Does the interface in the test case description comply with the detailed design or architectural model specification?
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
      3. Are the integration, interaction and dependencies between SW Components or Features correctly verified? Is data flow, message passing and the synchronization mechanisms between interconnected modules considered?
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
   - [ ] Fault injection test
      1. Does the test case description provide information about the necessary test steps, injection points, input data, measurement points and the the expected results?
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
   - [ ] Resource usage evaluation test
      1. Does the test case as specified in the description consider system's behavior under different loads or stress conditions or resource constraints?
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
   - [ ] Verification of the control flow and data flow
      1. Does the test case verify the integrity of the control flow - this can enclose the order of function calls, instructions and statements as well as the amount of time for the individual steps OR of the data flow during the communication across SW Components tested?
         - [ ] OK:
         - [ ] NOK / NA : [enter text here]
   - [ ] Other: [enter text here]

---
