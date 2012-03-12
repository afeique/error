# error class
by afeique sheikh

## description
This is a simple PHP class for succinctly throwing exceptions representing errors. Its primary usage is for throwing an exception when the expected input requirements for a function are not met.

## usage
Usage is straightforward:

    throw error::expecting_string();

Will throw an exception saying _expecting string_.

## comments
Nothing spectacular. Created a github repo for versioning control across multiple projects.

A slight warning: this class is purposely not enclosed within a namespace. You may want to enclose it within a namespace yourself.
