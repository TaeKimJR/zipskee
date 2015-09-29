# Zipskee
Zipskee is ...

## Development
### Environment Setup (Mac OSX)
- Clone Repo
  * github URL: https://github.com/TaeKimJR/zipskee
- Start Server
  * navigate to project's index.html
    `cd app/`
  * start local server
    `python -m SimpleHTTPServer`
  * open browser
    `open http://localhost:8000`

### Deployment
- Using a FTP client (Filezilla), connect to the GoDaddy file server
  * Host: ftp.zipskee.com
  * Username: dev@zipskee.com
  * Password: **********
  * Port: 21
- Navigate to your project root
- Create a new directory named last_commit
- Move all of the files on the server into the newly created directory (last_commit)
- Delete all of the files on the server
- Move all of your new commit files to the server
- Test the shit out of your site. Or... I'll... Find... You...

#### Revert Deployment
- Re-connect to the GoDaddy file server through FTP (see Deployment step 1)
- Delete all of the files on the server
- Move all of the files from the last_commit directory to the server
- Test again. I... Mean... It...  

### Credits
Template: http://themeforest.net/item/urip-professional-landing-page/11317046


