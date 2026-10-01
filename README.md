Project Title: Auto Ticket Classification System

Purpose:
The system automatically analyzes an incoming IT support ticket and classifies it into the appropriate category, subcategory, priority, or assignment group. This reduces manual work and helps tickets reach the correct support team faster.

1. Problem Statement

Normally, when a user creates an IT ticket, a support agent has to read the ticket and manually decide:

What type of problem is it?
Which category does it belong to?
Which team should handle it?
How urgent is it?

This can take time and may cause classification mistakes.

2. Proposed Solution

The Auto Ticket Classification system uses the information entered in the ticket, such as:

Short description
Description
Issue type
User/device information
Previous ticket patterns or classification rules

The system then automatically determines the appropriate classification.

3. Example

Suppose a user creates:

Short Description: “My laptop cannot connect to Wi-Fi.”

The system can classify it as:

Field	Example
Category	Network
Subcategory	Wi-Fi
Priority	Medium
Assignment Group	Network Support

Another ticket:

Short Description: “Outlook is not opening.”

Could become:

Field	Example
Category	Software
Subcategory	Email/Outlook
Priority	Medium
Assignment Group	Software Support
4. How the Project Works

User creates ticket → Ticket information is captured → Classification logic/AI analyzes ticket → Category is identified → Assignment group is selected → Ticket is routed → Support team resolves ticket

5. Main Components

Incident/Ticket:
Stores the user's IT problem.

Classification Logic:
Determines the appropriate category and other fields.

Assignment Group:
Routes the ticket to the responsible team.

Automation:
Runs the classification automatically when a ticket is created or updated.

Testing:
Different sample tickets are entered to verify that the system produces the expected classification.

6. Benefits
Reduces manual classification
Saves support-agent time
Sends tickets to the appropriate team
Provides consistent classification
Helps reduce routing errors
Improves IT support workflow
Can handle a large number of tickets
7. Simple Project Flow
User
  ↓
Creates IT Ticket
  ↓
Short Description + Description
  ↓
Auto Classification
  ↓
Category / Subcategory
  ↓
Priority / Assignment Group
  ↓
Correct Support Team
  ↓
Ticket Resolution
8. Example for Your Project

You can explain your project like this during a presentation:

“My project is an Auto Ticket Classification System developed in ServiceNow. The main purpose of this project is to automatically classify IT support tickets based on the information provided by the user. Instead of manually checking every ticket, the system uses classification logic to identify the appropriate category and route the ticket to the relevant support team. This helps reduce manual effort, improve ticket routing, and make the IT support process faster and more efficient.”# Auto-ticket-collection-AMAN-
Auto ticket collection system that automatically classifies
