 Python and Serverless / guideline
 ========
 
 Python and Serverless standards to go by.
 
 ## Source code
 
 ```text
 
 1. Follow rules defined in PEP-8.
 2. Source code follow "clean code" DRY and SOLID principals,  if it is hard to achieve at one sprint, create ticket for “cleaning” in new sprint.
 3. Consider if some bunch of code you create is generic, and can be reused in other projects. Place it in dedicated directory and only register in SF through a bundle. That cases should be calmly discussed with other programmers.
 4. If new service class, method is delivered – it is covered by unit tests in at least 90% level.
 5. In aws apis each lambda function should be named after the file name where it's contained.
 ...

```
 Serverless examples https://github.com/serverless/examples 
 
 PEP-8 https://www.python.org/dev/peps/pep-0008/
 
 
## Editor settings

```
1. Empty line at end of the file.
2. Four spaces indentation. 
...
```

## Unit tests

```
1. All unit test passes.
2. Unit tests does not affect real external resources like database, file storage, external APIs, etc.
3. Repeating: unit test does not depend on third party vendor code e.g. propel, amazon S3 SDK, etc.
...
```


 
 



