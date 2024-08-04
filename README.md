</p>
<h1 align = 'center'>Issue Tracker Application</h1>
<br>
</p>

### Description:
The Issue Tracker Application is a web-application built using Nextjs and TypeScript for frontend as well as backend and Tailwind CSS for styling. The application aims to provide a streamlined process for users to submit, track, and manage issues efficiently. Users can authenticate themselves using Google Cloud OAuth, ensuring secure access to the application. The submitted issues are stored in a MySQL database managed by Prisma ORM.

### Techn Stack
Here are the technologies I used in this project:

<div style="display: flex; flex-direction: row;">
<img src="Images/typescript.png" width="75" height="75" style="margin-right: 25px;">
<img src="Images/next-js.svg" width="75" height="75" style="margin-right: 25px;">
<!-- <img src="Images/icons8-nodejs-128.png" width="75" height="75" style="margin-right: 25px;"> -->
<img src="Images/icons8-prisma-orm-100.png" width="75" height="75" style="margin-right: 25px;">
<img src="Images/icons8-tailwind-css-144.png" width="75" height="75" style="margin-right: 25px;">
<img src="Images/icons8-mysql-100.png" width="75" height="75" style="margin-right: 25px;">
</div>

`Frontend` : Next.js,Tailwind CSS <br>
`Backend` : Next.js <br>
`Database` : MySQL,Prisma ORM <br>
`Authentication` : Nextauth, Google cloud OAuth <br>

### Screenshots
Here are some Output images of this project:

<div style="display: flex; flex-direction: row; padding-bottom: 30">
<h3> Dashboard: </h3>
<img src="Images/Output/Dashboard Image - 1.jpg" width="800" style="margin-right: 50; margin-bottom: 50;">
<img src="Images/Output/Dashboard Output -2.jpg" width="800" style="margin-right: 50; margin-bottom: 50;">
<h3> Issue: </h3>
<img src="Images/Output/Issue Image.jpg" width="800" style="margin-right: 50; margin-bottom: 50;">
<h3> Google Authentication: </h3>
<img src="Images/Output/Authentication.jpg" width="800" style="margin-right: 50; margin-bottom: 50;">
<img src="Images/Output/Google Authentication.jpg" width="800" style="margin-right: 50; margin-bottom: 50;">
</div>

### Features:

- **User Authentication:** Users can securely authenticate using Google Cloud OAuth, ensuring their identity and protecting the application from unauthorized access.

- **Issue Submission:** Authenticated users can submit issues via a user-friendly interface. They can provide detailed descriptions, tags, and priority levels for each issue.

- **Issue Tracking:** The application allows users to track the status of submitted issues. Each issue can be in one of the predefined states: submitted, in-progress, or resolved.

- **State Management:** The frontend interface dynamically updates to reflect the current state of each issue. Users can easily identify which issues are pending, being worked on, or resolved.

- **Database Integration:** Prisma ORM is used to interact with the MySQL database, providing seamless integration and efficient data handling.

- **Responsive UI:** The frontend UI is built using React, ensuring a responsive and intuitive user experience across different devices and screen sizes.

- **Styling with Tailwind CSS:** Tailwind CSS is utilized for styling, enabling rapid development and customization of the user interface.



Overall, the Issue Tracker Application provides a robust solution for teams and organizations to effectively manage and resolve issues, ensuring smooth workflow and enhanced productivity. With its user-friendly interface, secure authentication, and comprehensive features, it serves as an indispensable tool for tracking and resolving issues in various projects and domains.

