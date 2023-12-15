
![Logo](https://github.com/akm-engineer/mern-deploy-movie-app/blob/master/app/public/favicon.png?raw=true)


# 5 Star MRP


I am introducing a cutting-edge movie review application with the latest MERN (MongoDB, Express.js, React.js, Node.js) technologies. This feature-rich platform boasts both an admin panel and a user panel, offering a seamless experience for movie enthusiasts.

Within the admin panel, administrators have the privilege to effortlessly upload and manage movies via a user-friendly form, as well as add and update actor information. On the user panel, individuals can explore a curated collection of movies, access engaging trailers, and provide insightful ratings—exclusively available to authenticated users.

Furthermore, users have the flexibility to refine their movie reviews by leveraging the edit feature, ensuring their opinions are accurately reflected. This innovative movie review app provides a dynamic and interactive space for administrators and users, enhancing the cinematic experience.

## Tech Stack

**Client:** React, TailwindCSS

**Server:** Node, Express, MongoDB

**Cloud Storage:** Cloudinary

**Email Testing:** Mailtrap


## Steps to run the project on your machine

1. Download the Vs Code IDE on your machine
2. Download the zip file of the GitHub repository
3. Extract all the files in the folder on your device
4. Open the folder in VS Code
5. Open the terminal and add ```npm install```
6. Run the command ```npm start```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`JWT_SECRET`

`MONGO_URL`

`MAIL_TRAP_USER`

`MAIL_TRAP_PASS`

`CLOUD_API_SECRE`

`CLOUD_API_KEY`

`CLOUD_NAME`

`PASSWORD_URL`

## Getting into the Project
## Admin Panel
- This **homepage** provides an overview of our platform, displaying key metrics such as the total number of uploaded movies, the overall count of registered users, and the number of reviews contributed by authorized users. Additionally, it features a comprehensive list of all uploaded movies, allowing administrators to designate them as either public or private. Private movies are exclusively accessible to admin users. Users can easily edit movie details, ensuring accurate information, and remove any irrelevant movies through the deletion functionality.
Furthermore, on the right side of the homepage, users can find a section highlighting the top-rated movies. These rankings are determined based on the number of reviews submitted by users, providing a glance at the most highly regarded films on the platform.

- Users have the flexibility to personalize their experience on the platform by changing the **theme** according to their preferences. This feature enables users to customize the visual appearance of the interface, allowing them to select a theme that aligns with their preferred color scheme or aesthetic. Whether opting for a dark mode for reduced eye strain in low-light conditions or choosing a light theme for a brighter look, users can tailor the platform's appearance to enhance usability and suit their individual preferences.
![admin-panel](https://github.com/akm-engineer/mern-deploy-movie-app/assets/118009781/c7c7c17f-eb9e-4e4a-b7dd-77f47fc9c93d)


- The 'Movies' section serves as a comprehensive hub for all activities related to movies, facilitating CRUD (Create, Read, Update, Delete) operations. Users can seamlessly manage and manipulate movie data, including adding new entries, viewing existing details, updating information, and removing irrelevant content. This centralized area ensures efficient and user-friendly control over all aspects of the movie-related functionalities on the platform.
![admin-panel-movies](https://github.com/akm-engineer/mern-deploy-movie-app/assets/118009781/b02d0560-2a06-4839-89cd-408997ed734d)

- Adding the **Trailer** of the Movie

![adding-movie-1](https://github.com/akm-engineer/mern-deploy-movie-app/assets/118009781/072e7dce-6881-49dd-b38d-ec166c433c82)

- **While the trailer is currently in the process of uploading to our cloud storage, we can fill in the remaining details.**

![adding-movie-2](https://github.com/akm-engineer/mern-deploy-movie-app/assets/118009781/1062d892-a0c0-4f26-a05b-7deaa73bead4)

- The 'Actors' section is designed exclusively for administrators, providing a centralized repository of all actors, both male and female, associated with the movies. Admins have the privilege of performing CRUD operations on actors, enabling them to add, view, update, and delete actor details. The actor form within this section serves as a dedicated tool for admins to input and modify basic actor information, ensuring that the platform maintains accurate and relevant actor details accessible only to authorized administrators.
The platform includes a search feature that allows users to search for both movies and actors seamlessly. This search area provides a convenient tool for users to find specific movies or actors quickly. Whether looking for a particular film or actor, users can enter relevant keywords into the search bar, and the platform will return results that match the search criteria. This functionality enhances user experience by making it easy to locate specific content without navigating through extensive lists manually.
![admin-panel-actors](https://github.com/akm-engineer/mern-deploy-movie-app/assets/118009781/44307af8-2cd8-416b-81ba-29f9598aabce)

- **Updating the Actor Section**

![updateing-actor](https://github.com/akm-engineer/mern-deploy-movie-app/assets/118009781/2d3f1b70-164a-4dcb-9dab-4df3c9d5b6e4)

## User Panel
![users-panel](https://github.com/akm-engineer/mern-deploy-movie-app/assets/118009781/5c5e7025-517e-48f1-9aee-a46b25b6624c)

- The User Panel provides users with a rich array of features for an engaging experience:

1. **Movie Catalog:**
    Access a comprehensive list of movies uploaded by administrators.

2. **Search Functionality:**
    Utilize the search bar to quickly find specific movies based on keywords.

3. **Trailer Viewing:**
    Click on a movie to watch its trailer, gaining a preview of the content.

4. **User Ratings:**
    Sign up and become authorized to rate movies, express your opinions and contribute to the community.

5. **Reviews Section:**
    View reviews made by other users, gaining insights into different perspectives on each movie.

6. **Review Editing:**
    Edit your reviews to ensure they reflect your evolving thoughts and opinions.

7. **Cast Details:**
    Explore the cast of a movie by clicking on their names, revealing additional details about the actors.

8. **Related Movies:**
    Discover related movies based on tags, allowing you to explore content with similar themes or genres.
- This user-centric approach aims to provide a seamless and interactive platform, enhancing your overall experience and connection with the content.


