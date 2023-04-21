## Incomplete issues planning:
- Two-factor authentication when accessing the repository. Difficulty: Easy Priority: Medium
- Solution: Google Authenticator is a great two-factor authentication tool that will be implemented in the future.
- Implement encryption methods to perform commits. Difficulty: Moderate Priority: Mediium
- Solution: Encrypt a file by generating and transfer the decryption key or set a password on the file.
- User error input logging will be implemented. Difficulty: Moderate Priority: Low
- Solution: Implement a local Version Control System or keep track of the loggin database.

https://github.com/phanandco/security-project-code-copy-2/commit/285e0282a6eae1ae6eff70677d956a916dfb30d2

### Fix 1: using namespace std is removed
- By including "using namespace std", you declare all namespace as global. Including using namespace std in the header is limited to the function or class scope.
### Fix 2: Redeclared different shapes as entity classes.
- Declaring classes allows data encasulation, follows Oject Oriented Programming practices, improve tracibility and maintainability withion the code. Declaring classes controls access to data and functions, that could result in
unwanted alterations to sensitive information.
### Fix 3: Implement of smart pointers that would potentially eliminate bound issues.
- Improve memory allocation and deallocation. Smart pointers eliminate memory leaks.

## The addition or use of an online repository has increased security related to Access control and Code Sharing/Distribution by:
- Access control
- Authorized alterations
- Improve collaboration
- Intergrated version control system.


## To perform security testings:
- Perform SQL injections.
- Evaluate project weaknesses.
- Introduce the use of OWASP ZAP for security testing.
