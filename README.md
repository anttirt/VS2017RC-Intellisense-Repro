1. Open solution `ExternalLinkTest\ExternalLinkTest.sln`
2. Verify that the solution builds without errors
3. Inspect Class1 and Class2
4. Expected: No intellisense errors shown
5. Result: In Class2, which is linked from outside the project folder, an "ambiguous reference" error is reported by intellisense, and Intellisense actions that depend on that reference are unavailable
