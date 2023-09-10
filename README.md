# frontend-challange-result-summary

# Table of contents 

  * **Overview**
  * **The Challenge**
  * **Key Code Sections**
       * **CSS Styling**
       * **JavaScript**
  * **What I Learned**
  * **Continued Development**
  * **Author**
  * **Acknowledgments**

 # Overview
 
The Result Summary Challenge is a web application designed to display a user's test result and related category scores. It showcases the result in an aesthetically pleasing and responsive manner.

 # The Challenge
 
The main challenge was to create a visually appealing layout that adapts to different screen sizes. The result needed to be presented along with individual category scores. I also wanted to ensure that the design looked great on both desktop and mobile devices.

# Key Code Sections

* **CSS Styling**

I began by defining the styles for various elements in the project. Here are some key CSS sections:

**Body:** I set the background color to "whitesmoke" and added basic padding to the body element.

**Containers:** I created two containers: "container" and "container1." These containers have different styles and are used to structure the layout.

Text Styling: I defined styles for headings (h4, h6, h1, h3), paragraph text (para), and headers. I used appropriate colors and padding to make the content visually appealing.

**Category Boxes:** I created a box design with a circular shape (class "box"). This box includes the user's score and adapts its size based on the content. It also has a gradient background and a subtle box shadow.

**Responsive Design:** To ensure the design was responsive, I used media queries for screens with a maximum width of 375px (e.g., mobile screens). This ensured that the layout adapted smoothly.

* **JavaScript**

JavaScript was used to dynamically populate the content based on data from a JSON file. Here's what I did:

**Fetching Data:** I used the fetch API to load data from a JSON file (data.json) that contains the user's result and category scores.

**Populating Data:** I dynamically inserted data into HTML elements. For instance, the user's score, maximum score, and grade were populated into the respective elements. I also added the description text, which could include line breaks (\n).

**Category Boxes Generation:** I generated category boxes based on the data in the JSON file. Each category box includes the category name, an icon (placeholder), the category score, and the maximum score.

# What I Learned

While working on this project, I gained valuable insights into web development. Here are some key takeaways:

**Flexbox:** I improved my understanding of how Flexbox works, allowing for flexible and responsive layouts.

**CSS Custom Properties:** I explored the use of CSS custom properties (variables) to enhance maintainability.

**Media Queries:** I learned how to use media queries effectively to create responsive designs that adapt to different screen sizes.

# Continued Development

In future projects, I plan to focus on the following areas for improvement:

Grid Layout: I want to delve deeper into CSS Grid to create even more flexible layouts.

Font Variables: Incorporating font variables into my stylesheets to streamline font management.

Icon Integration: I aim to add real icons instead of placeholders for a more polished look.

# Author

Frontend Developer: Ganga sravani (https://www.frontendmentor.io/profile/Gangasravani12)

# Acknowledgments

I'd like to acknowledge the Frontend Mentor community and the resources available online. Additionally, a special shoutout to ChatGPT, which assisted me in solving specific design challenges.

 # Links

 * **Solution link :** https://github.com/Gangasravani12/frontend-challange-result-summary.git

 * **Live site Url :**  https://gangasravani12.github.io/frontend-challange-result-summary/
