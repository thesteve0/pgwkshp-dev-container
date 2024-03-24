I think the next steps are
1. Replace the docker build from the Dockerfile with just pulling an image I publish somewhere
2. Once I have this finished I think I can place the .devcontainer directory in any code project and it should start the devcontainer with the code already there. 
3. Not sure if I should download the data before I make the image or after.  Seems like the download speeds are really fast so, I think putting it into a postStartupCommand (or whatever is is called will be fine)