### GPG key

#### 1. Generate a New Key Pair: In the Git Bash terminal, use the following command to generate a new PGP key pair:

		gpg --full-generate-key
		
#### 2. List Your Keys: First, you'll need to list your PGP keys to find the key ID you want to use. You can do this by running the following command in Git 
	
	gpg --list-secret-keys --keyid-format LONG
	
#### 3. Configure Git: Tell Git to use your PGP key for signing commits and tags. Replace KEY_ID with your actual key ID:

	git config --global user.signingkey KEY_ID
	
##### 4. Set Commit Signing: Enable commit signing globally by running:

	git config --global commit.gpgsign true
	
#### 5. Export Your GPG Key: First, you need to export your GPG key. Open Git Bash or your terminal and run the following command, replacing KEY_ID with the ID of your GPG key:

	gpg --armor --export KEY_ID

#### 6. Paste your GPG key in your profile
