# angular-notes
##### Memo
- First, you should type `docker-compose build`.
- Second, you should start project, So type command `docker run -it --rm -w /app -v $(pwd):/app angular:latest ng new notes` \*notes is project name.
 - Would you like to add Angular routing? -> `Y`
 - Which stylesheet format would you like to use? -> We can select style
 - Would you like to share anonymous usage data with the Angular Team at Google under Google’s Privacy Policy at https://policies.google.com/privacy? -> If you want to use analytics, you should type `Y`.
- Third, you must change yml's volumes to project name.
- Last, should type `docker-compose up -d`.
