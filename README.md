#The project name is "THE DICTIONARY" and it is an English dictionary app : Access it via this link : www.estherglobaltech.tech

#This fully functional project has been built using HTML CSS and JavaScript, with an integrated english dictionary free API. It has been built along with different Youtube videos explaining some concepts on implementing APIs in an app, and also building a dictionary using HTML, CSS and JavaScript

This dictionary essentially allows the users to have access to a simple, reliable, and user-friendly app to extend their understanding of English words, and hence expanding their vocabulary. It is useful as it serves in educational purposes.

References :

API: from https://dictionaryapi.dev/, Free to use
Background image : By Pixabay, free to use, from the website Pexels
Helpful videos to build similar project : Leon Noel, https://www.youtube.com/watch?v=WcSTeotmJtw ; ProgrammingWithHarry, https://www.youtube.com/watch?v=S5uLkxNUk-M

Improvements :

Implement the audio function to allow the user get the pronounciation of the word

Watch this video to better understand how this app works : https://youtu.be/jQlfusyeH2U

For the Deployement :

To deploy the app on the different servers :

1. Firslty make sure that the ssl certificates are there, so that the domain is secure

2. Clone the repository that contains the application files on the terminal, and navigate into it using the git clone [https://github.com/estheredi0406/The-dictionary_Summative.git]

3. Use sftp command to connect to the server and move the files into the server stfp ubuntu@

4. ls into the server to make sure the files are there. And Rename the Html file (in my case, it was necessary because the name of my file was not index.html)
   mv dico.html index.html

5. Now we have to upade the Nginx Configuration to point to the directory using the comand root /var/www/esther;
6. We ahve to restart Nginx using sudo service ngnix retart
7. Testind the deployment by checking the app locally curl localhost, this shoud output our app html file
8. Verify if the URLs point to the app : www.estherglobaltech.tech; http://web-01.estherglobaltech.tech, http://web-02.estherglobaltech.tech
