# REVELIA – Event Management Website

**Discover. Connect. Experience.**

REVELIA is a responsive event discovery and management website developed using **HTML5, CSS3 and Vanilla JavaScript**. It provides users with an interactive platform to explore upcoming events, access event information, and register for events of their choice.

The platform combines an intuitive event discovery experience with a dedicated member profile section, allowing users to manage their personal information and keep track of their event registrations.

The project focuses on responsive design, interactive functionality, client-side form validation and browser-based data management.

---

## 1. Project Overview

The objective of REVELIA is to develop a modern and user-friendly event management platform that simplifies the process of discovering and registering for events.

Users can browse available events, search and filter listings, view detailed event information, and complete registrations through an interactive registration form. The platform also includes a profile management section where users can access and update their personal information and view their registered events.

The website is designed to provide a consistent experience across desktop, tablet and mobile devices.

## 2. Key Features

### Event Discovery and Exploration
- Dynamic event listings displayed through individual event cards.
- Featured events and an introductory hero section.
- Event information including title, date, venue, description and entry fee.
- Dedicated event details modal with additional information.
- Event countdown timer.

### Search and Category Filtering
- Search functionality across event names, categories, venues and descriptions.
- Category-based filtering for:
  - Technology
  - Music
  - Art & Design
  - Wellness
  - Learning
- Ability to browse all available events.

### Event Registration
- Interactive registration form for event participation.
- Collection of essential participant information, including name, email address and phone number.
- Event selection and consent validation.
- JavaScript-based form validation.
- Registration confirmation with a uniquely generated reference number.

### Member Profile Management
- Dedicated profile section for registered participants.
- Profile lookup using the registered email address.
- Display of personal information, including:
  - Full name
  - Email address
  - Phone number
  - Profile information
- Ability to edit and save profile details.
- Registered Events section displaying the events associated with the participant.
- Event information including event name, date, venue, registration reference and status.
- Automatic profile creation following successful registration.

### User Interface and Experience
- Responsive layouts for desktop, tablet and mobile devices.
- Consistent REVELIA branding and visual identity.
- Light and dark theme support.
- Smooth transitions and interactive interface elements.
- Accessible form labels and keyboard-based modal dismissal.
- Reduced-motion support.

### Browser-Based Data Management
- Local Storage-based registration management.
- Persistent user profile information.
- Saved events and theme preferences.
- Automatic migration of supported data from the previous K Explore version.

## 3. Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic website structure and content |
| CSS3 | Styling, responsive layouts, animations and themes |
| JavaScript (ES6+) | Event rendering, search, filtering, validation and interactive functionality |
| Browser Local Storage | Persistent storage of registrations, profiles, saved events and preferences |
| Git & GitHub | Version control and project management |

The project uses vanilla JavaScript without requiring a frontend framework or backend server.

## 4. Project Structure

```text
revelia-event-management-website/
│
├── index.html
│   └── Main website structure and interface
│
├── style.css
│   └── Styling, responsive design and theme configurations
│
├── script.js
│   └── Event management, registration,
│       profile functionality and interactions
│
└── README.md
    └── Project documentation
```

## 5. Application Workflow

The primary user journey follows these steps:

1. **Explore Events:** Users visit the homepage and browse the available events.
2. **Discover Events:** Users search for specific events or filter them by category.
3. **View Details:** Selecting an event opens a detailed view containing relevant information.
4. **Register:** Users complete the registration form and submit their details.
5. **Receive Confirmation:** The website validates the information and displays a registration confirmation with a reference number.
6. **Access Profile:** Users visit the profile section to retrieve their information using their registered email address.
7. **Manage Information:** Users can edit their profile details and view their registered events.

## 6. Profile and Registration Data Management

REVELIA currently uses the browser's Local Storage API to maintain registration and profile information.

Following a successful registration:
- A registration record is saved in the browser.
- A corresponding participant profile is created or updated.
- The latest registered email is used for profile access within the current browser.
- Registered events are associated with the participant's email address.

Users can retrieve their profiles using the email address provided during registration.

Profile updates are reflected in the stored profile information. When a participant changes their email address, the associated registration records in the same browser are updated accordingly.

The application also supports migration of existing K Explore Local Storage data to the corresponding REVELIA storage keys.

**Technical limitation:** The current implementation is a frontend-only demonstration. It does not include server-side authentication, a backend API or a centralized database. Consequently, stored information is limited to the browser and device in which it was created. Local Storage should not be considered secure storage for private user information.

A production-ready implementation would require a backend service, secure authentication, database integration and appropriate access controls.

## 7. Installation and Local Setup

Follow these steps to run REVELIA locally.

**Prerequisites**
- A modern web browser.
- Visual Studio Code or another code editor.
- Git (optional, for repository management).

**Setup Instructions**

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd revelia-event-management-website
```

3. Open the project in Visual Studio Code.

4. Open `index.html` directly in a browser or use the Live Server extension for a local development environment.

5. Explore the website and test its available functionality.

No additional package installation or build process is required.

## 8. Deployment

REVELIA can be deployed using static website hosting platforms such as GitHub Pages, Netlify or Vercel.

### GitHub Pages Deployment

1. Create a public GitHub repository.
2. Upload the project files to the repository's root directory.
3. Navigate to **Settings → Pages**.
4. Select **Deploy from a branch** under Build and Deployment.
5. Choose the `main` branch and `/ (root)` directory.
6. Save the configuration.
7. Wait for the deployment process to complete.

The deployed website will be accessible through:

```text
https://<username>.github.io/<repository-name>/
```

Alternatively, the project can be deployed through Netlify or Vercel by importing the GitHub repository.

## 9. Testing and Validation

The following functionality should be verified before deployment:

- [ ] Homepage and event listings load correctly.
- [ ] Event search returns relevant results.
- [ ] Category filters work correctly.
- [ ] Event details modal displays the correct information.
- [ ] Countdown timer displays the event timing.
- [ ] Registration form validates participant information.
- [ ] Invalid email addresses and phone numbers are rejected.
- [ ] Successful registrations generate confirmation references.
- [ ] Participant profiles are created after registration.
- [ ] Profile lookup retrieves the correct participant information.
- [ ] Profile details can be edited and saved.
- [ ] Registered events display the correct event information and status.
- [ ] Registration and profile information persist after refreshing the page.
- [ ] Light and dark themes function correctly.
- [ ] Responsive layouts work across different screen sizes.
- [ ] Existing data migration works in the same browser.
- [ ] The deployed website functions correctly.

## 10. Customization and Future Enhancements

The project can be extended with additional functionality to improve its capabilities:

- Backend integration for centralized registration management.
- Secure user authentication and authorization.
- Database integration for persistent user and event records.
- Administrative dashboard for creating and managing events.
- Event capacity and availability management.
- Email-based registration confirmations.
- Registration cancellation and management.
- Improved profile management and account settings.
- Real-time event updates.

## 11. Project Information

**Project Name:** REVELIA – Event Management Website

**Project Category:** Web Development / Event Management

**Development Type:** Frontend Web Application

**Technologies:** HTML5, CSS3 and Vanilla JavaScript

**Deployment:** GitHub Pages / Netlify / Vercel

**Project Purpose:** Academic Web Designing Project

---

*REVELIA aims to make discovering and participating in events a simple, accessible and engaging experience.*