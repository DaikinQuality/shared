# FRACAS Guide

This guide provides instructions for accessing and using the FRACAS system to document and manage projects effectively. The intent of this document is not only to explain how to complete the PDCA, but also to establish best practices for conducting strong quality investigations and sustainable corrective actions.

## Table of Contents
- Accessing FRACAS
- Navigating to the PDCA Template
- Creating a New PDCA
- Filling Out the PDCA Tabs
  - Problem Statement
  - Pictures
  - Containment
  - Root Cause Analysis
  - Corrective Action
  - Monitor Verification
- PowerPoint Reporting Guide for PDCA

---

# Accessing FRACAS

1. Login using SSO on the DaikinApplied network.
2. Navigate to:
   - Quality -> Quality_DaikinPDCA

---

# Creating a New PDCA

1. Click the Insert button.
2. Open the newly created entry.
3. Complete tabs in order.

---

# 1. Problem Statement (Detailed Instructions)

The Problem Statement is the most important section of the PDCA. A strong problem statement clearly defines the issue, quantifies the impact, and explains why the problem matters.

A weak problem statement leads to weak root cause analysis and ineffective corrective actions.

The problem statement should:
- Clearly describe the failure mode
- Quantify the issue
- Identify production and customer impact
- Identify affected facilities
- Avoid assumptions or proposed solutions

## Problem Statement Best Practice

A strong problem statement should include:
- Number of TRC cases
- Warranty quantity
- Warranty dollar amount
- Turnback quantity
- Downtime or labor impact
- Customer impact
- Date range
- Models or serial ranges affected

### Good Example

"12 TRC cases and 4 warranty claims were identified on DPSA units with intermittent pressure switch failures between January and March 2024. Warranty exposure is currently estimated at $18,500. Production experienced 37 turnbacks resulting in approximately 22 labor hours lost. Failures were identified at FBN with similar product configurations also produced at SLP and FBS. Field failures resulted in troubleshooting visits and component replacement."

---

## Headline / Title

Provide a short description of the issue.

### Example
"DPSA pressure switch escapes"

---

## Responsibility

Assign ownership for the PDCA.

### Example
"Robert Haas"

---

## Impact in the Field

Describe the customer or field impact.

### Example
"Field troubleshooting and component replacement required due to intermittent switch failures."

---

## Source

Identify where the issue originated.

### Example
"Escapes"

---

## Team Assignment

List cross-functional team members participating in the investigation.

### Example
"Robert Haas (Test Engineer), Riley Hullett (Operator), Production Supervisor, Quality Engineer"

---

## Workflow

Select the appropriate workflow.

### Example
"DaikinPDCA"

---

## Problem Statement

Provide a detailed description of the issue and impact.

The problem statement should:
- Describe the failure mode
- Describe the escape point
- Quantify the impact
- Explain customer impact
- Explain operational impact

---

## Sites Affected

List all facilities potentially affected by the issue, not just the site where the issue was discovered.

### Example
"FBN, SLP, FBS"

### Purpose
Ensures containment and corrective actions are deployed across all affected facilities.

---

## Safety Related

Indicate if the issue impacts safety.

### Example
"Yes"

---

## Linked Incidents

List related incident numbers.

### Example
"01914679, 01901871, 01857918"

---

## Document Attachment

Attach:
- Pictures
- Test reports
- RCCA documents
- Supporting evidence
- Customer information

---

# 2. Pictures

Upload clear pictures showing:
- Failure mode
- Incorrect condition
- Correct condition
- Serial labels
- Tooling
- Test setups
- Damage

Pictures should help explain the issue without requiring verbal explanation.

---

# 3. Containment (Detailed Instructions)

Containment actions are immediate actions taken to prevent additional escapes while root cause analysis and corrective actions are being completed.

Containment should address:
- Work in process
- Finished goods
- Field exposure
- Units in transit
- Customer impact

Containment actions should clearly identify:
- Who implemented the containment
- How containment effectiveness is verified
- Whether field escapes are expected
- Identification method for affected units

---

## Containment Best Practice

Containment should include:
- Expected quantity of field escapes
- Serial number ranges
- Inspection method
- Verification method
- Communication plan

### Good Example

