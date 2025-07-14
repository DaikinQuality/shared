# FRACAS Guide

This guide provides instructions for accessing and using the FRACAS system to document and manage your projects effectively.

## Table of Contents
- [Accessing FRACAS](#accessing-fracas)
- [Navigating to the PDCA Template](#navigating-to-the-pdca-template)
- [Creating a New PDCA](#creating-a-new-pdca)
- [Filling Out the PDCA Tabs](#filling-out-the-pdca-tabs)
  - [Problem Statement](#1-problem-statement-detailed-instructions)
  - [Pictures](#2-pictures)
  - [Containment](#3-containment-detailed-instructions)
  - [Root Cause Analysis](#4-root-cause-analysis-detailed-instructions)
  - [Corrective Action](#5-corrective-action-detailed-instructions)
  - [Monitor Verification](#6-monitor-verification-detailed-instructions)
- [PowerPoint Reporting Guide for PDCA](#powerpoint-reporting-guide-for-pdca)

---

## Accessing FRACAS

1. **Login with SSO**:
   - Navigate to the FRACAS login page.
   - Use Single Sign-On (SSO) the network set as **DaikinApplied**
   ![fracas login](../images/FRACAS_login.PNG)

2. **Network Access**:
   - Ensure you are connected to the **DaikinApplied** network to access FRACAS.

---

## Navigating to the PDCA Template

1. **Locate the PDCA Template**:
   - On the left side of the screen, find the navigation tree.
   - Go to **Quality -> Quality_DaikinPDCA**.
   ![Quality_DaikinPDCA](../images/QUALITY_DaikinPDCA.PNG)

2. **Access the PDCA Table**:
   - Clicking on **Quality_DaikinPDCA** will open a table view of all PDCA's.

---

## Creating a New PDCA

1. **Insert a New PDCA**:
   - At the top of the table, click the **Insert** button to create a new PDCA entry.
   ![Insert new PDCA](../images/insert_pdca.PNG)

2. **Open the New PDCA Entry**:
   - Double-click the newly created entry to start entering data.

---

## Filling Out the PDCA Tabs

After opening the new PDCA entry, you will see a series of tabs. These tabs should be completed in order. Ensure most fields are filled out, unless they are not applicable.

### 1. Problem Statement (Detailed Instructions)

The **Problem Statement** tab is the first step in documenting a PDCA entry. The purpose of this section is to provide a clear and concise description of the issue and relevant details. Below are step-by-step instructions for completing the fields as shown in the image:

- **Headline / Title**:
   - **Description**: This field should contain a short, descriptive headline summarizing the problem.
   - **Example**: "DPSA pressure switch escapes."
   - **Purpose**: This allows anyone viewing the PDCA to quickly understand the general issue.

- **Responsibility**:
   - **Description**: Enter the name(s) of the individual(s) responsible for addressing the issue.
   - **Example**: "Robert Haas"
   - **Purpose**: This assigns clear ownership of the problem for tracking purposes.

- **Impact in the Field**:
   - **Description**: Briefly describe the impact that the problem has in real-world applications.
   - **Example**: "Troubleshooting is required, and replacement switches are required if the transducer is wired incorrectly."
   - **Purpose**: This explains how the problem affects operations, customers, or other field conditions.

- **Source**:
   - **Description**: Indicate the origin of the problem or the source of the issue.
   - **Example**: "Escapes."
   - **Purpose**: This helps in categorizing the problem, often indicating whether it stems from a specific incident, manufacturing process, or customer feedback.

- **Team Assignment**:
   - **Description**: List the individuals or teams assigned to the PDCA entry, specifying their roles.
   - **Example**: "Robert Haas (Test Engineer), Riley Hullett (Test Stand Operator)."
   - **Purpose**: This identifies the team responsible for investigating and resolving the issue.

- **Workflow**:
   - **Description**: Select the appropriate workflow for the PDCA entry. This should align with your organizational structure.
   - **Example**: "DaikinPDCA."
   - **Purpose**: Assigning the correct workflow ensures that the PDCA follows the proper review and approval process.

- **Problem Statement**:
    - **Description**: Provide a detailed explanation of the problem. This is the core of the PDCA entry and should be specific and thorough.
    - **Example**: "Multiple escapes have occurred with refrigerant pressure switches inoperable or wired incorrectly."
    - **Purpose**: This field should provide a comprehensive overview of the issue, ensuring that anyone reading it can understand the exact nature of the problem.

- **Sites Affected**:
    - **Description**: List the site(s) or location(s) affected by the problem.
    - **Example**: "FBN."
    - **Purpose**: This helps in identifying where the problem occurred and if it has a widespread impact.

- **Safety Related**:
    - **Description**: Specify if the problem relates to safety issues. Choose "Yes" or "No" based on the nature of the problem.
    - **Example**: "Yes."
    - **Purpose**: Highlighting safety-related problems ensures they are addressed with the appropriate urgency and care.

- **Linked Incidents**:
    - **Description**: Provide any incident numbers or references to other issues related to this problem.
    - **Example**: "01914679, 01901871, 01857918"
    - **Purpose**: Helps in cross-referencing other documented problems or incidents.

- **Related Incident**:
    - **Description**: Enter the related incident numbers, if applicable.
    - **Example**: "01914679, 01901871, 01857918."
    - **Purpose**: Provides references to other documented incidents that may be connected to this problem.

- **Document Attachment**:
    - **Description**: Attach any relevant documents or files that provide additional information about the problem.
    - **Example**: Attach images, reports, or other documentation that might be necessary to understand or resolve the issue.
    - **Purpose**: This allows users to attach supporting materials that further explain or illustrate the problem.

---

### 2. Pictures
   - Upload any relevant images that help illustrate the problem or current situation.

---

### 3. Containment (Detailed Instructions)

The **Containment** section documents the immediate actions taken to address the problem across all relevant locations (e.g., factory, field, other facilities). The actions should be swift and address the problem at all identified locations. Below are step-by-step instructions for completing the fields as shown in the image:

- **Containment Date**:
   - **Description**: Set the date when the containment actions are planned or were completed.
   - **Example**: "5/31/2024."
   - **Purpose**: This establishes the timeline for implementing containment actions, ensuring the issue is addressed promptly.

- **Containment**:
   - **Description**: Describe the containment actions taken to prevent the issue from affecting additional units, whether in the factory, in transit, or in the field.
   - **Example**: "Instruct and train test stand operators to test 100% of the switches by simulating the switch being activated and verify the MCB reads the values expected."
   - **Purpose**: This outlines immediate steps taken to isolate or minimize the impact of the issue until a more permanent solution can be implemented. Actions should be targeted at all relevant locations to ensure full containment.

- **Containment Reporting**:
   - This is automatically populated based on the "Containment" section.

---

### 4. Root Cause Analysis (Detailed Instructions)

The **Root Cause Analysis** section is critical to identifying the underlying cause(s) of the problem. In most cases, the best practice is to use a **fishbone analysis** (also known as an Ishikawa diagram) followed by a **5 Why analysis**. Both tools should be used with a group of people from different departments (e.g., TRC, Production, Quality, etc.) to identify all potential root causes.

- **Problem Solving Methodology**:
   - **Description**: Select the methodology used to identify the root causes. Typically, this will be the **Fishbone** and **5 Why** method or other problem-solving tools.
   - **Example**: "Fishbone and 5 Why."
   - **Purpose**: This field records the specific problem-solving method employed during the root cause analysis.

- **Problem Solving Tool**:
   - **Description**: If applicable, attach any supporting documentation, such as analysis tools or reports.
   - **Example**: "RCCA_pressure_switch.xlsx" (1 Attachment)." 
   - **Purpose**: This allows users to attach relevant documents used in the analysis. It is recommended to attach the results of the fishbone analysis and 5 Why in this section. 
   - **Note**: Use the RCCA_template.xlsx document to start.

- **Preliminary Confirmed Root Cause**:
   - **Description**: Enter the preliminary confirmed root cause(s) identified through the analysis.
   - **Example**: "The PFMEA process is not well known or used after NPI. The location of PFMEA's are not known. If the PFMEA process was well known, we could flow from NPI to sustaining, manufacturing, and production teams."
   - **Purpose**: This field allows for documentation of the initial findings from the fishbone and 5 Why analyses. Ensure that all significant potential root causes are recorded.

- **Preliminary Confirmed Root Cause Reporting**:
   - This field is automatically populated by the previous table.


### Best Practices for Root Cause Analysis:

- **Fishbone Analysis**: 
   - A fishbone diagram should be used to brainstorm all possible root causes. This should be done collaboratively with team members from multiple departments such as TRC, Production, and Quality.
   - Ensure to categorize the causes (e.g., Man, Machine, Materials, Methods, etc.) to fully explore all potential contributors to the problem.
   - Use the [RCCA_template.xlsx](../templates/RCCA_template.xlsx) to create and document the fishbone diagram. Attach this document under **Problem Solving Tool**.

- **5 Why Analysis**: 
   - After completing the fishbone analysis, use the 5 Why technique to drill down further and identify the root causes.
   - The 5 Why should be **3-legged**—this means identifying at least three different branches (areas) where the root cause analysis can explore further.
   - Each branch may reveal multiple root causes that require attention.
   
- **RCCA Template**:
   - Use the RCCA_template.xlsx located in the **templates folder**. This template provides a consistent format for conducting fishbone and 5 Why analyses.
   - Attach the filled RCCA template to this section after completing the analysis.

---

### 5. Corrective Action (Detailed Instructions)

The **Corrective Action** section outlines the steps to address the identified root causes and failure modes. The process should follow a structured workflow to ensure that actions are implemented, monitored, and documented effectively. Below are step-by-step instructions for completing the fields as shown in the image.

- **Action**:
   - **Description**: Document each corrective or containment action taken to address the issue. This can include immediate containment steps, identifying root causes, and implementing solutions.
   - **Example**:
     - "Identify root cause of escapes."
     - "Put containment in place to test all switches by simulating a switch activated."
   - **Purpose**: This field outlines the specific steps being taken to correct the problem and ensure it doesn’t recur.

- **Owner**:
   - **Description**: Assign the individual responsible for completing the corrective action.
   - **Example**: "Robert Haas."
   - **Purpose**: This assigns accountability for each step in the corrective action process.

- **Due Date**:
   - **Description**: Set a deadline for completing each action. This ensures that actions are completed in a timely manner.
   - **Example**: "6/28/2024."
   - **Purpose**: This field provides a clear timeline for when corrective actions must be implemented.

- **Complete**:
   - **Description**: Mark whether the action has been completed. This is a simple "Yes" or "No" field to track the status of each task.
   - **Example**: "Yes."
   - **Purpose**: This allows the team to easily see which actions are still pending and which have been completed.

- **Action Type**:
   - **Description**: Specify the type of action being taken (e.g., Corrective Action, Containment).
   - **Example**: "Corrective Action," "Containment."
   - **Purpose**: This categorizes the type of action being taken to address the issue, allowing for better tracking of different stages in the process.

- **Report Out**:
   - **Description**: Use this checkbox to indicate if the action needs to be reported out to other team members or stakeholders.
   - **Purpose**: This ensures that important corrective actions are communicated to relevant parties.

The steps below outline the typical actions that should be documented in the "Corrective/Countermeasure Actions":

  - **Containment**: Implement immediate actions to contain the issue.
  
  - **Root Cause**: Conduct a thorough analysis to determine the root cause of the problem.
  
  - **Identify All Failure Modes**: Examine and document all potential failure modes related to the issue.
  
  - **Work with Team to Identify Possible Solutions**: Collaborate with team members to brainstorm and evaluate potential solutions.
  
  - **Make Changes**: Implement the chosen solution(s) to address the root cause and failure modes.
  
  - **Deploy and Training**: Deploy the corrective action and provide necessary training to all relevant personnel.
  
  - **Update Repositories**: Update all relevant documentation and repositories to reflect the changes made.


### Current Poke-Yoke Level (5 Ranks)
- Poka-Yoke levels are described in detail in the "RCCA_template.xlsx" document.

- **Description**: Select the current level of mistake-proofing (Poka-Yoke) for the process. The ranking ranges from manual detection to full automation.
- **Example**: "Level 2 - Detectable by human judgment (Think & judge by human)."
- **Purpose**: This helps in understanding how robust the previous system was in preventing errors.

### Completed Poke-Yoke Level

- **Description**: Select the improved Poka-Yoke level after the corrective actions have been implemented.
- **Example**: "Level 3 - Poka-Yoke by attention control (Able to judge easily at a glance)."
- **Purpose**: This field indicates the improvement in mistake-proofing due to the corrective actions.


### Estimated Implementation Date

- **Description**: Set the estimated date for completing all corrective actions.
- **Example**: "7/23/2024."
- **Purpose**: This establishes a final deadline for completing the corrective action phase.


### Is this problem likely to occur at other facilities?

- **Description**: Indicate if the issue is likely to be encountered at other facilities.
- **Example**: "Yes."
- **Purpose**: This helps in understanding the scope of the problem and whether actions need to be extended beyond the current facility.


### Who needs to be notified at other facilities?

- **Description**: List the individuals or teams that need to be notified if the problem is likely to occur at other locations.
- **Example**: "Kory Mensing."
- **Purpose**: Ensures that key stakeholders at other locations are made aware of the issue and can take preventive measures.

### Lessons Learned

- **Description**: Summarize any lessons learned from the corrective action process. This can include insights into the root cause, containment measures, and the effectiveness of the corrective actions.
- **Purpose**: Captures valuable information that can be applied to future problems, preventing recurrence and improving overall processes.


---

### 6. Monitor Verification (Detailed Instructions)

The **Monitor Verification** section is crucial for tracking the effectiveness of the implemented corrective actions. This section helps ensure that the corrective actions solve the issue long-term and identifies if any related events occur after the completion. Below are step-by-step instructions for completing the fields as shown in the image.

- **Actual Implementation Date**:
   - **Description**: This is the date when the PDCA implementation was completed. The corrective actions should be fully implemented by this date.
   - **Example**: "7/23/2024."
   - **Purpose**: Establishes the final completion date of the PDCA, signaling when corrective actions were put in place and monitoring began.

- **Verification of Effectiveness Duration**:
   - **Description**: Enter the duration (in months) that the project will be monitored for effectiveness after the corrective actions are completed.
   - **Example**: "24" (months).
   - **Purpose**: This field specifies the monitoring period, ensuring that the corrective actions are tracked for long-term effectiveness.


### Event Data (Issue Found After Closed)

- **Description**: This section is used to log any events that are discovered after the PDCA is closed. Each time a related event occurs after the corrective actions are implemented, a new row should be added.
- **Fields**:
  - **Event Date**: The date when the new issue or event was discovered.
  - **Source**: The origin of the event or how the issue was identified.
  - **Comments**: Additional information or details about the event, including how it relates to the previous PDCA.
  
- **Purpose**: Logging these events helps in tracking whether similar issues are still occurring and contributes to the automatic generation of an **Elephant Chart**. The Elephant Chart is used for reporting the effectiveness of the PDCA and highlights whether the problem persists or has been eliminated.

---


### PowerPoint Reporting Guide for PDCA

Until FRACAS automates the reporting process, manually create PowerPoint reports using the **PDCA Reporting Template**. Follow these steps to fill out the slide, copying and pasting fields from the **Reporting Tab** in FRACAS:

1. **Problem Statement**: Copy this section from the **Problem Statement** in FRACAS.  
2. **Impact**: Copy this section from the **Impact** fields in FRACAS.  
3. **Field Impact**: Copy the **Related Incident Numbers** from FRACAS.  
4. **Problem Solving Methodologies**: Copy the methodology used (e.g., **5 Why**).  
5. **Preliminary or Confirmed Root Cause**: Copy this section from the **Root Cause Analysis**.  
6. **Corrective Action**: Copy the **Corrective Actions** from FRACAS.  
7. **Containment**: Copy the **Containment Actions** from FRACAS.  
8. **Countermeasures**: Copy the corrective actions from FRACAS.  
9. **RCCA Open Actions**: Copy any open actions from FRACAS.  
10. **Poke-Yoke**: Copy the **Current and New Poke-Yoke Levels** from FRACAS.

---
