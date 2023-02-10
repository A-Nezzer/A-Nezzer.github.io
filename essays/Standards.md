---
layout: essay
type: essay
title: "Standards"
# All dates must be YYYY-MM-DD format!
date: 2023-02-09
published: true
labels:
- Software Engineering
- Coding
- Coding Standards
---
Good coding relies heavily on collaboration. Stack overflow is a thriving community of coders who all work together to ensure we all do better when we work. This collaboration, however, would be very hard if every person's code was organized differently. As such coding standards were made to properly regulate coding to be as universally understandable as possible.

A problem arises, however, when the set regulations are too overbearing. For example the following code:
```
function name(){
    return null;
}
```
is not standard, while this code:
```
function name() {
    return null;
}
```
would be fine, simply because it is standard in ESLint to add a space before the open bracket on functions. While I understand the existence of a streamlined coding environment allows for more streamlined collaboration on code, I think getting too specific on these things can lead to time wasted. Rules are important, but too many become overbearing and redundant.