**Video Link**: https://www.youtube.com/watch?v=y8JPJ0Z7IjQ

# **"86 No More: A Kitchen Intelligence Solution,"**

In the restaurant industry, efficient inventory management is essential for smooth operations, waste reduction, and maximizing profits. As a team, we have selected **"86 No More: A Kitchen Intelligence Solution,"** an innovative app to streamline inventory management, as our project to work on further. This essay will explore its key features and benefits, discuss initial sign-up challenges, and outline our strategies for **Project 2** to avoid similar issues.

## About "86 No More"

The term "86" in culinary lingo signifies that an item is no longer available or has been removed from the menu, making it a fitting name for this app. "86 No More" ensures a seamless customer experience by offering real-time inventory tracking and alerting managers when ingredients run low, effectively preventing "86" scenarios.

Signing up for "86 No More" is straightforward, granting users access to its powerful features. The user-friendly interface simplifies menu management, allowing for the easy addition of new dishes to keep the menu dynamic. Moreover, the app provides efficient inventory monitoring, displaying current stock levels and sending timely notifications for low quantities or expiring items. Its analytics feature empowers restaurant owners and managers with data-driven insights, guiding informed decision-making for sustainable growth.

## Overcoming Initial Challenges and Lessons Learned

While this application offers many benefits, we must acknowledge the challenges we faced during its installation. Initially, we encountered deprecated dependencies, necessitating extensive upgrades to ensure compatibility. Furthermore, we grappled with Cross-Origin Resource Sharing (CORS) issues. More than adding a Chrome extension was required to run the application as per the existing documentation. To address this, we had to configure the Access-Control-Allow-Origin CORS header in the index.js file to enable communication with the backend REST APIs.

Another hurdle we faced was the console's absence of clear error messages during application runtime. This lack of feedback prolonged the troubleshooting process as we struggled to pinpoint which file required modifications. Another confounding issue during project execution was the format of date inputs on the screens that needed to be clarified. Navigating these date formats became a puzzle, leading to application behavior errors and user dissatisfaction. Finally, one of the most critical features of an inventory management system is the 'Update' option, which enables restaurant owners or employers to update the inventory. However, it was unfortunate that this feature was not working as opposed to what the previous collaborators showed in the demo video.

## Avoiding Future Pain Points in Project 2

Reflecting on the challenges faced during the installation of "86 No More," we recognize several practices that could have been employed to avoid such pain points. In Project 2, we are committing to implementing the following measures:

1. **Thorough Documentation:** We will create comprehensive documentation that outlines the installation process and includes troubleshooting guidelines. This documentation will be valuable for team members and users, ensuring a smoother onboarding experience.

2. **Dependency Management:** To prevent issues related to deprecated dependencies, we will adopt a proactive approach to dependency management. We will be regularly checking for updates using commands like "npm-check -u" to keep our project dependencies current.

3. **CORS Handling:** We have learned the importance of understanding CORS and its implications. In Project 2, we will proactively address CORS-related challenges by configuring the necessary headers and providing clear instructions in our documentation.

4. **Enhanced Error Handling:** We will implement robust error handling mechanisms in our project to streamline troubleshooting. Clear and informative error messages will be a priority, enabling quicker identification and resolution of issues.

5. **Dependency Version Transparency:** We will ensure that team members, especially those new to technologies like React and Node, can access clear information about project dependencies and their versions. This transparency will facilitate a smoother development process.

6. **Fixing "Update Item" Functionality:** We acknowledge the significance of a fully functional "Update Item" feature. In Project 2, we commit to thoroughly testing and debugging this critical functionality to ensure it operates as intended, rectifying the frustrations encountered.

7. **Integration of Calendar API:** To overcome the perplexing date format confusion and enhance accuracy, we plan to integrate a Calendar API into our application in Project 2. This integration will empower us to determine and manage purchase and expiration dates precisely, reducing user errors and increasing the application's reliability.

8. **Email Alerts:** In Project 2, we will embark on an extensive effort to incorporate email notifications, ensuring that users and all relevant stakeholders benefit from timely and reliable communication within the application. We are committed to enhancing the overall user experience by seamlessly integrating this vital feature, enabling efficient communication across the board.

We will also be enhancing the application's user interface in addition to the changes stated in Project 2 to make it more user-friendly. Our dedication to constant improvement addresses new problems, improves functionality, and includes user-driven additions. Through an accessible GitHub repository for updates, we will maintain openness and cooperation. This strategy guarantees "86 No More" stays active and ensures smooth running.

