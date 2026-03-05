                                =======================     INSTRUCTION       =======================

                                                            For LINUX

                                            # Seneca Engineering Society Website

                            This repository contains the official website of the Seneca Engineering Society.
  
                    The website is built using **Hugo** with the **Blowfish theme** and deployed using **GitHub Pages**.

                                                          Live Website:
                                                  https://senecaengineering.org


                                      --------------------------------------------------
                                                      TECHNOLOGY STACK
                                      --------------------------------------------------

                                                  Static Site Generator:
                                                    Hugo (Extended)

                                                          Theme:
                                                          Blowfish

                                                          Hosting:
                                                        GitHub Pages

                                                      Deployment Folder:
                                                            docs/

                                                            Domain:
                                                      senecaengineering.org


                                        --------------------------------------------------
                                                          REQUIREMENTS
                                        --------------------------------------------------

                                          Before working on this project you must install:

                                                            1) Git
                                                        2) Hugo Extended

                                                        Check Hugo version:

                                                            ```bash
                                                          hugo version

                                                          CLONE THE PROJECT

                                                        Clone the repository:

                                                      git clone <REPOSITORY_URL>
                                                        cd engineering-society

                                                            Example:

                                    git clone https://github.com/Seneca-Engineering-Students-Society/ENG.git
                                                              cd ENG
                                                              PROJECT STRUCTURE

                                                        
                                                      RUN WEBSITE LOCALLY

                                                  To preview the website locally:
                                                  
                                                  hugo server
                                                  
                                                  Open in browser:
                                                  
                                                  http://localhost:1313
                                                  
                                                  Every change will update automatically.
                                                  
                                                  Stop the server:
                                                  
                                                  CTRL + C
                                                  
                                                  EDIT EXISTING PAGES
                                                  
                                                  Pages are located inside the content folder.
                                                  
                                                  Example:
                                                  
                                                  Edit About page:
                                                  
                                                  nano content/about/_index.md
                                                  
                                                  Edit Home page:
                                                  
                                                  nano content/_index.md
                                                  
                                                  Save file in nano:
                                                  
                                                  CTRL + X
                                                  Y
                                                  ENTER
                                                  
                                                  CREATE A NEW BLOG POST
                                                  
                                                  To create a new blog post:
                                                  
                                                  hugo new blog/my-post.md
                                                  
                                                  Then edit the file:
                                                  
                                                  nano content/blog/my-post.md
                                                  
                                                  Example content:
                                                  
                                                  ---
                                                  title: "Robotics Workshop"
                                                  date: 2026-03-05
                                                  ---
                                                  
                                                  We are hosting a robotics workshop this Friday at Seneca.
                                                  
                                                  Save and exit.
                                                  
                                                  CREATE A NEW EVENT
                                                  
                                                  Create an event page:
                                                  
                                                  hugo new events/my-event.md
                                                  
                                                  Edit the file:
                                                  
                                                  nano content/events/my-event.md
                                                  ADD IMAGES
                                                  
                                                  Place images in:
                                                  
                                                  static/images/
                                                  
                                                  Example usage inside Markdown:
                                                  
                                                  ![Example Image](/images/example.jpg)
                                                  BUILD THE WEBSITE
                                                  
                                                  Before publishing changes, build the site:
                                                  
                                                  hugo --minify
                                                  
                                                  This command generates the website inside:
                                                  
                                                  docs/
                                                  PUBLISH CHANGES
                                                  
                                                  After building the website, push changes to GitHub:
                                                  
                                                  git add .
                                                  git commit -m "update website"
                                                  git push
                                                  
                                                  GitHub Pages will automatically deploy the updated site.
                                                  
                                                  DEPLOYMENT SETTINGS
                                                  
                                                  GitHub Pages is configured to deploy from:
                                                  
                                                  Branch:
                                                  main
                                                  
                                                  Folder:
                                                  docs
                                                  
                                                  Do NOT manually edit files inside the docs folder.
                                                  
                                                  Always generate docs by running:
                                                  
                                                  hugo --minify
                                                  COMMON WORKFLOW
                                                  
                                                  Typical workflow for updating the website:
                                                  
                                                  Pull latest changes
                                                  
                                                  git pull
                                                  
                                                  Edit content
                                                  
                                                  Preview locally
                                                  
                                                  hugo server
                                                  
                                                  Build website
                                                  
                                                  hugo --minify
                                                  
                                                  Commit changes
                                                  
                                                  git add .
                                                  git commit -m "describe changes"
                                                  
                                                  Push
                                                  
                                                  git push
                                                  TROUBLESHOOTING
                                                  
                                                  Website not updating:
                                                  
                                                  Make sure you ran:
                                                  
                                                  hugo --minify
                                                  
                                                  Then push changes again.
                                                  
                                                  CSS changes not visible:
                                                  
                                                  Clear browser cache:
                                                  
                                                  CTRL + SHIFT + R
                                                  
                                                  If the website still does not update, check GitHub Pages settings.
                                                  
                                                  CONTACT
                                                  
                                                  Maintained by:
                                                  
                                                  Seneca Engineering Society
                                                  
                                                  For technical issues contact the repository maintainer.
                                              
