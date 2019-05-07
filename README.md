# Promote Gallery Exam

This app consists of a simple input at the top and an image gallery below it.
Once you type into the input, you get the relevant flicker image at the bottom.

## Getting Started
To set up the test environment and get this app running locally all you need to do is:
1. Make sure you have a [Gitlab](https://gitlab.org) account
2. [Import this repository](https://docs.gitlab.com/ee/user/project/import/repo_by_url.html) to your Gitlab account as a private repository. Use this as the import URL: https://github.com/wix-incubator/promote-gallery-exam

3. Clone your newly created repository
4. In the created folder install the node modules `npm install`
5. Run the app `npm start`
6. Your local app should be available at `http://localhost:8000`

## Your Tasks
This project includes 2 main tasks - Image Actions and Gallery Actions. You can, and should, learn new skills during the process. You may consult with Google or your friends, but you will need to explain the choices you made, so be responsible for your code.

*Important*: Please make sure to commit after each task. For example, after finishing task 1 ‘Filter’, commit the files with a relevant message such as “task 1 - filter image” and so on.

### Task 1 - Image Actions
Each image has three buttons that appear on mouse hover. You need to make them work.
1. Filter: each click should set a random filter on the image (choose between 5 CSS filters).
2. Clone: clicking the clone button should duplicate the image.
3. Expand: clicking an image should display this image in a larger view.

### Task 2 - Gallery Actions
1. Responsive:  the gallery adjusts the size of each image so that all the images will fit into the screen without margin. However, when the window is resized, the images are not fitted so well. Make sure the images are always adjusted to the window width.
2. Delay: Current implementation will fire an api call for each character you type. It causes a lot of redundant api calls. Change it so an api call will be fired only 500ms after no typing was done.
3. Infinite Scroll: currently the gallery displays only 100 images. *Create* a mechanism that loads more images from flickr when the user is scrolling past the last image.

### Bonus #1
Filter: There’s an option to get info on an image from flickr. This info contains title and description.
Create the ability to filter the existing images by text contained inside the title or description.

### Bonus #2
Images: When the user loads many images, the browser can become slow and sometime stuck altogether.
How would you solve this?

## Tips / Notes
- All the code you'll change / add will be in the `/src/components` folder.
- You can view a working example of the gallery here: https://youtu.be/_0OxprjOhk4

- The infinite scroll mechanism should not be imported via NPM. *You should do it yourself.*
- If you want to use `npm` modules for other parts, your choice - just make sure you know how they work under the hood.
- Be creative! Think of the product - how can you make it better? What is missing that can make the experience great? Add your own features and polish it until you're happy with it.

#### Remember: this test is designed to see how you complete tasks that require self learning, not to test your existing knowledge.

## Submitting your project
After you've completed your tasks, and you are ready to submit it, do the following:
1. Make sure all the code is committed and pushed
2. Add "promote-fed-exam@wix.com" as a user to the repo (Master permission)
3. Send us an email to promote-fed-exam@wix.com with your repo link

## Good Luck!
![Break a leg](https://media0.giphy.com/media/aHs1EAnUAxYgU/giphy.gif)


