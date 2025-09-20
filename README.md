# Energy Efficiency Retrofit Services

Smart contract system that enables comprehensive building improvement through energy audits, contractor matching, and verified savings tracking.

This project implements a complete workflow from initial energy assessment to project completion and performance verification. Property owners can request audits, certified contractors submit competitive bids, and the system tracks actual energy savings against projections.

## What This Does

- Energy audit request and completion tracking
- Contractor certification and verification system  
- Competitive bidding platform for retrofit projects
- Project management from start to finish
- Post-completion savings verification and reporting

## Implementation Details

Built with scalability in mind using separate Clarity maps for audits, contractors, projects, bids, and verification records. The contract maintains strict authorization controls ensuring only property owners can accept bids and only verified contractors can submit proposals.

Using principal validation throughout to ensure data integrity and prevent unauthorized modifications. The savings calculation automatically computes the difference between pre and post-retrofit usage for accurate reporting.
