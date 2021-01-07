# Questions for Engineering Leaders

Good answers to these questions will help an engineering team deliver on its purpose. These questions suggest guideliness appropriate for a Series A company in a lightly-regulated industry.

These questiosn aren't appropriate for everyone or every stage of the company, but they are a good list of practices I've used over the years in enterprise or SMB SaaS.

## Team

* How will demands on the organization change in the next 12 months? (e.g. decline, steady, linear growth, expontential growth.)

* What will the organization need to look like in 12 months?

* What new skills does the organization need to develop?

* Do managers have enough time for weekly 30min 1-1 meetings with each report and with key stakeholders?

## Hiring

* What roles will be needed in 12 months?

* How much lead time will you need for each hire?

* Do you have a consistent and documented process for hiring, including sourcing, interviewing, offers, and closing?

* Does each new hire update the onboarding document?

* Who are the referral magnets?

* Do you proactively solicit referrals from new hires?

## Goal setting

* What are the top OKRs for the company for the next quarter?

* How do your OKRs support the company OKRs?

* Do you set OKRs for you team and review them to down and across the team?

Use OKRs for:

* Alignment

* Prioritization

* Accountability

* Transparency

* Stretch

* Measurable

* Red, Yellow, Green status

* Reviewed and revised regularly

* Support behaviors and values

## Product

* What the customer personas?

* Is the value to the customer clearly understood and measurable?

* Is the product roadmap aligned with customer success?

* Are designs and mocks iterated with customers?

## Process

* Do you have a sprint planning process?

* Do you have daily standups?

* How are code reviews managed?

* Are items from the retrospective actioned?

## Ready for Launch

* Do you have end-to-end tests?

* Do you have real-time monitoring in place?

* Do you have runbooks and contingencies for handling different failures?

* Have you done a security review and is PI safe?

## Operations

* Are services monitored?

* Are logs searchable?

* Are services protected?

* Are secrets protected?

* Are appropriate and required operational controls followed?

* Can services be deployed individually without downtime?

* Is there an incident response runbook?

* Is there a runbook for a suspected data leak or breach?

* Is someone on-call responding to alerts?

* Is there an RCA process?

## Customer Success

* Is the customer at the table? i.e. does the team reflect on the customer when making decisions? How is the customer voice heard in the organization?

* Is there status page displaying interruptions in service?

* Are RCAs shared with key stakeholders, including customers?

* How is customer success involved in product and engineering decisions?

* How are product and engineering involved in customer success?

## Feedback 

* Can users submit feedback?

* How is customer feedback synthesized?

* Is customer usage tracked and correlated to value?

* What is the Net Promoter Score?

* Do some customers get preferential treatment?

## Architecture

* Are there architectural, security, and design reviews?

* Is the system architectural diagram up to date?

* Are architectural documents versioned and in text/markdown?

* Is the system modular and decoupled?

* Are end-points secure?

* Is PII encrypted in flight and at rest?

* Is there an architectural and tech debt roadmap?

* Is the team given time to refactor and work on debt?

* What are the replicatable units that allow the system to scale without bottlenecks? Express you system in `O` notation, e.g. `O(users)`, `O(traffic)`, `O(data)`.

* Can you detect, flatten, or autoscale spikes?

* What are the single points of failure with respect to a single customer?

* What is the blast radius affecting all customers?

## Culture

* Do you do self-directed hackathons or other things to allow people (not just engineers) to explore and showcase their ideas?

* How do different teams express their support and respect for each other?

* Do people know and live the company values?

* Are there regular team demos, show-casing recent work?

* Are there "book clubs", "brown bag lunches", or other group activities for learning?

* How do people mentor each teach each other?

* Do performance reviews help or hurt? Who gets value from them?

* In meetings, who does the talking?

* Is leadership and decisions command and control, consensus, partnership, or empowerment based?

* Who would describe the team as "agile"?

## Deadlines

* How are deliverables committed?

* How are risks raised and mitigated?

* How are cross-team dependencies tracked and managed? Are there in person forums with all stakeholders? How are decisions that affect multiple teams made?

* Is status tracked regularly and is there a dashboard of with deliverable dates coded red, yellow, green?

* Are deliverables tracked at the epic-level in customer centric language?

## Releases

* Is there a release train and how often does it leave?

* Are builds blue-green?

* Can features go in dark?

* Can users opt in and out of major changes?

* Can product managers flip feature flags? Is there a system for the lifecycle of feature flags?

* Are releases rolled out incrementally to reduce risk?

## References

[Measure What Matters](https://www.whatmatters.com/)

[The First 90 Days](https://www.amazon.com/First-90-Days-Strategies-Expanded/dp/1422188612)

[Principles of Product Development](https://www.amazon.com/Principles-Product-Development-Flow-Generation/dp/1935401009)

[The Pragmatic Programmer](https://www.amazon.com/Pragmatic-Programmer-journey-mastery-Anniversary-ebook/dp/B07VRS84D1/)

[Agile Estimation and Planning](https://www.amazon.com/Agile-Estimating-Planning-Robert-Martin-ebook/dp/B004X1D3TC)