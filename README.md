# Nov_task

## KHub_Practice Task 3: ICC MEN'S CRICKET WORLD CUP

### Table of Contents
- Introduction
- Problem Statement
- Technologies used
- Project flow
- Components
- Conclusion

 #### Introduction:
  
Step into the heart of cricketing history with our tribute to the ICC Men's Cricket World Cup held in 2011. Celebrating the exhilarating journey of triumph and passion, this website encapsulates the epic tournament where India emerged victorious, capturing hearts with iconic moments like Dhoni's historic six at Wankhede Stadium. Explore the glory of India's second World Cup win, relive the heroic performances of legends like Tendulkar and Dhoni, and delve into the behind-the-scenes magic that made this event an unforgettable chapter in cricket history by using the React components.

#### Problem Statement:

Task is to create your own webpage by using the React components below:

1. Navbar
2. Sidebar
3. Search bar
4. Cards with any kind of information related to your webpage, one image and some content need to be on every card (Minimum of 4)
5. Piecharts, which represents any kind of information related to your webpage (Minimum of 4) 
6. Table with minimum of 5 columns and 4 rows
7. Form [Date and Day selection, Dropdown, Check boxes (min of 3), Radio buttons (min of 2), Text boxes (min of 2), Button]
8. Footer (content related to the webpage you chose)
You should be able to create app pages that show smooth responsive behavior that adapts to screen size as well as device type.The webpage theme and design are your choice.

#### Technologies used:

**Reeact.js :**   React.js simplifies UI development through its component-based architecture, enhancing code reusability and performance optimizations for dynamic web interfaces. Its virtual DOM efficiently updates the actual DOM, leading to faster rendering and improved user experience.

### Install Node.js
If you haven't already installed Node.js, download and install it from the [official Node.js website](https://nodejs.org/). This will also install npm, the package manager for Node.js.

### Create a new React app
Open your terminal or command prompt and use the `npx` command to create a new React app. Run the following command:
```
npx create-react-app client
```

#### Project flow:

The First thing is to create 1 folders named *client* .In client I cretaed three sub folders named assests,components,pages.The folder structure is as follows.
                
![Screenshot 2023-11-17 105401](https://github.com/Madhurithotakua/Nov_task/assets/104493027/87d400af-f7bc-4a84-9197-1eb370e89305)

For frontend we have used *React.js*
-> Initially navigate to the client folder and open the terminal using``` ctrl + shift + ` ``` in vs code or click on new terminal 

->Type cd client .It will navigate to the folder. Then type ``` npm install ```  The necessary files and node modules will be installed.

->We run the frontend part using the command ``` npm start ``` 

This will be the webpage that has to be displayed on running the command and allowed to select or open Dashboard,Cards,Charts,Table,Form.
![WhatsApp Image 2023-11-13 at 01 43 50_f320230f](https://github.com/Madhurithotakua/Nov_task/assets/104493027/c1171f36-e8e8-487e-8111-9b83a377098e)

->Utilizing React.js, the frontend page seamlessly integrates a dynamic Navbar, Sidebar, Search bar, visually appealing Cards displaying essential information with images, interactive Piecharts, a structured Table, a comprehensive Form offering varied inputs, and a Footer enriched with content pertinent to the webpage, delivering a highly functional and engaging user experience.

#### Components:

- **Navbar:**  The navbar in the image contains the following text:
ICC Men's Cricket World Cup
ICC Fan Hub
ICC Insights
ICC Score Tracker
ICC Live Scoreboard
All About Cricket
- **Sidebar:**  The sidebar contains the Dashboard,Cards,Charts,Table,Form.
- **Searchbar:** The searchbar in the image says users can search for anything related to the 2011 ICC Cricket World Cup.
- **Footer:** the text in the footer indicates that your website is a dashboard that provides information about the 2011 ICC Cricket World Cup.
- **Dashboard:**  Dashboard Component - 2011 ICC Men's Cricket World Cup
  
->The `Dashboard` component in this React.js project showcases key highlights and moments from the historic 2011 ICC Men's Cricket World Cup. It includes various sections:

->The component contains different sections with headings highlighting pivotal moments, India's victory, memorable experiences, and insights into cricket equipment. Each section elaborates on its respective topic with descriptive paragraphs and accompanying images.

->Explore more about the 2011 ICC Men's Cricket World Cup by clicking on the provided Wikipedia link, diving deeper into India's triumph and the tournament's significance.

->At the bottom, there's a container with linked logos leading to external sites like Google and Instagram.
![image](https://github.com/Madhurithotakua/Nov_task/assets/104493027/a76a9bd5-7320-4f7c-a124-493f773da3d4)

- **Cards:** The Cards component showcases a main card highlighting the ICC Men's World Cup 2011 victory, along with a series of sub-cards. Each sub-card presents distinct aspects, including historical triumphs, iconic moments, player contributions, behind-the-scenes insights, technological advancements, and memorable cricket moments, all linked to relevant external sources, creating an engaging display of cricket history in a visually appealing format.


- **PieCharts:**  The PieCharts component, built using React and Chart.js, displays informative pie charts highlighting statistical data of players from the 2011 ICC Men's Cricket World Cup. Key features include:
**Visualization of Player Performance**
->Utilizes Chart.js to render pie charts showcasing player statistics such as runs scored and wickets taken during the 2011 World Cup.
->Dynamically generates individual charts for each player using data fetched from the worldCup2011Winners array.
 ![WhatsApp Image 2023-11-13 at 01 43 36_ab078ebd](https://github.com/Madhurithotakua/Nov_task/assets/104493027/42555ca5-d067-40cd-80b0-91240f630cb8)

- **Table:** The Table component, a React-based presentation, renders a comprehensive table showcasing statistical data of players from the 2011 ICC Men's Cricket World Cup:

->Generates an organized table displaying players' details including their names, roles, batting and bowling styles, runs scored, and wickets taken during the tournament.
->Utilizes the worldCup2011Winners dataset to dynamically populate and present player statistics.
![WhatsApp Image 2023-11-13 at 01 43 26_e0ff764e](https://github.com/Madhurithotakua/Nov_task/assets/104493027/182ad8df-1689-4fd0-94da-0e174478a88a)

- **Form:**  The Form component in React facilitates users to share their cricket passion by providing:

->Presents a user-friendly form allowing users to input their preferred dates, favorite cricketers, liked skills, match preferences, memorable moments, and more, fostering an engaging user interaction.
->Utilizes various input types including checkboxes, radio buttons, and text areas to capture diverse preferences and moments related to cricket.
![WhatsApp Image 2023-11-13 at 01 43 13_075d57f6](https://github.com/Madhurithotakua/Nov_task/assets/104493027/329b3cad-965b-474e-81dc-cdcafaf82801)




