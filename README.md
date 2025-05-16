# Information
* Generating html files
- Source environment ( virtual environment using pip) 
   - source ...github.io/env/bin/activate
       - using requirements.txt to create environment  
- Run the following command in ...github.io/docs directory
    - make html
- An error occurs where links don't map correctly after file generation. Within directory docs/build/html/, do the following prior to pushing (i.e. deploying). 
    - rename directory _static to static.
    - rename directory _images to images. 
    - in all .html files rename strings '_static', '_images' to 'static', 'images', respectively.
    - push updated changes to repo (i.e. redeploy hmtl page)
