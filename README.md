# CS 405 – Secure Coding Portfolio  
Jessica Johnson  
Southern New Hampshire University  

## Course Overview

This course focused on secure coding practices in C/C++ and how to integrate security into the full software development lifecycle. Instead of treating security as something added at the end, we approached it as something that must be built in from the start.

Throughout this course, I worked on developing and applying secure coding standards, performing static analysis, evaluating vulnerabilities, and implementing defensive programming techniques.



## What I Learned

### Secure Coding Standards
I created a full secure development policy based on widely accepted security principles. This included:

- Input validation
- Preventing buffer overflows
- SQL injection prevention
- Integer overflow protection
- Proper exception handling
- Avoiding unsafe randomness
- Memory safety using RAII and smart pointers

I learned how small coding decisions (like implicit type conversion or unchecked input) can introduce real security risks.



### Risk Assessment & Policy Development
For Project One, I developed a secure development policy for a fictional company (Green Pace). This required:

- Defining 10 secure coding standards
- Performing risk assessments (severity, likelihood, remediation cost, priority)
- Mapping standards to security principles
- Creating encryption policies (at rest, in flight, in use)
- Implementing the Triple-A framework (Authentication, Authorization, Accounting)

This project helped me understand how security is documented, enforced, and governed in real organizations.



### Static Analysis & Automation
I compared static analysis tools such as:

- SonarQube
- CppCheck
- Visual Studio warnings

I learned how automated scanning tools can detect:
- Uninitialized variables
- Unsafe type conversions
- Buffer overflows
- Memory leaks
- Improper exception handling

More importantly, I learned how these tools fit into a DevSecOps pipeline, where security checks are automated during build and deployment.



### DevSecOps & Defense in Depth
One of the biggest takeaways for me was understanding defense in depth. Security is not just one control, it’s layers:

- Input validation
- Parameterized queries
- Compiler warnings
- Static analysis
- Logging
- Encryption
- Access control

I also learned how automation strengthens compliance by enforcing standards continuously instead of relying on manual review.


## Technical Skills Developed

- C++ secure coding practices
- Static code analysis interpretation
- Secure policy writing
- Risk assessment modeling
- Encryption standards (AES-256, TLS)
- Triple-A framework implementation
- DevSecOps integration strategy


## Personal Reflection

I started this course thinking secure coding mostly meant “don’t write bad code.” I’m leaving it understanding that secure software requires structure, policy, automation, and layered protection.

This course strengthened my awareness of how security decisions impact real systems and real users. It also helped me think more critically about how to design systems that fail safely instead of failing dangerously.



## Included in This Portfolio

- Project One – Secure Development Policy  
- Project Two – Presentation on Secure Coding  
- Coding Project Source Files  
- Portfolio Reflection  



Secure coding is no longer something I see as optional or secondary. It is foundational.
