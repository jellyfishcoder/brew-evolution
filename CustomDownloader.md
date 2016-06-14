$Custom_Downloaders
Introduction

Add the ability to customise the commands used to download resources in homebrew. 

Motivation

Though curl is by default installed on macOS, other, sometimes faster/less resource consuming download managers exist. Though you could modify the source code and replace the curl commands with another download manager, this would be very complicated and potentially harmfull to your installation. Also, it would not allow you to easily switch between downloaders.

Proposed solution

Add a simple interactive command, something like `brew chdownloader`, which would prompt the user to enter the location of the commands, like `/usr/bin/t

Detailed design

Describe the design of the solution in detail. The detail in this section should be sufficient for someone who is not one of the authors of this proposal to be able to reasonably implement the feature.

Alternatives considered

Describe alternative approaches to addressing the same problem and why you chose this approach instead.
