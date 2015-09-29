# Zipskee
`Zipskee is a social platform where travelers and locals connect. Travelers and locals can search by destination and/or 
interest. Connect with people who have the same passions in life no matter where you’re going. Message people for 
recommendations, for travel advice, or even for meeting up. Make a connections when you’re planning your trip or even 
after you land. Share stories, experiences, and culture! Stay connected and bit by bit, the world gets a little bit 
smaller.`

## Development
### Environment Setup (Mac OSX)
- Clone Repo
  * github URL: https://github.com/TaeKimJR/zipskee
- Switch to the 'develop' branch (DO NOT DEVELOP OUT OF MASTER!)
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
- Move all of the files on the server into the last_commit directory
- Delete all of the files on the server
- Move all of your new commit files to the server
- Test the shit out of your site. Or... I'll... Find... You...
- If acceptable, merge development -> master and tag with version

#### Revert Deployment
- Re-connect to the GoDaddy file server through FTP (see Deployment step 1)
- Delete all of the files on the server
- Move all of the files from the last_commit directory to the server
- Test again. I... Mean... It...

### Credits
Template: http://themeforest.net/item/urip-professional-landing-page/11317046


