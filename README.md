This project is made to find products suitable to your needs. To find the product you require (software or physical) put your requirement in the input field and press submit and just wait. 
You will get the info you require.
 
The frontend has been created using vite and backend using express, javascript, nodeJS, and openAIs API. 
To run the application just go into the main directory and run "docker compose up". This will spin up 3 containers containing the db, backend and the frontend.
Then you can start using the application.

Once you enter the application, you can type anything to search in the input field and click the submit button. The only limitation here is that for the icon to be generated beside the product,
only 5 requests can be sent in a minute as we are operating on the free tier of openAIs API. Post 5 requests in a minute, icon is not generated but the text giving info on the product will get generated. 
We have made use of DALL-E 2 model for image generation and gpt-turbo-3.5 for text generation. 
