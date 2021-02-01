## Initializing a Katacoda Scenario

We can now initialize an empty Katacoda tutorial by using the Katacoda-CLI.

`katacoda scenarios:create`{{execute}}

You will be prompted a few questions about the scenario properties like name and description. 

1. Friendly url: This will be in the url of your scenario. It'll look something like `https://katacoda.com/YOUR_KATACODA_USERNAME/YOUR_FRIENDLY_SCENARIO_URL`. You'll have to specify the last section of this URL, being `YOUR_FRIENDLY_SCENARIO_URL`.
2. Scenario Title: The title for your scenario.
3. Scenario Description: A description for your scenario, can only be 100 characters long.
4. Difficulty Level: Specify if this course is for Beginner, Intermediate or Advanced users.
5. Estimated time: Estimate how much time it will take the user to work through the scenario.
6. Number of Steps: The number of total steps in the scenario. As an example, you're currently at step 4 in this tutorial.
7. Image: Choose an image that will run as a backend service for your scenario. For example, this scenario you're currently working through uses `nodejs:12`. This image was chosen because Node.js is required to install the Katacoda-CLI. Of course, we could've gone with a basic Ubuntu image, but this would mean extra steps like installing Node.js. Choose the image that suits your needs the best.
8. Layout: This is the layout that will be presented to the user on the right hand side. This scenario uses a Terminal-only, but you could also go with things like Editors, if you would like the user to edit files.

Finally, the scenario was created in your current directory. You can see it with the command `ls`{{execute}}. You should be able to see a new directory that was just created, which contains the scenario files. `cd` into this fresh folder.