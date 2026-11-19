# WheelFeel Builder

Public GitHub Actions runner configuration for testing Windows builds of the private WheelFeel project.

**No WheelFeel source files or credentials belong in this repository.**

First, run the manual workflow **Test free Windows runner** to verify that GitHub Actions can start in this public repository despite the account's exhausted private-repository allowance.

Do not create an access token until this basic test succeeds. Future private-source checkout will require a fine-grained, read-only token stored in an Actions secret, and builds/logs/artifacts in this repository must be treated as public.
