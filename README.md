# Setup global aliases for gitconfig

## Steps - 
1. Clone this repository to local
2. Update contents of your .gitconfig (google for its path on your machine!) to below - 
```
[include]
   path = <path\\to\\gitalias.config>

[alias]
	cfg = !git config --file <path\\\\to\\\\gitalias.config>
	
[user]
	email = <your-email>
	name = <your-name>
	
```

3. Update gitalias.config path to appropriate path from repository cloned
