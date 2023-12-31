# Track It

[Click here](https://croftsdeveloper.github.io/track-it/) to view the live web application.

## Table of Contents

- [Project Development & Planning](#project-development--planning)
  - [Project Goals](#project-goals)
    - [Project Purpose](#project-purpose)
    - [Client Background](#client-background)
    - [Client Goals](#client-goals)
    - [User Goals](#user-goals)
  - [Research](#research)
    - [Market Review](#market-review)
    - [Existing Product Audit](#existing-product-audit)
    - [Key Takeaways](#key-takeaways)
  - [User Stories](#user-stories)
  - [Design, Layout & Structure](#design-layout--structure)
    - [Wireframes](#wireframes)
    - [Structure](#structure)
    - [Colour](#colour)
    - [Fonts](#fonts)
  - [Technologies Used](#technologies-used)
    - [Languages](#languages)
    - [Tools](#tools)
  - [Features](#features)
    - [Whole Site](#whole-site)
    - [Home Page](#home-page)
    - [Future Features](#future-features)
  - [Testing](#testing)
    - [HTML Validation](#html-validation)
    - [CSS Validation](#css-validation)
    - [Accessibility](#accessibility)
    - [Performance](#performance)
    - [Responsiveness / Device Testing](#responsiveness--device-testing)
    - [Browser Compatibility](#browser-compatibility)
    - [Bugs & Fixes](#bugs--fixes)
    - [Testing User Stories](#testing-user-stories)
    - [Feedback Incorporation](#feedback-incorporation)
  - [Deployment](#deployment)
  - [Credits](#credits)

## Project Development & Planning

### Project Goals

#### Project Purpose

"Track It" aims to help individuals efficiently manage and monitor their finances without any hassle.

#### Background

As a debt advisor, I regularly see clients facing difficulties when trying to track and present their financial details. This challenge led to the idea of "Track It".

#### Client Goals

- Provide a simple and easy-to-use platform for financial tracking.
- Offer real-time financial summaries, allowing users to have immediate insights.
- Ensure flexibility for users to edit or delete their financial entries.
- Incorporate a reset feature for those wanting a fresh start.

#### User Goals

"Track It" serves a wide range of users, especially:

1. **Individuals on a Budget**: People with a need of monitoring their personal finances.
2. **Professionals**: Professionals with varying monthly incomes and expenses.
3. **Debt Advisory Clients**: Those who need a structured way to document financial data for advisory sessions.

### Research

#### Market Review

Before starting the development of "Track It", I completed a search for free budget trackers. I struggled to find some that could be accessed immediately.

#### Existing Product Audit

A number of existing financial tracking products were explored in-depth. Many lacked the simplicity and intuitiveness required for a Debt Advisory Client. I found that most required the user to sign-up or go through various pages to get to the tracker functionality.

#### Key Takeaways

1. **Simplicity is Crucial**: The most successful products were those that prioritised user experience and simplicity.
2. **Flexibility and Control**: Users prefer control over their entries, especially editing and deletion.
3. **Clarity and Real-Time Updates**: Immediate insights and clear summaries were pivotal.

### User Stories

**User Story 1:** As an individual new to budgeting:

- Grasp the core functions of "Track It".
- Seamlessly input monthly income and daily expenses.
- View real-time financial summaries.
- Edit or delete entries when needed.

**User Story 2:** As a freelancer:

- Quickly add varying monthly incomes.
- Note down both work and personal expenses.
- Get an instant snapshot of finances.
- Edit entries as situations change.

**User Story 3:** As a debt advisory client:

- Compile financial data for the session.
- Navigate a simple and intuitive layout.
- Export or print the financial summary for meetings.

### Design, Layout & Structure

In crafting "Track It", I prioritised a design that speaks to its core functionality - tracking finances. The interface needed to be straightforward, inviting, and avoid unnecessary frills. A neutral colour palette was chosen, striking a balance between simplicity and professionalism, ensuring users find the platform approachable yet dependable.

#### Wireframe

As the project was intended to be simlpe, I made a basic wireframe. By laying out the basic design groundwork, it allowed for a clearer vision of the user's journey, ensuring a simple experience.

[VWireframe Screenshot](https://ibb.co/9Z4cMqT)

#### Colour

A neutral colour palette was chosen for "Track It". This not only provides a clean backdrop for users to focus on their finances but also exudes a sense of professionalism and reliability.

#### Fonts

For the typography, I focused on fonts that are readable and clean. This ensures that users can easily comprehend their financial details, especially when dealing with multiple entries.

### Technologies Used

In building "Track It", I've utilised a combination of languages and tools to achieve a clean user experience:

#### Languages

- **HTML**: Used for structuring the content of the web application.
- **CSS**: Applied for styling, ensuring the interface is user-friendly and responsive.
- **JavaScript**: Powers the dynamic features, providing real-time updates to users.

#### Tools

- **Git & GitHub**: These were used for version control and code storage.
- **VS Code**: My preferred code editor
- **GitHub Pages**: Provides a stable hosting environment for "Track It".
- **ImgBB**: Used for hosting images.

### Features

- **Currency Selection**: Users can select from various currency options to tailor their financial tracking experience.

- **Income & Expense Entry**: Distinct sections for documenting income and expenses, each with a dedicated form for easy data entry.

- **Live Financial Summary**: As data is entered, a running total of income, expenses, and the balance is displayed. A negative balance is clearly indicated in red, drawing attention to overspending.

- **Reset Option**: Users can clear all data with a single click, offering a fresh start for a new month or financial period.

- **Data Persistence**: The application utilises local storage, ensuring that financial records persist between browser sessions.

The streamlined features of "Track It" are designed with user convenience in mind, ensuring efficient and effective financial tracking.

## Future Features

To cater more closely to the needs of our users, especially individuals new to budgeting, I have identified a few key enhancements:

- **Data Export and Reports**:

  - Generate monthly or yearly financial reports. Export them as PDFs or spreadsheets, making it easier to share, print, or archive for future reference.

- **Expense Categories**:

  - Categorise expenses like food, transport, or entertainment. This fine-tuned approach can give individuals a deeper insight into where their money goes each month, aiding in more informed budgeting decisions.

- **Expense Alerts**:
  - Receive notifications when your spending in a particular category exceeds the monthly average or a set threshold, ensuring you're always in the know.

As "Track It" grows, feedback from users will pivotal role in shaping these features, ensuring it focuses on a user-centric approach.

## Testing

Throughout the development of "Track It", I ensured that testing was at the forefront of the process. This section aims to provide a detailed breakdown of all the tests conducted, their results, and any fixes applied based on the feedback from my previous project.

### HTML Validation

The structure of the website was checked using the [W3C HTML Validator](https://validator.w3.org/). By doing this, I could guarantee that the site adhered to the latest web standards and was devoid of structural issues. [View HTML Validation Screenshot](https://ibb.co/5BKmYQR)

### CSS Validation

To ensure our styling maintained best practices, I passed the stylesheets through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).
[View CSS Validation Screenshot](https://ibb.co/VmGvHC3)

### Accessibility

A combination of [AXE](https://www.deque.com/axe/) to check its accessabilitY. [View AXE Validation Screenshot](https://ibb.co/2s1Sr8x)

### Performance

Performance metrics were captured using [Google Lighthouse](https://developers.google.com/web/tools/lighthouse). This ensured that user have a fast experience.[View lighthouse Screenshot - Desktop](https://ibb.co/4gTYqzq)

### Responsiveness / Device Testing

To ensure "Track It" delivers a seamless experience across different devices, I adopted a systematic approach to device testing:

- **Manual Testing on Physical Devices:**  
  Initially, I began with hands-on testing using devices I had access to. This included a desktop monitor, a tablet, and android & apple smartphone models. This hands-on approach gave me a feel for the user experience.

  #### **Button Functionality Test**:

- **What I Expected**: When a user clicks on any button, it should promptly trigger the intended action without glitches.
- **What I Did**: I interactively tested every button on the site.
- **Outcome**: All buttons were responsive and performed their designated functions without issue.

#### **Responsive Design Test**:

- **What I Expected**: "Track It" should look professional and be fully functional across different device sizes.
- **What I Did**: I accessed the site on various devices and also employed browser developer tools to emulate a range of screen sizes.
- **Outcome**: The site maintained its aesthetics and functionality across all sizes, confirming its responsive design.

#### **Input Field Functionality Test**:

- **What I Expected**: Users should be able to input financial details into the provided input boxes effortlessly.
- **What I Did**: I tried entering various types of data into all input boxes.
- **Outcome**: Each input box accepted and showcased the data as intended. They also resisted any inappropriate data types.

- **Browser Developer Tools:**  
  Using the built-in responsive design modes in browsers like Google Chrome and Mozilla Firefor, I was able to emulate a variety of screen sizes and resolutions, simulating the look of the app across a spectrum of devices.

- **Feedback Loop:**  
  Gathering feedback from family was important. They tested the application on their devices, providing insights into any quirks or issues that I might have missed.

Through this approach, I ensured that "Track It" not only looks appealing but also functions consistently, regardless of the device it's accessed from.

### Browser Compatibility

"Track It" was tested on major browsers including Google Chrome, Firefox, Safari, and Microsoft Edge to ensure a uniform experience.

### Bugs & Fixes

Throughout the development, several bugs were encountered and promptly addressed:

- **Button Alignment**: There were visual discrepancies with the alignment of buttons. This was fixed by adjusting the padding.
- **Spacing Issues**: Uneven spacing between the Income and Expenses sections was detected and fixed by adjusting their respective padding.
- **List Item Alignment**: The edit button in the list items was misaligned, which was rectified by modifying its CSS.
- **Delete Button Malfunction**: An issue where the delete button did not function immediately after adding an item was identified and fixed.
- **Summary Section Layout**: The summary section appeared too close to the expense section, which was resolved by adjusting padding and margin.
- **Local Storage & Currency Formatting**: Issues like NaN errors and inconsistent currency symbols after changing the dropdown were addressed with a revamp of the code implementations.

### Testing User Stories

Each user story was put to the test to align the project better with user needs:

### Testing User Stories

##### User Story 1: As an individual new to budgeting

- **Expected**:
  The platform should allow users, especially those new to budgeting, to intuitively understand its core functionalities. They should be able to input monthly income and daily expenses without any issues and instantly see the outcome.

- **Testing**:
  Invited a family member who has never used a budgeting tool before. Watched as they navigated "Track It", asking them to input example incomes and expenses and interpret the result.

- **Result**:
  The friend was able to navigate the application, input data, and understand the summaries without any guidance. They appreciated the simplicity and clarity of the interface.

- **Fix**:
  Based on this feedback, no immediate changes were deemed necessary.

---

##### User Story 2: As a freelancer

- **Expected**:
  Freelancers, who often have fluctuating incomes and both personal and work-related expenses, should find it easy to input varying amounts of income and document different kinds of expenses. They should get a clear snapshot of their financial status at any given moment.

- **Testing**:
  Approached a freelance debt advisor in my network and asked them to use "Track It" to chart their finances for the past month, observing their interactions and gathering feedback afterwards.

- **Result**:
  The user was able to easily add different income streams and categorise various expenses, finding the live financial summary useful for gauging their monthly balance.

- **Fix**:
  No modifications were needed, but the advisor did express interest in having a feature to categorise expenses in the future.

---

##### User Story 3: As a debt advisory client

- **Expected**:
  Debt advisory clients should be able to quickly compile and document their financial data in preparation for advisory sessions. The interface should be straightforward and not add to their financial stress.

- **Testing**:
  Shared "Track It" with one of my advisory clients 10 minutes before a session, asking them to prepare their financial summary using the tool and reviewed the laptop during our session. After our session, gathered feedback on their experience.

- **Result**:
  The client found the tool much simpler than other methods they've used in the past. They especially appreciated the clear distinction between income and expenses and the real-time balance calculation. It also allowed me to look through the expenses in a clear way.

- **Fix**:
  The client suggested a potential feature to export or print the summary for meetings that were not face to face, which could be considered for future versions.

### Feedback Incorporation

From the feedback received on the previous project:

- **README Improvement**: Significant enhancements were made to the README, providing a more detailed account of the project, its features, and the testing process.
- **Directory Structure**: The project directory structure was refined to follow standard conventions.

## Deployment

### GitHub Pages

The site was deployed to GitHub Pages using the following steps:

1. Navigate to the main page of the GitHub repository at [https://github.com/CroftsDeveloper/track-it](https://github.com/CroftsDeveloper/track-it).
2. Under the repository name, click on the "Settings" tab.
3. Scroll down to the "GitHub Pages" section.
4. From the "Source" dropdown, select the "main" branch.
5. Click "Save".
6. Once the repository is published, the page will be refreshed and the website's live link will be displayed under the "GitHub Pages" section.

The live link to the deployed site can be found here: [https://croftsdeveloper.github.io/track-it/](https://croftsdeveloper.github.io/track-it/)

### Forking the GitHub Repository

If you wish to contribute to this project, you can fork the repository. This means you'll have a copy of the repository in your GitHub account which can be edited without affecting the original project. Here's how you can fork the repository:

1. Log in to GitHub and navigate to the repository [https://github.com/CroftsDeveloper/track-it](https://github.com/CroftsDeveloper/track-it).
2. In the top-right corner of the page, click the "Fork" button.

### Cloning the GitHub Repository

If you wish to work on this project locally, you can clone the repository. Here's how:

1. Navigate to the desired location on your computer where you want to host the cloned repository.
2. Open your terminal or command prompt.
3. Type `git clone https://github.com/CroftsDeveloper/track-it.git` and press "Enter".
4. The project will be cloned to your local machine.

Ensure that you navigate into the correct directory by entering `cd track-it` before you start editing or view the files!

### Credits

#### Inspiration

- While no code was directly taken, insights and techniques discussed in [this YouTube video](https://www.youtube.com/watch?v=GrFnS7YUdiU&t=94s&ab_channel=AKBARIT) by AKBAR IT were a valuable resource and provided inspiration for some layout aspects of the project

#### Code

- **HTML**: The foundational structure of the website was built using vanilla HTML5. Several techniques and best practices were reviewed at [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML).

- **CSS**: Styling for the website was achieved using CSS. Inspiration for some CSS properties and responsive design patterns were taken from [CSS-Tricks](https://css-tricks.com/).

- **JavaScript**: The primary scripting language used to implement functionalities. Resources like [JavaScript.info](https://javascript.info/) and [Stack Overflow](https://stackoverflow.com/) helped me get a visual on problem solving, especially at the later stages.

### Favicon

- I have downloaded and implemented a free Favicon from [favicon.io](https://favicon.io/emoji-favicons/money-bag)
