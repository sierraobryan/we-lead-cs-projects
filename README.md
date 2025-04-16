# Projects Repository

Welcome to the Projects repository for our Hackathon project website! This repository contains a list of hackathon projects available for participants.

## How to Contribute

During the session, you'll be making contributions by:

1. **Cloning the repository**: Clone this repository to your local machine.
2. **Creating a branch**: Create a new branch for your changes.
3. **Making updates**: Add your own project idea or update existing projects in the `projects.json` file with a title, description, owner, and skills needed.
   - Here’s the structure of the data you need to add:

   ```json
   {
     "title": "Project Title",
     "description": "A brief description of the project.",
     "owner": "Your Name",
     "skills_needed": ["Skill 1", "Skill 2", "Skill 3"],
     "status": "open"
   }
   ```
5. **Creating a pull request**: Push your changes and create a pull request.
6. **Resolving merge conflicts**: Learn how to resolve merge conflicts if multiple changes are made to the same file.

## File Structure

- `db.json`: Contains an array of project details, including title, description, owner, and skills needed.

## Usage 

This JSON is used to power [we-lead-cs-hackathon.github.io](https://we-lead-cs-hackathon.github.io/). The website pulls data from two separate JSON files hosted on Github using My JSON Server, a fake online REST server for teams. This data is used to display participant profiles and project details on the website.

- The People data is served from the [People JSON Repository](https://github.com/sierraobryan/we-lead-cs-people).
- The Projects data is served from the [Projects JSON Repository](https://github.com/sierraobryan/we-lead-cs-projects) (this repository).
- The [Website Repository](https://github.com/we-lead-cs-hackathon/we-lead-cs-hackathon.github.io) contains the core files for the website (HTML, CSS, JavaScript) and handles the display of the data.

---

**Feel free to take on more issues after the session to keep improving the site and practicing Git!**

Happy hacking!
