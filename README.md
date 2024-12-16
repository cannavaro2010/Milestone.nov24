# News Daily Website

This project is a simple **newspaper website** built using **HTML**, **CSS**, and **Bootstrap**, featuring a responsive layout with news articles, 
weather information, and social media icons. The website uses real-time information from **Google Images**, **Sky News**, and **UK Weather API** to display news and weather data.
Additionally, it integrates **Font Awesome** for social media icons in the footer.

### Created By:
**Youssef Abassir**

## Project deployed link :
https://cannavaro2010.github.io/Milestone.nov24/index.html

### Feel free to use it!

---

## Features

- **Responsive Design**: The website is mobile-friendly, using **Bootstrap** to ensure it looks great on all devices.
- **News Section**: Displays the latest news articles and updates using data sourced from **Sky News**.
- **Weather Section**: Provides current weather information using the **UK Weather API**.
- **Social Media Integration**: Displays social media icons for Facebook, Instagram, and Twitter in the footer using **Font Awesome**.
- **Simple Navigation**: The website includes a navigation bar for easy access to the Home, Articles, and Contact pages.

---

## Project Structure

/NewsDailyWebsite  ├── /css │ │ └── style.css # Custom CSS styles │ └── /img │ └── logo.png # Logo for the site ├── /index.html
# Homepage (News Feed) ├── /article.html # News Articles page ├── /contact.html
# Contact Form page ├── /submit_form.php # Backend script to handle contact form submissions └── README.md 
# Project documentation (this file)
## Project Screenshots 





![image03](https://github.com/cannavaro2010/Milestone.nov24/blob/main/Img/screenshot2.jpg)

![image02](https://github.com/cannavaro2010/Milestone.nov24/blob/main/Img/screenshot3.jpg)

![screenshot1](https://github.com/cannavaro2010/Milestone.nov24/blob/main/Img/screentshot01.jpg)

## Project Wireframe


![screenshot1](https://github.com/cannavaro2010/Milestone.nov24/blob/main/Img/wireframe.jpg)

## Technologies Used

- **HTML**: The basic structure and content of the website.
- **CSS**: Custom styling to make the website look visually appealing.
- **Bootstrap 5**: Used for responsive design and grid layout.
- **Font Awesome**: For social media icons (Facebook, Instagram, Twitter).
- **Sky News API**: For fetching the latest news articles.
- **UK Weather API**: For showing real-time weather data.
- **Google Images API**: For displaying relevant images for articles (optional).

---

## Pages Structure

### 1. **Home Page (index.html)**
   - Displays the latest news articles.
   - Includes weather information for the UK.
   - Displays social media links in the footer (Facebook, Instagram, Twitter).

### 2. **Articles Page (article.html)**
   - Displays a list of news articles.
   - Allows users to view detailed information about each article.

### 3. **Contact Page (contact.html)**
   - Contains a contact form that allows users to send messages or inquiries.

---

## External Resources Used

1. **Google Images API**:
   - Used to fetch relevant images for the articles.
   - API documentation: [Google Custom Search API](https://developers.google.com/custom-search/v1/overview)

2. **Sky News API**:
   - Used to fetch the latest news articles.
   - API documentation: [Sky News API](https://developer.sky.com/docs/news-api)

3. **UK Weather API**:
   - Provides real-time weather data.
   - API documentation: [UK Weather API](https://www.metoffice.gov.uk/services/data)

4. **Font Awesome**:
   - Used for social media icons (Facebook, Instagram, Twitter).
   - Website: [Font Awesome](https://fontawesome.com/)

5.**Codes Html Css Bootstrap**:
  -https://www.w3schools.com/
  -https://getbootstrap.com/
  

---

## System Requirements

- **Web Browser**: Any modern web browser (Chrome, Firefox, Safari, Edge).
- **Internet Connection**: Required to load images from Google and news/weather data from the APIs.
- **Server**: To run the PHP backend script (`submit_form.php`) for the contact form. You can use **XAMPP** or **MAMP** for local development or deploy it to a live server.
  
### Steps to Run the Website Locally

1. **Clone this repository**:
   ```bash
   git clone https://github.com/cannavaro2010/Milestone.nov24.git

   License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions or inquiries, feel free to reach out to me at abassir@hotmail.fr.

### Explanation of Sections in the README:

- **Project Description**: A brief overview of the project.
- **Created By**: Mentions your name as the creator of the project.
- **Features**: Lists the key features of the website.
- **Project Structure**: Shows the folder structure of the project and which files are included.
- **Technologies Used**: Describes the core technologies used in the project (HTML, CSS, Bootstrap, Font Awesome, APIs).
- **Pages Structure**: Describes the purpose and content of each page.
- **External Resources**: Lists all external APIs and resources used (Google Images, Sky News, UK Weather, and Font Awesome).
- **System Requirements**: Details what is needed to run the project locally or on a server.
- **Steps to Run the Website Locally**: Step-by-step guide to set up and run the project on a local server.
- **License**: Information about the project’s license (MIT in this case).
- **Contact**: A place for your email or other contact information.

---

### Font Awesome Social Media Icons

You may want to customize the social media icons further by using additional Font Awesome classes to adjust their size or appearance. 
Here’s an example to increase the icon size:

```html
<i class="fab fa-facebook-f fa-2x"></i>  <!-- This will make the icon 2x larger -->
