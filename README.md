Project overview:
    npm kind of sucks because of shit like leftpad ruining it for everyone.
    There is a proposal to make a node standard library.  This standard library will likely take 3-5 years to come to completion.
    There are a constellation of moderately sized libraries that form a defacto standard library.  We will create a metric to detect such defacto standard libraries, then search npm for libraries that seem defacto standard.
    De-facto standard libraries will be pulled into the project or re-implemented on a per lib basis

Project workflow:
    list all npm packages
    for every npm package run users/LoC, users/cyclomatic complexity, etc.
    Any package with a high score (meaning it is used by many and takes little work) we will target for re-implementation.
    And we will continue


