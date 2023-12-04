# Video

[Link](https://youtu.be/SaOdiAgUM2E)



### Requirements


| **Requirement** | **Input** | **Output** | **CFP** |
|-----------------|--------------------------|------------|---------|
| 1               | - Go to system settings.<br>- Pick keywords for notifications. | - System watches for new notifications.<br>- If a notification has a keyword you picked, it gets shown first. | 4       |
| 2               | - Open system settings.<br>- Connect system to Outlook email. | - System securely links to Outlook.<br>- Emails from Outlook can trigger prioritized notifications. | 4       |
| 3               | - Open system settings.<br>- Choose how you want notifications to look and sound. | - Changes you picked are applied to notifications. | 3       |
| 4               | - System asks if you still want to filter certain senders. | - System adjusts filtering based on your answer. | 2       |
| 5               | - Go to system settings.<br>- Pick how you want the system to look and sound. | - The system looks and sounds the way you chose. | 3       |


### Effort and Cost Summary

we have a summary of the total CFP of the requirements that we worked on the second sprint, the #E means the total entries of the requirements, and the #X the number of exits,  at the end, we have the total CFP of entries and exits and the sum of the total CFP.

| Requirement                                       | #E | #X | #R | #W | Error messages | Sum (CFP) |
|---------------------------------------------------|----|----|----|----|-----------------|-----------|
| Prioritize Notifications Based on User-Defined Keywords | 2  | 2  | 0  | 0  |             | 4        |
| Integration with Outlook Email App                | 2  | 2  | 0  | 0  |               | 4        |
| Customize Notification Preferences                | 2  | 1  | 0  | 0  |               | 3        |
| Periodic User Confirmation for Sender Filtering   | 1  | 1  | 0  | 0  |             | 2       |
| Customization of System (Appearance, Sounds, Backgrounds) | 2  | 1  | 0  | 0  |      | 3     |
| **Total**                                         | 9  | 7  | 0  | 0  |             | 16         |


The fifth column "error messages" adds an Exit for error/confirmation messages.

**Effort:** 7 PM (7 persons dedicated 1 month to the sprint) 

Regarding salaries, we have a Scrum Master, a QA/Tester, and 5 developers, all with low experience levels. Our salary reference is: [Indeed Salaries](https://mx.indeed.com/career/salaries) 
**Total Monthly Cost:** $105,393
Assuming a productivity of 5 function points per month and the cost of having the team for one month is $105,393, the cost per function point would be $21,078.6. Multiplying this cost by the total function points (16), the project cost would be $337,257.6.

Additionally, assuming a productivity of 5 function points per month and a total of 16 function points, the time to complete the project would be 3.2 months.

The effort involves 7 PM (Person Months), with 7 individuals dedicating 1 month to the sprint.


Assuming a productivity of 5 function points per month and a total of 16 PF, the project completion time would be 3.2 months.

### Work Breakdown Structure (WBS)


| ID  | Activity                                      | Responsible          | Time  | Cost |
|-----|-----------------------------------------------|-----------------------|-------|------|
| 1   | Design Draft.                                 | Eduardo Matos         | 1 week |      |
| 2   | User links their Outlook (interface).         | Eduardo Matos         | 1 week |      |
| 2.1 | Allows you to enable and authenticate the user´s email. | Eduardo Matos         | 4 days |      |
| 2.2 | Correct integration of the software with Outlook. | Pablo Canto           | 3 days |      |
| 3   | Select keywords to filter.                   | Eduardo Del Río        | 1 week |      |
| 3.1 | Interface where the user can enter keywords. | Rodrigo Alonzo         | 5 days |      |
| 3.2 | The interface is tested and functional.      | Braulio Cuevas, Eduardo Del Rio | 2 days |      |
| 4   | Customize the appearance and notifications.  | Mauricio Villanueva    | 1 week |      |
| 4.1 | Design the customization interface.          | Mauricio Villanueva    | 3 days |      |
| 4.2 | Visualization of interface functionalities such as color and theme. | Lexus Parra           | 4 days |      |

### Gantt Chart

The Gantt chart represents the project timeline with three stages: analysis, interface design, and user testing (UX).


The Gantt chart for the UAY! The project is based on all the activities carried out...
imagen del gantt


### Software Quality Models - McCall and Boehm

#### McCall Model Characteristics

- Correctness
- Reliability
- Efficiency
- Integrity
- Usability
- Ease of Maintenance
- Ease of Evaluation
- Flexibility
- Portability
- Reuse
- Interoperability

#### Boehm Model Characteristics

- Portability
- Reliability
- Efficiency
- Ergonomics
- Ease of Evaluation
- Understandability
- Ease of Modification

In the project, Boehm model is preferred due to its adaptability to changing requirements.

### Software Configuration Management Audit


#### Configuration of Project Interfaces
For the project interfaces, we began with configuration based on the requirements to ensure consistency and integrity within the project. As the design process unfolded, versioning of the interfaces was carried out with the approval of the entire team. Upon completion, the finalized version was uploaded to the repository."

- Have all configuration items in the project been clearly identified and labeled? yes
- Is there an efficient control in place to ensure that only authorized changes are made to the configuration items?
- Is there an established process for managing versions and facilitating the retrieval of previous versions of the design if needed?
- Is there a formal process for proposing, reviewing, approving, and implementing changes to the interfaces?
- Are the reasons and impact of changes adequately documented?
- Are branches used to develop new features or fixes without affecting the main version of the design?
- Does the configuration management facilitate effective collaboration among team members?
- Is the configuration of the design and associated processes adequately documented?

#### Use Case Selection and Updating
The updating and selection of each use case were crucial for describing how the system would be interacted with, ensuring coverage of various possible scenarios. There was always effective communication about significant changes and discussions regarding any potential impact on the design or development of the system.

- Is each software functionality represented as an identifiable use case?
- Have the limits and scopes of each use case been clearly defined and documented?
- Have the relevant configuration elements been assigned to each use case?
- Is there an established process for managing changes in the use cases?
- Is there a protocol for documenting and approving changes to the configuration associated with a use case?
- Is each version of a use case clearly identified and documented?
- Does configuration management facilitate collaboration among team members working on different use cases?
