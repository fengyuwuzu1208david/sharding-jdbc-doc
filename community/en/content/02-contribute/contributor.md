+++
title = "Contributors' Guide"
weight = 1
prev = "/02-contribute/"
next = "/02-contribute/committer/"
chapter = true
+++

You can report a bug, submit a new feature enhancement recommendation, or commit codes by a pull request.

## Reporting Bugs

 - Before report a bug, please search from google to confirm you cannot find any hint on it.
 - Look [issues List](https://github.com/shardingjdbc/sharding-jdbc/issues) to confirm this issue is not a duplicated one.
 - [Create](https://github.com/shardingjdbc/sharding-jdbc/issues/new) a new issue.
 - Define a clear and descriptive title for the issue.
 - If bug reported, please provide information below:
       - Details for reproduce bug step by step. Include SQL, configuration, expected results, actual results and tracing log.
       - Sharding and Operation System version.
       - Source code to reproduce bug on github cna copy the link here.
       - Stack trace if exception thrown.
       - Screenshot and animated gif to help bug reproduce if necessary.
       - Screenshot for CPU, Memory, Network and IO stat if performance issue.
 - If enhancement recommendation reported, please provide information below:
       - Details for enhancement behaviour.
       - Explain why this enhancement is general feature for most developers.
       - List similar features which already available in other product if possible. Both open source and commercial software are available.
 - Assign label after create issue. Label should be bug, enhancement, discussion and so on.
 - Please pay attention on the issue and provide more information during discuss.
 - Please close issue when it is resolved. If you don't close it, we will close it after 3 days。
 - If this issue has new information, please reopen it again. Please note, issue can reopen which only closed by yourself. If the issue is closed by us, you have no permission to reopen any more.

## Commit pull request

 - Please choose a interested issue, or create a new issue and then settle a correct label.
 - Reply a deadline message to pickup this issue. 
 - Find a mentor in [Core developers list](/01-organization/), he will give you feedback for design and implements.
 - Fork to your github repo and begin to work.
 - Please follow Sharding's [Development conventions](/03-convention/), and complete check before pull request submit.
 - Submit a pull request to dev branch when finished, please do not submit pull request to master.
 - Mentor will do code review and discuss some details, include design, implement, performance and code style. Code will be merged until mentor accepted.
 - Finally, congratulations that you have become the official contributor for Sharding!
