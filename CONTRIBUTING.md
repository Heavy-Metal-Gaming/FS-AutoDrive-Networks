# How to Contribute
For this repository.  
Create a branch.  
Make the needed changes in that branch.  
Create pull request against this repository's master branch.  
Follow (Using the Fork and Pull model):  
- [GitHub Documentation Collaborative Development](https://docs.github.com/en/github/collaborating-with-pull-requests/getting-started/about-collaborative-development-models)
- [GitFlow Document](https://guides.github.com/introduction/flow/)
Don't forget to edit the main readme and add your information to the Contributors section.  

# Requirements
Network file: AutoDrive_config.xml  
Network README.md file created from the README-TEMPLATE.md file.  
Placed in a folder named for the official name of the map under the folder for whichever version of Farming Simulator the map belongs to.

## Optional Extras
Translations, with filename properly formatted using the 2 character country code. Example: AutoDrive_config_de.xml  
Visual Map of the network created in AutoDrive Course Editor.

### Extracting Network Destinations
This regex can be used in Notepad++ on the AutoDrive_config.xml file. If you open the file, and use the Replace dialog.  
Find what: ```<mm.+?>\n.+?\n.+?<name>(.+?)</name>\n.+?\n.+?</mm.+?>```  
Replace with: ```\1```  
This regex is actually from J.T. Sage's FS19 AutoDrive repo, and reproduced here without his permission. All credit belongs to him.
