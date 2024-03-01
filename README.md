Task

1. Implement Stores api
   http://localhost:3001/stores?\_page={page_no}&\_per_page={per_page}&\_sort={key/-key}

Query Parameters
\_page: The page number of the results to fetch.

Type: Integer
Description: Specifies the page of results to return.
Required: No
Default: 1
\_per_page: The number of items per page.

Type: Integer
Description: Limits the number of items returned in one request, allowing for pagination.
Required: No
Default: 10
\_sort: The key to sort the results by.

Type: String
Description: Determines the sorting order of the results based on the specified field. Prepend with - for descending order.
Required: No
Examples:
name: Sorts the stores by name in ascending order.
-name: Sorts the stores by name in descending order.

Reference web page => https://lbp8.enactweb.com/all-stores

Task Objectives:

1. Develop a user interface (UI) to showcase categories and a comprehensive list of stores, featuring Logo, Name, Cashback, and Link.

2. Fetch data seamlessly from the API and render it on the frontend for both categories and individual stores.

3. Implement sorting options for stores based on API parameters like Alpha, Popularity, and Cashback.

   -http://localhost:3001/stores?\_sort=name.en

4. Integrate category filtering functionality for stores based on API parameters.

5. Enable an efficient search feature, facilitating users in locating specific stores effortlessly.

6. Implement specific filters for different store attributes:

   - "Claimable" stores: http://localhost:3001/stores?is_claimable=1
   - "Cashback Enabled" stores: http://localhost:3001/stores?cashback_enabled=1
   - "Sharable Stores": http://localhost:3001/stores?is_shareable=1
   - "Featured Stores": http://localhost:3001/stores?is_featured=1
   - "Promoted Stores": http://localhost:3001/stores?is_promoted=1

7. Allow users to apply multiple filters simultaneously.

8. Integrate an Infinite Scroll feature, dynamically loading additional stores as users scroll through the interface.

9. Enable users to mark favorite stores, with this information stored in local storage and automatically displayed upon page reload.

10. Persist user-selected filters and sorting preferences in the URL parameters. This ensures that reloading the page or sharing the URL reproduces the same set of stores based on the user's previous interactions.

Deliverables:

1. Provide well-documented code, elucidating the application's logic, structure, and usage.

2. Share a public GitHub repository housing the project code, accompanied by a detailed README file guiding users through the setup and usage of the application.

3. Create a recorded tutorial or demo, potentially utilizing tools like Bubble, to effectively explain how users can navigate and utilize the application's features.

Reference :

- Repo : https://github.com/nishu-murmu/interview-template-app

- Recorded Bubble : https://app.usebubbles.com/jkpsVoLyTFRQ7ZbKhywze1

- All Store Page : https://laraback.enactweb.com/all-stores

<!-- Final -->

# React Store Showcase App

## Introduction

Welcome to the React Store Showcase App project! In this practical exercise, you will be creating a React application that showcases different store categories along with a detailed list of individual stores. The app aims to provide a user-friendly interface with features like sorting, filtering, searching, and user preferences.

## Task Objectives

1. **User Interface (UI) Development:**

   - Develop a UI to showcase categories and a comprehensive list of stores, featuring Logo, Name, Cashback, and Link.

2. **Data Fetching and Rendering:**

   - Fetch data seamlessly from the API and render it on the frontend for both categories and individual stores.

   Categories : http://localhost:3001/categories
   Stores : http://localhost:3001/stores

3. **Sorting Options:**

   - Implement sorting options for stores based on API parameters like Alpha, Popularity, and Cashback.
     - Sorting example: `http://localhost:3001/stores?_sort=name.en`

4. **Category Filtering:**

   - Integrate category filtering functionality for stores based on API parameters.

   Ref : http://localhost:3001/stores?cats=16

5. **Efficient Search Feature:**

   - Enable an efficient search feature, facilitating users in locating specific stores effortlessly.

6. **Specific Filters for Store Attributes:**

   - Implement specific filters for different store attributes, including "Claimable Stores," "Cashback Enabled Stores," "Sharable Stores," "Featured Stores," and "Promoted Stores."

     - "Claimable Stores": http://localhost:3001/stores?is_claimable=1
     - "Cashback Enabled Stores": http://localhost:3001/stores?cashback_enabled=1
     - "Sharable Stores": http://localhost:3001/stores?is_shareable=1
     - "Featured Stores": http://localhost:3001/stores?is_featured=1
     - "Promoted Stores": http://localhost:3001/stores?is_promoted=1

7. **Multiple Filters:**

   - Allow users to apply multiple filters simultaneously.

   - Ref : http://localhost:3001/stores?\_page=1&\_per_page=5?is_claimable=1

8. **Infinite Scroll:**

   - Integrate an Infinite Scroll feature, dynamically loading additional stores as users scroll through the interface.

   - Ref : http://localhost:3001/stores?\_page=1&\_per_page=25

9. **Favorite Stores:**

   - Enable users to mark favorite stores, with this information stored in local storage and automatically displayed upon page reload.

10. **URL Parameter Persistence:**
    - Persist user-selected filters and sorting preferences in the URL parameters to reproduce the same set of stores based on the user's previous interactions.

## Deliverables

1. **Well-Documented Code:**

   - Provide well-documented code, elucidating the application's logic, structure, and usage.

2. **GitHub Repository:**

   - Share a public GitHub repository housing the project code, accompanied by a detailed README file guiding users through the setup and usage of the application.
     - [GitHub Repository Reference](https://github.com/nishu-murmu/interview-template-app)

3. **Recorded Tutorial or Demo:**

   - Create a recorded tutorial or demo, potentially utilizing tools like Bubble, to effectively explain how users can navigate and utilize the application's features.
     - [Recorded Bubble Tutorial](https://app.usebubbles.com/jkpsVoLyTFRQ7ZbKhywze1)

4. **Application Reference:**
   - Explore the [All Store Page](https://laraback.enactweb.com/all-stores) for reference.

Feel free to reach out if you have any questions. Good luck, and happy coding!
