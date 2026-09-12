# 🚀 Automated Network Request Management in ServiceNow

## 📌 Project Overview

**Automated Network Request Management in ServiceNow** is a ServiceNow-based application that automates the complete process of network access requests. Instead of handling network requests manually through emails or phone calls, users can submit requests through the Service Catalog, and the system automatically sends them for approval, creates fulfillment tasks, updates request status, and notifies users throughout the process.

This project improves efficiency, reduces manual work, and provides complete tracking of every network request.

---

## 🎯 Project Objective

The main objective of this project is to automate the network request process using ServiceNow workflows and approval mechanisms.

The system helps organizations to:

* Submit network requests through a catalog item.
* Route requests to the correct approver automatically.
* Generate network fulfillment tasks after approval.
* Notify users during every stage of the request.
* Track requests using reports and dashboards.

---

## ✨ Features

* Service Catalog item for Network Requests.
* Dynamic form fields using Client Scripts.
* Auto-populated user information.
* Approval workflow based on request type and priority.
* Automatic task creation for the Network Team.
* Email notifications for requester and approver.
* Status tracking from New to Completed.
* Reports and Dashboards for monitoring requests.
* Role-based access control for users, approvers, and network engineers.

---

## 🛠️ Technologies Used

| Technology                 | Purpose                 |
| -------------------------- | ----------------------- |
| ServiceNow Platform        | Application Development |
| Service Catalog            | Request Submission      |
| Flow Designer / Workflow   | Approval Automation     |
| Client Scripts             | Dynamic Form Behavior   |
| UI Policies                | Field Validation        |
| Notifications              | Email Alerts            |
| Reports & Dashboards       | Request Monitoring      |
| ACL (Access Control Lists) | Role-Based Security     |

---

## 👥 User Roles

### Requester

* Creates a network request.
* Provides business justification.
* Tracks request status.

### Approver

* Reviews submitted requests.
* Approves or rejects requests.
* Adds approval comments.

### Network Engineer

* Receives fulfillment task after approval.
* Performs network configuration.
* Updates work notes and closes the task.

### Administrator

* Manages catalog items.
* Configures workflows, notifications, and user roles.
* Monitors dashboards and reports.

---

## ⚙️ Workflow

1. User submits a Network Request from the Service Catalog.
2. Form validates required information.
3. Request is sent to the appropriate approver.
4. Approver approves or rejects the request.
5. If approved, a fulfillment task is automatically created.
6. Network Team completes the requested network activity.
7. Request status is updated to **Completed**.
8. Notifications are sent during important stages.

---

## 📋 Catalog Item Variables

The Network Request catalog item includes variables such as:

* Request Type
* Access Level
* Device Name
* Device IP Address
* Department
* Requested For
* Business Justification
* Priority

Some variables are auto-populated using ServiceNow reference fields and Client Scripts.

---

## 🔐 Security Features

* Role-based access using ACL.
* Mandatory field validation.
* Approval before network changes.
* Authorized access for Network Team only.
* Request history and audit tracking.

---

## 📧 Notifications

The system sends automatic email notifications for:

* Request Submission
* Approval Pending
* Request Approved
* Request Rejected
* Task Assigned to Network Team
* Request Completed

---

## 📊 Reports and Dashboards

The dashboard provides:

* Total Network Requests.
* Pending Approvals.
* Approved Requests.
* Rejected Requests.
* Completed Requests.
* Request Status by Priority.
* SLA and Task Performance.

---

## 📁 Project Structure

```text
Automated-Network-Request-Management-in-ServiceNow/
│
├── README.md
├── docs/
│   ├── Introduction.md
│   ├── Project_Overview.md
│   ├── Workflow.md
│   ├── Architecture.md
│   ├── Roles_and_Responsibilities.md
│   └── Reports_and_Dashboard.md
│
├── catalog-item/
│   ├── Variables.md
│   ├── Client_Scripts.md
│   ├── UI_Policies.md
│   └── Catalog_Item_Setup.md
│
├── workflow/
│   ├── Approval_Flow.md
│   ├── Flow_Designer.md
│   └── Notifications.md
│
└── images/
    ├── architecture.png
    ├── workflow.png
    └── dashboard.png
```

---

## 📸 Project Screenshots

Add screenshots inside the `images` folder, including:

* Service Catalog Form
* Approval Screen
* Flow Designer
* Network Fulfillment Task
* Reports Dashboard

---

## 🚀 How to Run the Project

1. Open your ServiceNow instance.
2. Import or create the Network Request Catalog Item.
3. Configure variables and Client Scripts.
4. Create the approval workflow using Flow Designer.
5. Configure notifications.
6. Create reports and dashboards.
7. Test the request submission and approval process.

---

## ✅ Expected Output

* Users can submit network requests easily.
* Approvals happen automatically.
* Network Team receives tasks instantly.
* Users receive email updates.
* Administrators can monitor all requests from dashboards.

---

## 📚 Learning Outcomes

This project demonstrates practical implementation of:

* Service Catalog Development
* Client Scripts
* UI Policies
* Flow Designer
* Approval Workflow
* Notifications
* Access Control Lists (ACL)
* Reports and Dashboards

---

## 📌 Future Enhancements

* AI-based request priority prediction.
* SLA breach prediction.
* Teams or Slack notification integration.
* Network asset availability check.
* Mobile approval support.
