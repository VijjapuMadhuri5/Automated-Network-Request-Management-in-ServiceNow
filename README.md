# Automated-Network-Request-Management-in-ServiceNow

📌 Project Overview

The Automated Network Request Management system is a ServiceNow application designed to simplify and automate the process of submitting, validating, approving, and tracking network access requests.

The system allows users to submit network-related requests through the Service Catalog. Based on the request details, the system validates the information, routes the request for approval, and sends automated email notifications to the appropriate approvers.

This project reduces manual work, improves request tracking, and provides a structured workflow for managing network access requests.

🎯 Objectives

- Automate the network request submission and approval process.
- Reduce manual effort in managing network access requests.
- Provide role-based access to users and administrators.
- Validate request information before processing.
- Send automated email notifications to approvers.
- Improve transparency and tracking of request status.

🛠️ Technologies Used

- Platform: ServiceNow
- Service Catalog: Request submission and management
- Service Portal: User-friendly request submission
- Flow Designer: Workflow automation and approval routing
- JavaScript: Client-side scripting and dynamic field behavior
- Business Rules: Server-side validation and automation
- Notifications: Automated email notifications
- Access Controls: Roles and permissions

👥 User Roles

1. Requester

- Submits network access requests.
- Provides the required request details.
- Tracks the status of submitted requests.

2. Approver

- Reviews submitted network requests.
- Approves or rejects requests.
- Receives automated email notifications.

3. Network Team

- Handles network-related requests.
- Reviews and processes approved requests.
- Updates request records when required.

4. Administrator

- Configures the Service Catalog and workflows.
- Manages user roles and access controls.
- Maintains the application and automation rules.

⚙️ Key Features

1. Service Catalog Item

The application provides a Network Request Service Catalog item with the following fields:

- Request Type
- Access Level
- Device
- Business Justification
- Priority

2. Dynamic Form Fields

Client-side scripting dynamically displays or hides fields based on the selected request type, making the form easier to use and ensuring relevant information is collected.

3. Request Validation

The system validates the submitted information before processing the request, helping to prevent incomplete or incorrect submissions.

4. Automated Approval Routing

Flow Designer routes requests to the appropriate approvers based on network access type and priority.

5. Email Notifications

Automated email notifications are sent to approvers when a request requires review. Additional notifications are triggered when the request is approved or rejected.

6. Request Tracking

Users and administrators can track request records and monitor their current status, including requests waiting for approval.

7. Role-Based Access Control

Access is managed through configured groups and roles, including Requesters, Approvers, and the Network Team.

🔄 Workflow

1. The requester opens the Service Catalog through the Service Portal.
2. The requester fills in the network request details.
3. The system validates the submitted information.
4. A request record is created.
5. The workflow routes the request to the appropriate approver.
6. An automated email notification is sent to the approver.
7. The approver reviews the request and selects Approve or Reject.
8. The system updates the request status and sends a notification.
9. The Network Team processes the request when applicable.

🧪 Demo Flow

1. Submit a network request through the Service Portal.
2. Verify that the request record and email notification are created.
3. Run or test the configured workflow.
4. Check that the request status changes to Waiting for Approval.
5. Open the approval request in the portal.
6. Approve or reject the request.
7. Verify that the request status and notification are updated.

📂 Project Modules

- Service Catalog Configuration
- Request Form and Field Management
- Client-Side Dynamic Field Display
- Request Validation
- Approval Workflow Automation
- Email Notifications
- User Roles and Access Controls
- Request Status Tracking

🚀 Benefits

- Faster network request processing.
- Reduced manual communication.
- Improved approval management.
- Better visibility into request status.
- Consistent and organized request handling.
- Enhanced user experience through automation.

📚 Learning Outcomes

Through this project, I gained practical experience in:

- ServiceNow Service Catalog configuration.
- Flow Designer and approval workflows.
- Client-side JavaScript scripting.
- Business Rules and server-side automation.
- Email notification configuration.
- Roles, groups, and access control.
- Service Portal request submission.
