ilovepharmacology app - Play Store package
1. Create a free GitHub account, make a public repository (e.g. ilovepharmacology-app), upload ALL files in this folder.
2. Repository Settings > Pages > Deploy from branch "main" > Save. Your site: https://<username>.github.io/ilovepharmacology-app/
3. Open the site on your phone to check it works.
4. Go to https://www.pwabuilder.com, paste the site URL, click Package for stores > Android > Download.
5. Upload the .aab file to Google Play Console (closed testing track first). Keep the signing key file PWABuilder gives you safe - you need it for every update.
6. Put the assetlinks.json file from PWABuilder in a folder named .well-known in the repository (removes the browser bar in the app).
To add content: edit the POTD, MCQS, DOC and VIDEOS lists near the bottom of index.html.
