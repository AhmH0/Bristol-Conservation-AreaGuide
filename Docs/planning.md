# Project Proposal

## Business Case
The dataset I decided to pick was the [Conservation areas](https://arcg.is/1OubTP1) in Bristol Dataset. 

### Problem statement
The dataset showcases the conservation areas within Bristol, these are areas of special architectural and historic interest, giving them the need to be preserved. For some people, both tourists and residents of the city - finding information regarding these historic areas within the city could be difficult, this is mainly due to the fact that these users would have to go through several websites, watch countless videos and go through documents to get a grasp on these historically rich areas and monuments, this limited accessibility makes it difficult for individuals to interact with the city's heritage, and makes planning tourist trips tedious.
To get into more detail, picking out one of the conservation areas that Bristol open data provides - the "St James's Parade", if I were interested in planning a visit to this location, id have to go through a 43 page document that explains the heritage and reason behind this areas conservation and historical importance. 
As I mentioned, this lack of accessibility to this information for the general public makes it hard for people to interact with the city's heritage, and so, we would lose the historical importance as people become less and less educated, so, having a solution to this issue is important in maintaining Birstols rich history and heritage.

### Business benefits
Since Bristol receives 9 million tourists in a year, this platform would mainly be appealing towards them, as they'd be the main target audience, although residents who are interested in their city's heritage might also find it appealing. A lot of the benefits that would come from this platform would be regarding helping out users plan out their visits to the city, and thus, as it becomes easier to plan these trips, tourism revenue for the city would increase, and it would create opportunities for the local businesses as tourism rates increase. 
So not only would this platform be beneficial to tourists or history interested residents, as it makes information and planning more accessible, time efficient and easy, but it would also be beneficial to the local communities around these areas as tourist revenue builds up.

### Options Considered
The application lets the user search for different conservation areas in the city, while also showcasing information (facts) regarding the said area they choose to visit, it even shows where its located on the map, and allows for easier planning for tourists or anyone interested in visiting them. It saves the user time as they wouldn’t have to do the research on their own – the application compiles all the data in one place. 

This solution was filtered out of two other platforms that i thought of, those two being:
- a basic HTML site that isn't interactive, simply showcases the name of the conservation area, the location of it, and an image of on it on the map. This would be nowhere near as detailed as my current solution, it would be very quick to make as it has a simple design, however, it doesn't solve the main issue that is making information easy to access, since the user would have to manually go through a long list of conservation areas and pick out the ones they find interest in.
- an app for ios and android was another thought i had regarding the solution, since it would be very smooth, easy to navigate and convenient, but it was also rejected like the HTML site, since unlike a web platform, an app would require downloading and would need a lot more thought put into when it comes to implementation, and its unlikley for people to look up and download an app when a website can display the same information without needing to download.

Based on competitor research that I have done, ["Visit Bristol"](https://opendata.bristol.gov.uk/datasets/conservation-area-dataset/explore?location=51.456558%2C-2.601034%2C-1.00&showTable=true) is the main competitor that I could find, as they also provide information mainly aimed towards tourists, regarding the best areas to visit in the city, while also giving a function on their website that makes planning easier. 
- Visit Bristol mainly intends to GUIDE tourists and help them explore and find attractions in bristol

- It showcases information on the attraction, visitor guides and historic places within the city, and also has a planner feature which can be used to plan your trip

- Although it is a very useful application in terms of providing information that people visiting Bristol would need, it doesnt focus on conservation areas, which is what I think highlights the difference between them and my platform.

### Expected Risks
Some of the risks and challenges I can see coming up during the development of the application would be mainly around making sure it's easy to use, and that there might be a limited amount of information in the dataset regarding some of these conservation areas. However, most of these can be dealt with as I do continuous tests and handle errors properly. 
In more detail, here are some of the risks i could identify around my project, and their possible solutions:

-  The Dataset could have missing details or unfilled fields, like a conservation area could have its description or document missing, which could lead to a lack in data and affect the information I can provide the user. To avoid this, before deciding which data to display, I have to thoroughly check if all the fields are available and in case its missing, you could display it as "unavailable information".

-  The data from open data Bristol can have some inaccuracies or could even be outdated, so some of the areas that i would have as conservation areas might no longer be one, so to avoid this inaccuracies i would fact check my data before displaying it, to ensure that its up to data and valid. 

## Project Scope
The system of interest would be the "Bristol Conservation Areas Explorer", which includes these features and components: 

*A display of information regarding these conservation areas, which come from the Bristol Open Data platform.

*It allows users to look for and browse through the conservation areas.

*It showcases the location of these conservation areas.

*A user friendly interface made with the help of HTML, CSS and Javascript.



<img width="1087" height="827" alt="image" src="https://github.com/user-attachments/assets/6c071860-ce05-4ab5-97a9-16e01ac5d1dd" />

