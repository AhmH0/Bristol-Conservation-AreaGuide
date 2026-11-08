# Requirements

## User Needs

### User stories
* As a tourist, i would like to find interesting places to visit in Bristol, so i would look for conservation areas with rich history.

* As a tourist i want to view conservation areas around a map so that planning my journey becomes easy.

* As a tourist, reading information about the conservation areas would be good to learn about the historical importance of these areas.

* As a resident, browsing conservation areas in Bristol is something i would do to learn more about the heritage of my local area.

* As a resident, i would want access to information regarding my local areas history and heritage.

* As a system maintainer, i would want to update the conservation area info so that users can stay up to date and receive accurate data.

* As a system maintainer, i want to identify inaccuracies in the data to upkeep the information quality.

### Actors
* Tourists: These are visitors of the city and the main audience of the system, since they'll use it to discover conservation areas, learn about the history and plan their visits.
  
* Residents: People living in the city who would like to use the system to have a chance to explore their local conservation areas, learn about the city's heritage while getting the relevant information about these areas.
  
* System Maintenance team: A person or a group of developers which will maintain the software, as they ensure that data is up to date and accurate, managing the updates, monitoring performance and dealing with possible emerging issues with the software.

### Use Cases
TODO: Describe each use case (at least one per team member).
    Give each use case a unique ID, e.g. UC1, UC2, ...
    Summarise these using the use-case template below.

| Use Case 1 | Search Conservation Areas | 
| -------------------------------------- | ------------------- |
| **Description** | Will allow the user to search through the conservation areas of Bristol simply by entering the name of their area, then based of distance providing them with the nearest conservation area to their location.|
| **Actors** | Tourists and Residents |
| **Assumptions** | Assuming the application is available and the data is accurate and up to date. |
| **Steps** | The user opens the conservation area explorer, enters the name of an area (e.g Kingswood), the system then goes through the data and displays the nearest conservation areas, the user then selects the area and gets to see the location and information on a map. |
| **Variations** | No nearby conservation areas are found, or the user enters an invalid search query, or the dataset isn't currently available.|
| **Non-functional** | The search interface should be easy to use. |
| **Issues** |Some of the areas have lacking information which might limit the amount of search results that the software can provide. |


| Use Case 2 | View conservation area information | 
| -------------------------------------- | ------------------- |
| **Description** | Allows the user to view all the details and information regarding the selected area, such as the description, historical importance, and documents. |
|**Actors** | Tourists and Residents |
| **Assumptions** | Assuming the user picked one of the areas, and that the selected area has valid information within the dataset. |
| **Steps** | The user selects an area, the system picks up information on the area from the data set, the system displays information about the area, user reads the information. |
| **Variations** | Some information isn't available, the selected area has missing data, the dataset cant be accessed.|
| **Non-functional** | The information should be displayed in a readable and accessible format. |
| **Issues** |Some of the areas have lacking information which might limit the amount of search results that the software can provide. |

| Use Case 3 | Maintain conservation area data | 
| -------------------------------------- | ------------------- |
| **Description** | Allows the team maintainers to review then update the information based on the available data, this ensures accuracy and reliability in whats being displayed. |
|**Actors** | Maintenance team |
| **Assumptions** | Assuming the maintenance team has the valid access to the systems so that these functions can be done|
| **Steps** | Maintenance team access the system, they review the existing information and data being displayed, updates the inaccuracies or outdated information, the new information is available to the user. |
| **Variations** | Some of the information cant be updated if the data set still has some missing information or errors. |
| **Non-functional** |Only users with enough authority can be permitted to make these changes to the data, aka the maintenance team members |
| **Issues** |Some of the areas have lacking information which might limit the amount of search results that the software can provide. |

| Use Case 4 | View supporting documents | 
| -------------------------------------- | ------------------- |
| **Description** | Allows the user to access the documents which are provided by the Bristol open dataset, in case the summarized description/information on the area isn't enough, they can view the supporting documents for further information. |
|**Actors** | Tourists and Residents|
| **Assumptions** |The selected conservation area has these supporting documents available. |
| **Steps** | User selects a conservation area, the system displays information on the area, gives the option for further information, user selects further information, system displays supporting documents. |
| **Variations** | Documents aren't available. |
| **Non-functional** |Documents should load within a reasonable time |
| **Issues** |Some of the areas have lacking information which might limit the amount of search results that the software can provide. |

| Use Case 5 | Filter Conservation areas | 
| -------------------------------------- | ------------------- |
| **Description** | Allows the user to filter through the areas that they search for, making it easier to find locations that they would find interesting. |
|**Actors** | Tourists and Residents|
| **Assumptions** | Assuming that the areas data loaded completely |
| **Steps** | User opens a list of conservation areas, applies one or more filter, system process filter request, system displays conservation areas based on the filter. |
| **Variations** | There are no matching conservation areas. |
| **Non-functional** | Filtered results should be accurate to the filter request |
| **Issues** |Some of the areas have lacking information which might limit the amount of search results that the software can provide. |

TODO: Your Use-Case diagram should include all use-cases.

![Insert your Use-Case Diagram Here](images/use-case.png)

## Software Requirements Specification
### Functional requirements
TODO: create a list of functional requirements. 
    e.g. "The system shall ..."
    Give each functional requirement a unique ID. e.g. FR1, FR2, ...
    Indicate which UC the requirement comes from.


### Non-Functional Requirements
TODO: Consider one or more [quality attributes](https://en.wikipedia.org/wiki/ISO/IEC_9126) to suggest a small number of non-functional requirements.
Give each non-functional requirement a unique ID. e.g. NFR1, NFR2, ...

Indicate which UC the requirement comes from.
