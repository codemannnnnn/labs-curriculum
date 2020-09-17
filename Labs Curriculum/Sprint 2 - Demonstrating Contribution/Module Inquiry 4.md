# Module Inquiry 4

## Questions

1. Link to the pull request you are most proud of.

I actually don't have a PR i'm proud of yet. All of my work so far as one of the backend people has been dealing with research on our notification/email implementation(learning what we need to do), as well as dealing with OKTA and figuring out our heroku db migration with postgres. Running into issue all over the place. Once I do have a PR i'm proud of, i'll be sure to let my TL know.

2. Why are you proud of this feature? What was difficult about its implementation?

I'm proud of how much digging we have done as a team on Okta and how to work with it, as well as the plethora of info we have dug up on deploying to heroku with db and migrating our db tables.

3. How does this feature help the user?

This will help our team because currently our deployed API doesnt have any tables connected to it.

4. Think about the process of delivering this feature: from ideation, to scoping, to pairing, to testing. Knowing what you know now, what would you change about the way in which you delivered this feature?

Wouldn't change a thing, the collab and digging has yeilded results. Except for the file structure. The scaffolding we were given includes the knexfile in a config directory, but as we have found we need that in the root. So now we need to update the rest of the files to point correctly.
