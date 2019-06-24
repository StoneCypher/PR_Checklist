# PR_Checklist
Things I should remember to check when reviewing a PR

## What's this?
I believe in [The Checklist Manifesto](https://www.amazon.com/dp/B0030V0PEW/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1), in [Standard Operating Procedure](https://en.wikipedia.org/wiki/Standard_operating_procedure), and in [Watts Humphrey](https://www.sei.cmu.edu/about/leadership/display.cfm?customel_datapageid_2623=3005)'s research.  Results from [The Toyota Way](https://en.wikipedia.org/wiki/The_Toyota_Way), [PDCA CPI](https://www.army.mil/article/41051/continuous_process_improvement), the [W Edwards Deming Institute](https://deming.org/), and [CMM/I](https://en.wikipedia.org/wiki/Capability_Maturity_Model_Integration) seem clear.

Checklists matter.

I should have more of them.

I invite friends and collagues to contribute as they see fit.  Forks and PRs are win.

<br/><br/>
# General
1. Does the code seem high quality
    1. [ ] Is it correct
    1. [ ] Is it well written
    1. [ ] Are there no obvious major improvements
    1. [ ] Does it cover all the obvious cases
    1. [ ] Does it look like it will complete extreme realistic workloads without resource failures
    1. [ ] Does it look like it will be adequately reliable
    1. [ ] Does it look like it will be adequately fast
    1. [ ] Are names well and clearly chosen
    1. [ ] Is the approach sufficiently obvious
    1. [ ] Has everything unnecessary been removed
    1. [ ] Are all unnecessary library dependencies removed

<br/><br/>
# Web specific

<br/><br/>
# Testing specific
1. [ ] Has coverage stayed at-previous or better
1. [ ] Is there genuinely adequate coverage of the testable new material
    1. [ ] Are there negative cases
    1. [ ] (Optional) Are there randomized cases
1. [ ] Is the testset closing as-fast-scaled or faster than before
