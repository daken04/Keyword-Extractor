# Keyword-Extractor
 Powered by OpenAI, using React, Vite, and Chakra UI

So, in this project, I'm building a keyword extractor web application using React and the OpenAI API. The goal is to create a tool that can extract keywords from text input provided by the user. Let me break down the different aspects of the project.

First, I'm using React, a JavaScript library, to develop the user interface. React allows me to create interactive components and efficiently manage the application's state.

To center the elements and structure the layout, I'm using components like Box and Flex. These components help me achieve a visually appealing and responsive design.

To gather user input, I'm setting up a form with an input field where users can enter the text they want to extract keywords from. I'll use React's State to keep track of the input's value and update it as the user types.

When the user submits the form by clicking a button, I'll trigger the keyword extraction process. This involves sending the user's input to the OpenAI API and requesting the extracted keywords. During this process, I'll set a loading state to indicate that the extraction is in progress.

Once the API responds with the extracted keywords, I'll format the response and display it to the user. I plan to use a modal component to show the keywords in a visually appealing manner. The modal will be shown when the data is fetched, and it will automatically close once the keywords are displayed.

