| Functional Requirements                     |
|--------------------------------------------|
| The system will prioritize notifications according to the keywords that the user chooses. |
| The system will be linked to the Outlook email app. |
| The user will be able to customize how they receive notifications. |
| The system will periodically ask questions to determine if the user wishes to continue filtering notifications from certain senders. |
| The system can be customized (appearance, sounds, backgrounds). |
| Non-Functional Requirements                 |
|--------------------------------------------|
| The user will have no limits on the number of keywords they can enter. |
|                                            |


## Specifications 

Description:

The Universidad Autónoma de Yucatán (UADY) provides valuable information to its students and staff, including details about events, seminars, interesting talks, scholarship applications, and more. This information is primarily delivered via email through the Outlook application. However, as this channel also handles various other types of emails, important information can easily get lost amidst the email clutter.

This situation can result in individuals missing out on information that could greatly benefit them. To address this issue, our product is designed to assist students and staff in efficiently organizing and filtering their emails. By linking their Outlook accounts with the software and customizing their notification preferences, they can ensure that they receive information in a way that suits their needs and priorities.

Our product aims to enhance the academic and professional development of UADY's students and staff by streamlining their email management and ensuring that they don't miss out on critical updates and opportunities.

#### 1. Prioritize Notifications Based on User-Defined Keywords

| Step | Description | Exception |
|------|-------------|--------------------|
| 1    | User accesses the system settings. | - |
| 2    | In the notification preferences section, user defines keywords | - |
| 3    | System monitors incoming notifications. | - |
| 4    | When a notification matches a user-defined keyword, it is prioritized accordingly | If there's an issue with keyword recognition, default prioritization is applied. |

#### 2. Integration with Outlook Email App

| Step | Description | Exception |
|------|-------------|--------------------|
| 1    | User accesses the system settings. | - |
| 2    | In the email integration section, user links the system to their Outlook email app. | If the connection fails, provide clear error messages and instructions for troubleshooting. |
| 3    | System establishes a secure connection with the Outlook email app. | - |
| 4    | Incoming emails trigger the notification system for prioritization. | Handle errors gracefully, ensuring notifications are not lost in case of synchronization issues. |

#### 3. Customize Notification Preferences

| Step | Description | Exception |
|------|-------------|--------------------|
| 1    | User accesses the system settings. | - |
| 2    | In the notification preferences section, user selects customization options. | If customization fails, revert to default settings and notify the user. |
| 3    | Options may include choosing notification sounds, appearance, and backgrounds. | Ensure fallback options are available if selected sounds or backgrounds are not supported. |
| 4    | Changes are applied, and the user receives notifications as per their preferences. | Notify the user if changes cannot be applied immediately. |

#### 4. Periodic User Confirmation for Sender Filtering

| Step | Description | Exception |
|------|-------------|--------------------|
| 1    | System periodically prompts the user with questions about specific senders. | Ensure the prompt is non-intrusive, and if not answered, use default settings or assume no change. |
| 2    | User receives a notification asking if they want to continue filtering messages from certain senders. | Provide an option to skip or delay the confirmation if the user is busy. |
| 3    | User provides input (Yes/No) or adjusts filtering settings accordingly. | If input is unclear or ambiguous, prompt for clarification. |
| 4    | System updates sender filtering based on user responses. | If there's an issue with the update, provide feedback and retry mechanisms. |



#### 5. Customization of System (Appearance, Sounds, Backgrounds)

| Step | Description | Exception |
|------|-------------|--------------------|
| 1    | User accesses the customization menu in system settings. | - |
| 2    | User selects options for changing appearance, sounds, and backgrounds. | Gracefully handle cases where selected customization is not supported. |
| 3    | Changes are applied to the system interface. | If changes cannot be applied instantly, provide feedback to the user. |
| 4    | User experiences a personalized system environment. | Provide default settings in case of customization failure. |
