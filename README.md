# ASE220-pets-shelter

A front-end application aimed at efficiently managing the pets in a pet shelter.

### Team Members:

- Khanh Nguyen
- Bhuwan Bhandari
- Rajani Khatri

### Contributions:

- Khanh Nguyen: Fetched data from data.json and implemented modal for the index page
- Bhuwan Bhandari: Implemented pagination for the index page
- Rajani Khatri: Created data.json and implemented pagination for the index page

### Project Structure:

The project has been restructured with two folders: assets and pages.

- assets: Contains images and data.json.
- pages: Contains index.html and detail.html.

 index.html:
  + Displays 30 pet cards.
  + Utilizes JavaScript to dynamically generate cards based on data from data.json.
  + Each card triggers a modal when clicked, displaying more details about the pet.
  + The modal includes a button to navigate to the pet's detail page.
  + Implements pagination for the index page.
    
detail.html:
  + Presents detailed information about each pet.
  + Retrieves and displays data based on the unique parameters from the link in the index page.
  + Fetches data from data.json.
    
data.json:
  + Contains an array of 30 pet objects.
