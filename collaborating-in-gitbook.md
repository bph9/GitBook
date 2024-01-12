# Collaborating in gitbook

## Using Live editing (adding from Test Branch 3)

Our gitbooks are currently set to "live editing" so you should be able to click the "Edit" button in the top nav then just make your edits. You don't need to manually save.&#x20;

The comment feature is also useful for communicating with others or setting a reminder for yourself. You can tag other people in a comment using "@name".&#x20;

Click the speech bubble icon in top right to see if there are any comments for you.

Don't click "Publish" until we're ready to make it public.&#x20;



## Not using live editing (adding from Test Branch 3)

Note: I can not fully test out how it might work once the book is published so here are some thoughts and draft of how I think it might work. - Suzanne

This is probably going to be a better option once the book goes into production but you'll need to experiment and decide.

Without live editing turned on, it will allow you to work on edits without publishing them because it will create a new "branch" for the edits and the main one that's in production will become read-only. Any new edits to the branch will need to be submitted for change and someone will need to approve it.&#x20;

Gitbook offers a variety of role types if you want to set up a flow where certain people can only comment or edit but can't push out changes and others have fuller powers like putting something into production.&#x20;

### When multiple people are editing

If we want to do a large batch at once or small changes as needed that's fairly straightforward (just have one working "edit"). If we might have a some edits in progress to get published at a different time than another batch of edits, then we should make those as different edit chunks and use the edit annotations to know which page the edit is connected to.&#x20;

1. First person will make their edits and save (but NOT merge)
2. Second person should go into drafts and select the first person's draft and use that to make additional edits and save again.
3. When done, merge

If each person creates new edits in drafts, there may be a conflict when it's time to merge.
