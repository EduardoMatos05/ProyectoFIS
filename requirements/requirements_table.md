| Functional Requirements                     |
|--------------------------------------------|
| The system will prioritize notifications according to the keywords that the user chooses. |
| The system will be linked to the Outlook email app. |
| The user will be able to customize how they receive notifications. |
| The system will periodically ask questions to determine if the user wishes to continue filtering notifications from certain senders. |
|                                            |
| Non-Functional Requirements                 |
|--------------------------------------------|
| The system can be customized (appearance, sounds, backgrounds). |
| The user will have no limits on the number of keywords they can enter. |
|                                            |


## Specifications 

Description:

The Universidad Autónoma de Yucatán (UADY) provides valuable information to its students and staff, including details about events, seminars, interesting talks, scholarship applications, and more. This information is primarily delivered via email through the Outlook application. However, as this channel also handles various other types of emails, important information can easily get lost amidst the email clutter.

This situation can result in individuals missing out on information that could greatly benefit them. To address this issue, our product is designed to assist students and staff in efficiently organizing and filtering their emails. By linking their Outlook accounts with the software and customizing their notification preferences, they can ensure that they receive information in a way that suits their needs and priorities.

Our product aims to enhance the academic and professional development of UADY's students and staff by streamlining their email management and ensuring that they don't miss out on critical updates and opportunities.

Normal Sequence:

| Step | Action                                                                                                  |
| ---- | ------------------------------------------------------------------------------------------------------- |
| 1    | User downloads and installs the software on their device                                             |
| 2    | After launching it, a pop-up window appears to link their Outlook to the system                      |
| 3    | User sets up and customizes the appearance and background                                             |
| 4    | The user accesses the keyword management section of the software                                      |
| 5    | They enter the main keywords they want to prioritize or ignore in their notifications                |
| 6    | There is no limit to the number of keywords they can enter, so they can repeat the process            |
| 7    | The user navigates to the notification settings                                                       |
| 8    | They customize how they receive the filtered notifications                                            |
| 9    | The software periodically prompts the user with questions to determine if they wish to continue filtering notifications from specific senders |
| 10   | Based on the user's response, the system will change its filtering criteria                           |
| 11   | As new emails are sent to the user, the system monitors for the keywords                              |
| 12   | The system ensures that the user is notified immediately based on their chosen notification preferences if the filtering criteria is met |
| 13   | The user can access the settings to modify their preferences and customization                         |

Exceptions:

| Step | Action                                                                                         |
| ---- | ---------------------------------------------------------------------------------------------- |
| 3    | User sets up and customizes the appearance and background.                                      |
| E.1  | The user can only customize the color of the details of the software.                            |
| E.2  | The colors that the user can use to customize are limited to some.                                 |
| 7    | The user navigates to the notification settings                                                |
| E.1  | The user can customize the notification sounds based on the ones that the device includes.        |
| 8    | They customize how they receive the filtered notifications                                     |
| E.1  | The user can only choose how they will receive their notifications based on the options that the software gives. |
| E.2  | The user can choose from one of the different styles of notification.                              |
| E.3  | The user can adjust the letter font and choose whether to have a summary shown in the notification.   |

