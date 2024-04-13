# home-page
This website implements a custom new tab page where users can add their favorite websites for quick access. The main features include:

Add Site Functionality: By clicking on the "Add a Site" section, users can input the URL and name of a website, then confirm to add it to the page. Once added, the website will be displayed on the page, including its icon and name.

Remove Site Functionality: Each added website comes with a delete button (a small cross). Users can click this button to remove the corresponding website from the page.

Local Storage of Website Information: Using the browser's localStorage object, the website saves the information (URL and name) of the added websites locally. This ensures that the added websites will still be displayed on the page when the user reopens it.

Export and Import Functionality: Users can export the current saved custom website information as a JSON file. They can also import a JSON file from their local storage to restore their custom website information. This allows users to easily backup and restore their website information.

Retrieve Website Icons Functionality: Website icons are retrieved from Google's favicon service. When a user adds a new website, its icon is automatically fetched and displayed on the page. The icon is also cached locally to improve loading speed.


![test](https://github.com/MemeCats/home-page/assets/166717240/df711ba9-0da4-42fb-9f3f-01e4e2596a70)
