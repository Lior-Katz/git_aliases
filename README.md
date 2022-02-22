# Setup global aliases for gitconfig

## Steps - 
1. Clone this repository to local
2. Update contents of your .gitconfig (google for its path on your machine!) to below - 
```
[include]
   path = <path\\to\\alias4git\\alias.gitconfig>

[alias]
	cfg = !git config --file <path\\\\to\\\\alias4git\\\\alias.gitconfig>
	
[user]
	email = <your-email>
	name = <your-name>
	
```

3. Update alias.gitconfig path to appropriate path from repository cloned
