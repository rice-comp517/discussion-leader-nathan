# Review

## Info

Reviewer Name: Nathan Eigbe

Paper Title: Limiting the Damage Potential of Discretionary Trojan Horses

## Summary
Karger discusses various methods to detect and deter applications that seek to
illegaly access or modify existing files.

### Problem and why we care
The existance of malicious programs is an issue plaguing computer owners. We want
users to be able to know what any given application is doing to their computer and
control said application.

### Gap in current approaches
Current common approach separates information into classes, and prevents info from higher classes being 
leaked to lower classes. This method doesn't work for discretionary environments such as access control 
lists or capability lists. 

### Hypothesis, Key Idea, or Main Claim
The Name Checking Subsystem is the optimal design standard for tracking
Trojan Horses in a discretionary environment.

### Method for Proving the Claim
The paper compares the NCS with other popular methods for 
deterring Trojans, such as the Need-To-Know framework 
and explains why they are less efficient or robust than the NCS.

### Method for evaluating
The paper details various roadblocks that the framework
may encounter (Batch File Access Commands, Connecting the User to the Name Checking Subsystem) 
and expleins how each of these issues may be sidestepped.

### Contributions: what we take away
While the lack of any concrete data provides any details
to take away, the article does provide a number of intuitive 
security strategies that are worth implementing, particularly 
in the discretionary environment.

## Pros (3-6 bullets)
- Method is ultimately unintrusive
- Clearly lists out the goals and accomplishes them
- Provides alternatives and explains why the NCS is better

## Cons (3-6 bullets)
- Directory Tree Idea lacks user-friendliness
- Framework only applies specifically to the discretionary environment
- Explanation on Trojan could have been more in depth

### What is your analysis of the proposed?

The NCS brings up some intuitive design choices in 
avoiding Trojans though it's case it doesn't provide any 
hard data performance wise on how a discretionary system 
using the NCS would surpass a non-discressionary system
simply using a class system. Overall the general premise is
sound though a bit more depth on this issue would've been
appreciated.


## Details Comments, Observations, Questions

What systems use the NCS as a security feature? 
Do any features from the NCS apply to non-discretionary systems?


