# GitHub Introduction
FGRes AB2 2021-02-03

**GitHub Account**:  
Sign up on [github.com)(https://github.com)

## Software: Github Desktop (Windows / Mac OS)
go to [desktop.github.com](https://desktop.github.com) download "Github Desktop", launch it.

1. "Sign in to GitHub.com" (opens in Browser) --> "Authorize Desktop" --> authorize application, (always use application)
2. Configure git with user name and email

**Repository** = "repo" = a project on github

### begin with
"File ->"
- clone a repository from the internet
- create new repository on your hard drive (and upload it later)
- add existing repository (to GitHub Desktop that you already own)

#### clone
e.g. 
repository URL: `https://github.com/Lwinkeler/Q100-AB2-ABM`  
local path: `C:\Users\dav\Documents\GitHub\Q100-AB2-ABM`

Clone.

### Overview
- Changes: shows what you changed since your last pull
- History: history of changes of all users in repository

Fetch origin: checks what is 

### standard commands
see: [understanding the github flow](https://guides.github.com/introduction/flow/)

1. fetch: check for changes of your local repo to the remote origin
2. (pull): if there are changes on server (from somebody else), download them.
3. (add): (using the checkmark in GitHub Desktop) decide which of your changes you want to upload
4. commit: create a bundle of all your marked changes to upload. **Use a concise commit messages that will show others rightaway what has changed!**
5. push: upload the bundle of changes to the server (for everyone else to see)

### branches
see: [understanding the github flow](https://guides.github.com/introduction/flow/)
> When you create a branch in your project, you're creating an environment where you can try out new ideas. Changes you make on a branch don't affect the main branch, so you're free to experiment and commit changes, safe in the knowledge that your branch won't be merged until it's ready to be reviewed by someone you're collaborating with.

## GitHub.com
creating repositories, changing files, using issues, merging branches (using pull requests)
[gitHub Tutorials](https://guides.github.com/https://guides.github.com/activities/hello-world/)  
--> [understanding the GitHub flow](https://guides.github.com/introduction/flow/)  
--> a sentence to [markdown](https://guides.github.com/features/mastering-markdown/)  

## Github CLI
[GitHub CLI Manual](https://cli.github.com/manual/)  
- `git fetch`: check for changes of your local repo to the remote origin  
- `git status`: check for changes within you local repo since last pull  
- `git pull`
- `git add folder/file.txt`
- `git commit -m "commit message"`
- `git push`

## GitHub in AB2?

#### Ordnerstruktur
bisher nur Notizen  
Ordner für Code und Dateien, z.B.  

```
ABM
└───data
│       drop data from pre-computed models here
└───Doc
│       all process and progress here.
└───external
│       contains external git repositories from MIT and misc.
└───simulations
│   └───Simulation 1
│   │       with standard parameters
│   └───Simulation 2
│   │       some tests with other parameters 
│   └───Simulation 3
│           a completely different simulation
│
literature
│
notes
│
...
```

#### Issues
- unterschiedliche Projekte benutzen:
	- GAMA: _Aufgaben im weiteren Vorgehen der ABM-Gestaltung_
	- Gesamtübersicht: _Projektfortschritt im Stufensystem (nach Nikolic) mit Meilensteinen_
	- Fortschritt: _nicht-code-bezogene, kleinteiligere (organisatorische) Aufgaben_
- user-specific tasks: assign a person to a task
- zusätzlich zur Projekt-Zurodnung können labels benutzt werden