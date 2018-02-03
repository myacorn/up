The long term aim of this repository is to provide a server customization bash script
that can easily be called on a new server to add our usual dependencies, tools and customizations.

    curl up.myacorn.com|bash
    
Ideally, this would be both hosted on GitHub Pages and also be served over https.

*Customizations*

- Prompt displays machine name (instead of IP)
- Install git etc
- Set up zsh?
- Nested tmux?

*Status tool*

- Show memory usage, disk free
- List all crontabs
- List all MySQL/PostgreSQL databases
- List all Apache/NGINX sites
- List all supervisor jobs
- For each webapp, list all Django superusers and number of users