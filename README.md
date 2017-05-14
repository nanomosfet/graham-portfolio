# Graham Portfolio

This is a Music Artist's portfolio.

## How to make edits to the site

1. Install (Google SDK for Python 2.7)[https://cloud.google.com/appengine/docs/standard/python/download]
2. Install git
3. Clone the repository - `git clone https://github.com/nanomosfet/graham-portfolio.git`
4. The HTML files are in templates directory
5. Edit to your liking 
6. Run server on your local machine - to check if changes are good `dev_appserver.py app.yaml`
6. After your edits make sure to push the changes to the repository (note: Make sure to check with me to get permission to upload stuff)

In your repository directory:
```
git add ./*
git commit -m "Your change notes"
git push
```
7. Now upload the changed code to the google cloud - `gcloud app deploy`