learning objectives
* isolating chunks into separate functions for testing, reuse, readability, and practice
* increased intentionality to variable & value usage (limiting chunks to 2-3 args + 1 return value)
* abstraction - "i care what it does, not how it does it"
* implementation-independent, declarative functions. a starting point for functional programming

the questions:
* what to name the refactored function?
    * if you're reeaally struggling to find a strategically meaningful name, consider a different refactor
* what variables are used in this chunk?
* which values come from before? - arguments
    * a good refactor should need no more than 3 args
* which values are used after? - return value
    * a good refactor should only need one return value
    * in some rare cases you can return a data structure with 2-3 values
* can any values be derived from other variables available within the refactor?


exercise: given a snippet of code
1. determine it's behavior with test cases
2. determine it's implementation by expanding
3. determine it's strategy with chunking
4. abstract chunks to functions
5. reimplement the abstracted chunks