"Implemented 100% functional verification of pressure switch operation at all final test stations. Operators are required to simulate switch activation and verify expected MCB response. Approximately 42 units produced between serial ranges XXXX–XXXX may contain the issue and are being reviewed. No additional field escapes are currently expected after containment implementation."

---

## Containment Date

Record the implementation date for containment.

---

## Containment Reporting

This section is auto-populated.

---

# 4. Root Cause Analysis (Detailed Instructions)

The purpose of root cause analysis is to identify the true systemic causes that allowed the issue to occur and escape detection.

Best practice is to use:
- Fishbone analysis
- 5 Why analysis

These should be completed collaboratively with:
- Production
- Quality
- Manufacturing Engineering
- TRC
- Design Engineering

Root causes should focus on:
- Process weaknesses
- Detection weaknesses
- Tooling gaps
- Documentation gaps
- Training gaps
- System failures

Avoid simply identifying "operator error" without identifying the system weakness that allowed the issue to occur.

---

## Problem Solving Methodology

### Example
"Fishbone and 5 Why"

---

## Problem Solving Tool

Attach:
- Fishbone diagrams
- RCCA spreadsheets
- 5 Why documentation
- Supporting analysis

Use the RCCA_template.xlsx document.

---

## Preliminary Confirmed Root Cause

Good root causes are:
- Specific
- Actionable
- Measurable
- System-focused

### Good Examples

- "Assembly was completed using the incorrect wire stripping tool, damaging conductor strands."
- "The correct stripping tool was not available in the operator work area."
- "PFMEA did not identify the failure mode of conductor damage caused by incorrect stripping tooling because the process steps were defined at a high level."
- "Final test methodology did not consistently detect intermittent electrical contact because the wire maintained partial continuity during some test cycles."

---

## Fishbone Analysis Best Practice

Evaluate:
- Man
- Machine
- Method
- Material
- Measurement
- Environment

Fishbone analysis should be collaborative and cross-functional.

---

## 5 Why Best Practice

The 5 Why analysis should:
- Dig into systemic causes
- Include multiple branches
- Identify why the issue escaped detection

The 5 Why should not stop at operator actions.

---

# 5. Corrective Action (Detailed Instructions)

Corrective actions should eliminate the root causes and improve long-term process robustness.

Each action should include:
- Owner
- Due date
- Validation plan
- Deployment plan
- Sustainability plan

---

## Corrective Action Hierarchy

Preferred corrective action order:
1. Eliminate the failure mode
2. Add poka-yoke
3. Add automated detection
4. Improve process controls
5. Improve standard work
6. Training only (weakest)

Training alone is generally considered a weak corrective action.

---

## Corrective Action Best Practices

Corrective actions should answer:
- How was the fix validated?
- What evidence proves the fix works?
- How will sustainability be ensured?
- How will the fix be deployed to all affected sites?

---

## Typical Corrective Actions

- Implement containment
- Identify root causes
- Identify all failure modes
- Develop solutions
- Validate fixes
- Deploy changes
- Train personnel
- Update documentation
- Update PFMEA and control plans

---

## Poka-Yoke Levels

Document:
- Current poka-yoke level
- Improved poka-yoke level after corrective actions

---

## Lessons Learned

Capture:
- Process weaknesses discovered
- Improvements made
- Future prevention opportunities
- Standards needing updates

---

# 6. Monitor Verification (Detailed Instructions)

Monitor verification confirms that corrective actions remain effective over time.

Monitoring should confirm:
- Failure mode no longer occurs
- Detection systems remain effective
- Similar escapes are not continuing

---

## Recommended Monitoring Metrics

Track:
- TRCs
- Warranty claims
- Turnbacks
- Scrap
- Rework
- Downtime
- Escape rates
- Audit findings

Trend data should demonstrate sustained improvement.

---

## Event Data (Issue Found After Closed)

If related issues occur after closure:
- Add a new event entry
- Document source and findings
- Determine if RCCA updates are required

This information supports Elephant Chart reporting and long-term effectiveness tracking.

---

# PowerPoint Reporting Guide for PDCA

Until FRACAS automates reporting, manually create PowerPoint reports using the PDCA reporting template.

Copy the following sections from FRACAS:
1. Problem Statement
2. Impact
3. Field Impact
4. Problem Solving Methodology
5. Root Cause
6. Corrective Actions
7. Containment
8. Countermeasures
9. Open Actions
10. Poka-Yoke Levels
