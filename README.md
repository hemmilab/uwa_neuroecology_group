# hemmi_lab
hemmi lab website
To use the gh-pages actions, remove the the jekyll.yml file. You may have to switch back to the master branch as well

# Background
This site is implemented using Jekyll and Ruby, which dynamically links and arranges pages in a modular way to minimize maintenance time, but the file structure can be confusing.

New items for people, projects etc. are called 'posts'.

# Adding new posts
1. Go into the _posts folder and find the folder for the category you want to add it to (e.g. staff or students).
NOTE: the folder in the base directory is NOT the correct one. These only contain information for the parent page (index.md) that will display the posts in a grid.

2. Duplicate an existing post in that folder, or duplicate one from another folder.

3. The name of the file must be in the format YYYY-MM-DD-[title].md where title is the name of the post (e.g. a person's name) and YYYY-MM-DD is the date you want the post to be visible. Usually you want this to be the current day, or in the past, but you can set a future date if you only want something to be visible in the future.

4. Set the category of the post to the correct one. This will be either staff, researchers, research, phd-students or phd-alumni.

5. Update the content. Note that for images the source (src) must be in the format: {{site.baseurl}}/images/[folder]/[filename].[extension]
   Images will not display correctly in the Preview for your .md page, but will show correctly on the site.

6. To confirm you have set it up correctly, navigate to the base directory on github and refresh until the brown circle beside your commit turns into a green tick (usually take a few minutes). Then go to the website and force-refresh the page to renew the cache. In firefox, edge and chrome this is done using Ctrl+shift+R.
