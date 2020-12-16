Only front end not back endFrontend

In your frontend folder you will need to build out your React app to include routing between a home (/) route to upload an image and a /photos route to display all images. You will also be required to use a component library of your choosing (ex. React Bootstrap (Links to an external site.) or Material UI (Links to an external site.)).

User should be able to navigate between the Home (/) and Photos (/photos) routes from either webpage.
On the / route there should be a form that allows users to upload a file:
This form should only accept a file type of images.
This form should POST to your server when the upload button is clicked.
On the /photos route you should be displaying all of your images in a gallery format:
Images should be rendered based on details coming from a GET request to your server that should respond with all photos.
Images should all be the same width and height
If an image is clicked webpage should display a Modal component that displays a Card component (see Components tab in your component library docs).
Card component should display the image as well as the image's filesize as a title.
Image and title should be coming from a GET request to your server that should respond with ONE photo

//React Single File Upload Tutorial with Node, Express and Multer
