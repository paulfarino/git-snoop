# git-snoop
pre-commit: A POC Git post-commit hook that outputs relevant text  
pre-push: Asks... Are you sure you want to push at (current_time)?

#### Why build this?
The name originates from the idea of celebrating and having fun with every commit. After each commit you could pass in a variable to output Snoop Dogg lyrics or your favorite artist.  
ex: `git ci -m --snoop "Initial commit"`  

Working in various development environments there's value to create messages that are relevant based on time of commit, day the commit was made, and to which upstream environment.

#### TODO
- [x] Create POC shell command to output text
- [x] Create POC shell command pre-push to ask if you'd want to push at the current time
- [ ] Pass argument to allow output of a specific text file or shell command (ex: git commit -m "Initial commit [snoop])  
- [ ] Investigate Git Config Flags (ex: git commit --snoop)  
- [ ] Create Ruby Gem to allow anyone to drop into projects  
 
-------------
Brought to you by [Paul Farino](https://github.com/paulfarino)
