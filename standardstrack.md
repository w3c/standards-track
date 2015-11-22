# Best Practices for Bringing Work to the W3C Recommendation Track

## Status

Last updated on 2015/11/21



Distributed to the W3C Advisory board for discussion

# Table of Contents
1. [Purpose](#Purpose)
2. [Readiness Criteria for Recommendation Track](#Criteria)
3. [Additional Considerations](#Considerations)

## Example


## Purpose
Open source browser projects use an [intent to implement]() process to build the case for shipping 
a new feature. The  [Web Platform Incubator Community Group] ([https://wicg.github.io/admin/intent-to-migrate.html) has adopted 
something similar to determine when a spec under incubation is ready to propose to a Working Group.

https://www.w3.org/2015/10/27-ac-minutes.html#item02
- Incubation isn't a silver bullet to be applied to every situation
- If a CG incubates a spec that gets implemented in the browsers, it's hard to motivate them to take it to a WG for broad review
- If the CG did not work by consensus, the de facto standard might be imposed by a single strong editor or cabal of the top browsers
- There may be gaps in the patent commitment if all spec contributors don't join the WG
- He used Google AMP as an apparent example of a browser implementer developing an HTML-related technology without any input from others at W3c.

## Criteria 

Thanks for the pointer.  As I read Arnaud's comments he's saying:


But Arnaud's core concern was that incubated specs might have so much momentum that the WG will rubber stamp it. Or to put it differently, it gives implementers too much power.    But Alex's argument is essentially that the status quo doesn't give implementers enough respect, and WGs without a reality check from implementers tend to create specs that don't get used in the real world.

So I think it would be valuable for the AB to seek the right balance here.  Getting back to Jeff's questions and trying to answer them from this thread and the TPAC discussions ....


> 1. Insist on incubation together with putting a burden on proposers to explain why the standard would be implemented, etc.

>    To some extent the WICG --> Web Platform process already does much of this, which is beneficial for a big part of the platform.

>     Is the agenda+ to require this everywhere?  I thought Arnaud gave some rationale why you might not want that everywhere.



I do think there should be best practices guidance / team policy to favor WG proposals that have been successfully incubated in WICG, another community group, or some other community that includes lots of W3C members. We heard pushback in Sapporo that it would be a bad idea to *require* this of *all* proposed WGs, but even Arnaud (in private conversation) didn't seem to object to  SHOULD guidance about when to transition to a WG.  As I see it, a good balance between the concerns of Alex and Arnaud might be stated as:



Transition should happen  ...

NO SOONER than criteria such as those in https://wicg.github.io/admin/intent-to-migrate.html are met.

NO LATER THAN the spec is still fluid,  not frozen into shipping code used on many websites.



So I propose that the AB (and/or the Process CG) fork https://wicg.github.io/admin/intent-to-migrate.html to create something like the  normative reference policy http://www.w3.org/2013/09/normative-references  but the section might say "This document explains considerations the Director takes into account when evaluating proposals to create a WG or add new scope/deliverables to an existing Working Group. These considerations may be used by proponents to assess whether the work is ready for the Recommendation Track. The Director may refer to this document when a transition request is being decided.  The Director may consider other factors not listed in this document as well, and meeting all these criteria does not guarantee the Director will approve a proposal."



> 2. Ensure that chartering is "not so much a political exercise of lobbying, voting, and horse trading".

>    Definitely agree with that.  But is there a proposal - other than doing point 1 above?

We need a collaborative effort to draft the criteria listed in the document I propose above.  These criteria should be based on empirical evidence when possible and consensus judgment as necessary.  That is, we should attempt to use rigorous data gathering and analysis to find criteria that distinguish successful from unsuccessful W3C standardization efforts, while recognizing that subjective judgment about what "success" means and how to codify difficult-to-measure concepts may be necessary.

  Here's a strawman proposal to start discussion,  based on the Intent to Migrate criteria (and my subjective judgment :)) :

There are several factors that the Director needs to consider when assessing whether a spec is ready for the Recommendation track:


1.      Socialized proposal: A draft spec should be written down (or at least sketched out) and have been discussed in a community where website developer, framework/took developer, and core technology implementers are represented.

2.      Benefits: Proposers should have explained why the Web needs the feature this spec enables.  What are developers forced to do without this feature in the Web Platform? Why is that a problem? To what extent would having this feature broadly deployed alleviate the problem? What fraction of websites are implementing a similar feature in a non-standardized way?How many users would potentially benefit from this feature if standardized? [extra credit for data backing up these claims]

3.      Risks: What are the potential downsides of having this feature standardized?  Could it undermine security, privacy, accessibility, etc. if broadly deployed? Are there scenarios under which we would regret standardizing this feature?

4.      Experience: has a similar feature been attempted previously?  If it was not widely adopted, why not, and why is this proposal more likely to succeed?

5.      Interest: Which types of products (browsers, servers, frameworks,  applications...) would need to support the spec for it to be successful?  Are the appropriate implementers in the discussion about the value proposition for the feature?  Is there a critical mass of implementers tentatively interested in shipping this feature if standardized?

6.      Evidence: What implementation and user experience is there to back up the points above?

Bottom line:  I would like to move to a situation where W3C doesn't create a WG when people recognize a problem that falls within W3C's area of expertise, but once a tentative solution is identified and analyzed.  That doesn't mean the WG can just rubber stamp the proposal, it means the proposal is ready for broad and careful analysis of its usability, security implications, potential impact on privacy, accessibility, sustainability, etc. Finding the right balance between the narrow, pragmatic concerns of those incubating a spec and the broad, principle-driven concerns of the broader membership affected by it will be a challenge but that is what we members pay dues to hire a team to do!


### Is there a draft spec?

The Director consider

There are several factors that the Director needs to consider as part of a stability assessment.

### Was the draft incubated by relevant stakeholders?

## Clear RF Licensing Commitments

W3C seeks to issue Recommendations that can be implemented on a [Royalty-Free](http://www.w3.org/Consortium/Patent-Policy-20040205/#sec-Requiremenst) basis.

What are the licensing terms of the draft documents?

1.  Are the technologies in the initial available under terms that are compatible with the [W3C Royalty-Free licensing requirements](http://www.w3.org/Consortium/Patent-Policy-20040205/#sec-Requirements)?
2.  Do the references in the initial draft conform to the W3C normative reference policy?


