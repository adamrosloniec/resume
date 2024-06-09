# My Resume/CV App

This is a simple Resume/CV application built with pure JavaScript and Tailwind CSS. It fetches data from various endpoints and displays it on the web page. Timeouts are used to simulate loading spinners. This project is for fun and to practice pure JavaScript. It reflects my experience, skills, and personal details.

## Technologies Used

- **Pure JavaScript**: Used for fetching data from endpoints and updating the DOM.
- **Tailwind CSS**: Used for styling the application.
- **JSON**: Data format used for the endpoints.

## Features

- **Avatar**: Displays the user's avatar image.
- **Name**: Fetches and displays the user's name.
- **Role**: Fetches and displays the user's role.
- **Skills**: Fetches and displays a list of the user's skills.
- **About**: Fetches and displays a brief about section.
- **Interests**: Fetches and displays a list of the user's interests.
- **Experience**: Fetches and displays the user's work experience.
- **Education**: Fetches and displays the user's education history.
- **Social Links**: Fetches and displays links to the user's social profiles (LinkedIn, GitHub).

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/adamrosloniec/readme.git
   ```

2. Open `index.html` in your preferred web browser.

## Code Explanation

The main script file fetches data from various JSON endpoints and updates the HTML content accordingly. Below is a brief overview of the main parts of the code:

### Fetching Data

The `getData` function is a helper function to fetch data from an endpoint and update the DOM with the fetched data. It takes three parameters:
- `url`: The URL of the JSON endpoint.
- `updateFn`: The function to update the DOM with the fetched data.
- `delay` (optional): A delay to simulate loading time.

### Updating DOM Elements

Several functions handle updating different parts of the DOM with the fetched data:
- `getAvatar()`: Updates the avatar image.
- `getInterests(data)`: Updates the interests list.
- `getSocial(data)`: Updates the social links.
- `getExperience(data)`: Updates the experience list.
- `getEdu(data)`: Updates the education list.
- `getName(data)`: Updates the name.
- `getRole(data)`: Updates the role.
- `getAbout(data)`: Updates the about section.
- `getSkills(data)`: Updates the skills list.

### Displaying Content

The `showContent` function is called when the page is fully loaded. It hides the loading spinner and displays the main content. It also initiates data fetching for all sections.

### Timeouts

Timeouts are used to simulate loading delays for different sections of the page, creating a fake-loading spinner effect for demonstration purposes.

## License

This project is open source and available under the [MIT License](LICENSE).
```
