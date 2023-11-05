This is a README where I will explain a little about this repo.

Watch this space!

These are the commands I used to set up my credentials:

I created a token (classic) on GitHub.com and then used:

git credential-store --file ~/git.store store
protocol=https
host=github.com
username=18601512+bobbyiveson@users.noreply.github.com
password=my-github-token-string

git credential-store --file ~/git.store get
(this obtains my credentials saved in ~/git.store)
