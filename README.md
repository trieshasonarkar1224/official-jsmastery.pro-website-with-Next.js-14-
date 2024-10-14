# official-jsmastery.pro-website-with-Next.js-14-



<ar>

<a href = "https://www.youtube.com/watch?v=3WCIyNOrzwM"> Link To Tutorial </a>
<ar>

Date:-14/10/2024 
<ar>

Enlisted below are the things I learnt today. 👇
<ar>


✮ Navbar :-
<br>
  Creating and styling the Navbar component.
  <br>
  Semantic HTML structure is used for the Navbar, and Tailwind CSS classes are applied for styling.
<br>
  Adding a logo and a hamburger menu for mobile responsiveness, with proper styling and import statements.
<br>
  Creating navigation links for the Navbar and applying appropriate styles for a consistent look.
<br>
  Ensuring the Navbar links are functional and styled as per the design requirements.
<br>

✮ Footer 
<br>
  Implementing the Footer component.
<br>
  Using semantic HTML elements to create the Footer with copyright text and links to terms and conditions and privacy policy.
<br>
  Applying styles to ensure the Footer is visible and correctly positioned at the bottom of the page.
<br>
  Adjusting general styles to ensure the Footer appears correctly and is responsive.
<br>
  Finalizing the Footer component and moving on to the main content section.
<br>

✮ Home Page
<br>
  Building the Home Page component.
<br>
  Creating a main section with semantic tags and setting up the layout for the home page.
<br>
  Styling the Banner section with appropriate classes and background images.
<Br>
  Creating the Search Form component and importing it into the Home Page.
<br>
  Preparing to add Filters and resources rendering to the Home Page.
<br>

✮ Search Form
<br>
  Search Form
  The creator builds a form component, including a label with a search icon and an input field. They discuss using Shad CN components and Tailwind for styling.
<br>
  Additional styling is applied to the input field, including padding and placeholder text. The creator emphasizes client-side rendering for handling state changes and events.
<Br>
  They integrate useState from React to manage the search state and handle input events. The form is marked as a client-side component to facilitate state management.
<br>
  The search form's UI is complete, but the logic and server-side data fetching will be implemented later after setting up filters.
<br>

✮ Filters
<br>

  The creator starts by defining an unordered list for the filter links and maps over an array of predefined categories like front end, back end, and full stack.
<br>
  They implement buttons for each filter category, ensuring each button has a key and an onClick handler. The component is converted to a client-side component for interactivity.
<br>
  Styling is applied to both the unordered list and individual buttons, making them more visible and providing feedback on which filter is currently active.
<br>
  The creator demonstrates how to dynamically update the filter state and visually indicate the active filter, preparing for backend data fetching.
<br>

✮ Sanity 
<br>

  Sanity CLI is installed and configured. The creator logs in and sets up a new project named JSM resources, choosing TypeScript and Next.js app directory.
<br>
  Schemas for resources and resource playlists are created, defining fields such as title, slug, download link, views, poster, and category.
<br>
  The schemas are exported and imported into the Sanity configuration file. The creator shows how to access the Sanity Studio to manage content.
<br>
  Sanity Studio is tested by creating and publishing a new resource document. The studio is integrated within the local host, making content management efficient.
<br>

✮ Resource Card
<br>
  The home page fetches resources using the getResources action and displays them in a loop. A new component called ResourceCard is created to render individual resource items.
  <br>
  The ResourceCard component accepts props such as ID, title, image, download number, and slug. Shad CN card components are used for styling.
  <br>
  The card content is styled and wrapped within a Next.js link component. Images are fetched from Sanity's CDN, and the card displays download information and a 'Download Now' button.
<br>
  The creator tests the ResourceCard by adding a new resource in Sanity Studio and reloading the page. They ensure that the new resource is displayed correctly and handle caching issues.
<br>

✮ Header and Filtering
<br>
  Fixing the navigation bar and header issues.
  <br>
  The navigation bar overlaps the content and needs a background color adjustment. The header will be dynamic and show different content based on user actions.
<br>
  The header will support advanced searching and filtering, showing results dynamically. New Header component creation is discussed.
<br>
  Implementation steps for the new Header component are outlined, including its properties and dynamic behavior.
<br>

✮ Search Functionality
<br>
  Refining the search functionality with debouncing and URL updates.
  <br>
  Implementing debouncing for search input to optimize performance. The search results are updated based on user input.
  <br>
  Using debouncing to delay search requests and prevent excessive API calls.
  <br>
  Updating the search results by modifying the URL and handling empty search cases.
  <br>
  Ensuring the query parameter is removed when the search input is cleared.
<br>

✮ Resource Playlist
<br>
  Adding and displaying resource playlists.
<br>
  Creating a function to fetch resource playlists and displaying them on the homepage.
<br>
  Creating and managing resource playlists in the Sanity CMS.
<br>
  Mapping and displaying resource playlists on the homepage.
<br>
  Ensuring playlists are displayed correctly even when search filters are applied.
<br>

✮ Deployment
<br>
  Deploying the application using Vercel.
  <br>
  Steps to deploy the Next.js application using Vercel, including setting up environment variables.
  <br>
  Addressing potential build errors during deployment and ensuring successful deployment.
<br>

✮ Build Error Fix
<br>
  Fixing build errors and completing deployment.
<br>
  Identifying and fixing TypeScript errors to ensure a successful build.
<br>
  Making necessary adjustments to schema definitions and redeploying the application.
 <br>


✮ Further Improvements Loading:-
<br>
  Further improvements and SEO enhancements.
  <br>
  Fixing loading skeleton colors and improving SEO metadata for better search engine ranking.
<br>
  Adding metadata for social media sharing and mobile themes to enhance user experience.
<br>
  Verifying the improvements and checking website performance using tools like GTMetrix.

<br>

![Screenshot 2024-10-14 204510](https://github.com/user-attachments/assets/f787db87-3f70-4268-a91a-6e388e44431e)

![Screenshot 2024-10-14 204524](https://github.com/user-attachments/assets/0fa99e42-5eea-4647-a7ad-bd9808fe6f2b)

![Screenshot 2024-10-14 204536](https://github.com/user-attachments/assets/67f54348-d793-4a2e-9aa8-f33ba8ea49ae)

![Screenshot 2024-10-14 204557](https://github.com/user-attachments/assets/cb434b7a-ad2b-4d06-8900-523d2dbbf0b4)

![Screenshot 2024-10-14 204611](https://github.com/user-attachments/assets/f8494307-dc21-4fbb-8064-6036d1a78ec3)




  
