---
title: "Automation Anxiety"
date: 2025-11-10
categories: great-abstraction-tragedy
---

![Code review window](/res/code-review.png)

# 🚧 [The Great Abstraction Tragedy #4]

## Code Reviews

*once we read code*  
*now we perform ceremonies*

---

**2007**:  
You emailed a patch.  
Your teammate read it line by line,  
sometimes out loud.  
They cared about what it did -  
not how many spaces it used.  
If it made sense, they merged it.  
If not, they called you over.  
The discussion was short,  
and full of engineering.


**2025**:
You open a pull request.  
The first comment arrives before anyone reads a line:

> "Can you add a JIRA ticket to the title?"

The pipeline runs.  
The linter finds a missing semicolon in code you didn't touch.  
You fix it.  
Now another check fails — *"expected 120 chars per line, found 121."*  
You stare at it for a while,  
then delete one adjective from a variable name.  
Build green.  
Finally.

The first reviewer asks for *"just one small change"*  
The second wants a new abstraction layer.  
The third hasn't read the diff but feels compelled to say:

> "LGTM 👍"
> to appear *involved.*

You spend more time defending the indentation  
than explaining the algorithm.  
And when it merges,  
no one remembers what the code was for.  
But the PR description is immaculate.

---

We've turned *reviews* into *rituals.*  
Not to find bugs — but to find belonging.  
A shared performance of correctness.  
We debate naming conventions as if they were theology,  
and treat merge approvals as social currency.

Somewhere along the way,  
"Looks good to me" stopped meaning  
"I understand what this does."  
It now means  
"I trust the system more than I trust myself."

---

Once, review was about trust.  
Now it's about *process*.  
We automate empathy,  
lint conversation,  
and measure collaboration in comments per commit.

The tragedy isn't the bureaucracy.  
It's that we built all this ceremony  
because we stopped believing  
anyone could still read code  
and simply *know*.

---

**#GreatAbstractionTragedy #SoftwareEngineering #ProgrammingHumor #TechCulture
#LegacyCode #DevLife**

---

![Code Reviews](/res/code-reviews.png)
