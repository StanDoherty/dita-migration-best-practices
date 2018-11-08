# DITA Migration Best Practices for Workgroups (DRAFT IN PROGRESS)
First pass at collecting best practices for small- to medium-sized teams migrating to OASIS DITA

So - your workgroup or division is considering a migration to DITA, but your management team has not made firm commitments to you about:

* Increased operating budget
* Increased staffing
* Relief from continuous release deadlines

You are tasked with developing a migration proposal in the absence of guarantees that these supporting commitments will be in place. How might *you* approach this task based upon the collective experience of other startups, workgroups, or divisions that have successfuly completed a migration?

In short -- be conservative, be realistic, be agile. In OASIS meetings, we often describe DITA simultaneously as "highly beneficial" and "highly disruptive." It's only human nature to focus on the former, all those tantalizing DITA mapping, metadata, processing, reuse, and conditionalization features. What tends to kill DITA migration projects are all the disruptions, all the change management and process re-engineering work that is rarely apparent when you are reading about DITA or doing a preliminary pilot project. The big companies with access to dedicated tool engineers, information architects, conversion budgets, and consultants can recover from mistakes in planning or execution; workgroups without a lot of support cannot.

I like sailing analogies. No sailboat can sail directly into the wind, it must tack to port and starboard periodically to fill its sails and stay on course as best it can. A sailing ship that is "close to the wind" is one that can make good headway into the wind with only minor course deviations, say 10-degree or 20-degree tacks. "Heavy sailers" are ships that need to make more significant course deviations to stay on course, say 30-degree or 40-degree tacks. Big companies moving to DITA can afford to be heavy sailers; they have a huge payoff when they get to port -- even if it takes longer to get there. If a workgroup migration can afford only 15-degree tacks to stay on budget or on schedule and it veers off on a 40-degree tack, the migration is probably over. 

Making mistakes and course corrections during a DITA migration are inevitable. Expect them. The following best practices for workgroup DITA migrations are designed to reduce the amount of time or effort that is required for you to recover, to get back on the right tack. Let's take an example. If your workgroup does not have an experienced DITA architect on board (and most do not), you are going to bump into lots of little surprises and gotchas. No avoiding them. If you have made technology and design choices that maximize the ability of DITA experts and user groups in the community to help you out when you veer off course, your mean recovery time will be short. If many of your "surprises" are familiar issues to people on the DITA support lists or attending local DITA meetings, you'll get the help that you need quickly. If you adopt highly proprietary technologies or highly customized designs too early in your voyage, you will have limited the ability of people outside your workgroup to help you get back on course. Heavy sailing. 

## Types of DITA migrations

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |



| Organization | Writers | Dedicated DITA staff | DTDs | Transforms | Content management | Cross-org integration |
| ---- | ----- | ----- | ----- | ----- | ----- | ----- | -----|




Workgroup

Departmental

Enterprise 



The following best practices serve as input to your migration planning process. Adapt and season to taste. 

## Align your DITA migration goals to management priorities

Customers do not care how we author content. They want accurate, complete technical content delivered to them as they use our products to solve business problems. Our management organizations *do* care how efficiently we author, curate, build, translate, and distribute product content. DITA was designed to address some of the major causes of inefficiency in book-oriented content development:

1. *Low content reuse within and across organizations*: Results in costly re-implementation, re-testing, and global inaccuracy. 
1. *Poor separation of content from formatting*: Results in lower writer productivity and reduced ability to reuse content between output formats.
1. *Poor separation of content from context*: Results in duplicating similar content many times to satisfy minor variations in context (links, product names, platforms). 
1. *Low source consistency*: When the authoring environment imposes no restrictions, consistent is entirely discretionary.
1. *Low output consistency*: When individual source files contain style overrides or local formatting, the generated output can vary significantly.
1. *Inconsistent information architecture*: When the authoring environment does not require that similar types of information be structured similarly, any type of product content might be mixed with any other. 
1. *Impoverished metadata and semantic markup*: When the authoring environment does not encourage content developers to tag content for semantic meaning or to add descriptive metadata, downstream systems (SEO) and systems (bots) have a more difficult time leveraging information. 
1. *Opaque content management*: When the authoring environment cannot determine where content lives and how many dependencies there are between pieces of content, the content is really controlling the team -- not the team controlling its content. 
1. *Poor content collaboration with engineering*: When the authoring environment does not support engineering-friendly formats such as Markdown, ReStructuredText, or even MS Word, the ability of engineering peers to contribute significantly to content development is low. 

The DITA standard and its supporting tools can help with all of these issues, but *it takes time*. If a workgroup attempts simultaneously to learn DITA, convert its content to DITA, implement DITA tooling, standardize its markup, customize its outputs, and achieve significant reuse, it will almost certainly fail. 

If the two highest pain points for management are lack of content/formatting separation and source inconsistency, just converting your current sources into DITA and running themn through some company-branded verson of the DITA Open Toolkit transforms will help tremendously. Make those goals #1 and #2 for the first year. Reuse, metadata, and consistent IA become issues for subsequent years or phases. 

If management primarily wants to see increased collaboration between writing, engineering, support, and marketing professionals, you want to move you existing content to XML DITA while ramping up Lightweight DITA extensions for Markdown and HTML5. Content management and output consistency become candidates for subsequent years or phases. 

Set expectations with *everyone*. Be ruthless in deferring nice-to-have enhancements. 

## Build multiple phases into your plan

## Adopt technologies and designs that maximize the ability of people outside your workgroup to help you

* Industry standards (DITA)
* Standards-compliant commerical software (DITA editors) 
* Open source software (DITA Open Toolkit)
* Common engineering infrastructure software (Git, SVN, Jenkins)

## Commit to support your staff

## Make the migration a budgeted project, not a late-nights and weekends affair

## Develop a 360-degree communications plan



