Git Cache Maintenance — Jenkins Automation


Project Structure:-

git-cache-maintenance/
│
├── Jenkinsfile
│   └── Defines the Jenkins pipeline stages for Git cache cleanup, garbage collection, 
│       and disk usage reporting. Also includes a weekly scheduled trigger.
│
├── scripts/
│   └── clean-cache.sh
│       Handles actual cache cleanup using shell commands:
│         • Deletes .git directories older than 30 days
│         • Runs 'git gc' on active caches to optimize them
│
└── README.md
    └── This documentation file that explains the project purpose, setup, and usage.



    
