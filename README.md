# Roblox Script Assistance

Welcome to the official RSA FAQ and Guides page. 

If you're completely new to Roblox Studio and scripting in general, find your way to the **Online References** section. 
Most of the sections describe themselves. If you need any help or have any questions, make sure to ask in the [Discord Server](https://discord.gg/WHTAYrK). 
If you have any suggestions for the FAQ, make sure to submit them to the form.

# FAQ
**Where’s the best place to ask for help?**
Under the category titled "Help", you can find many channels suited for asking questions. Anything Roblox related belongs in the Roblox channels. Anything not related to Roblox’s goes in any channel applicable.


**Why am I not receiving help?**
Usually, if you don’t ask your question properly, the community responds sarcastically. To avoid that, try to follow the tips in the Asking Good Questions section.


**Can I hire developers here?**
The short answer is no. This is not a hiring community and is simply here for assistance in scripting. If you're looking for developers for hire, go to Hidden Developers or look on the Roblox DevForum.


**How do I obtain special roles like regular?**
There isn’t a guaranteed method of getting them, as it’s not automated by the bot. You mainly obtain them by being active or meeting standards set by the staff, for information ask the staff team.

# Discord Channels

#### For the most part, the channels document themselves. If you want to learn more about a channel, check the channel topic by clicking on the text at the top.

**#roles**

React to the messages in this channel to obtain self assignable roles like colors and event roles.

**#game-jam**

Occasionally, we host game jams which are timed events. You create a game with a given theme within the time constraint. The judges then decide who made the best game. Rewards for participating can include discord roles, robux, discord nitro and more.

**#beginner-resources**

This channel is catered towards helping people who are completely new to scripting. It contains resources that teach you how to use Roblox Studio and how to begin scripting.

**#general-logs**

Yes, you are meant to be able to see this channel. Moderation action is public in this server for transparency purposes. This channel lists out specific moderation actions within the server.

If you have any further questions about the channels in the discord, feel free to ask in `#commons`.

# Discord Roles
In progress.

# Common Errors
### Note: Always keep in mind that you have to check your spelling! Everything is case-sensitive.
#### (This section is not 100% comprehensive and you may need extra debugging.)

**Expected X when parsing expression, got 'Y':**

Simply put, X was expected (whether it be identifier, do, then, etc.) and you instead gave it Y.

Potential fixes: Check to see what Y is. If Y is something as simple as an end parenthesis, just get rid of it. If Y is a word like “then” or “do”, just add a condition in between.

**Attempt to index X with Y:**

This error means you attempted to access something that can't/shouldn't be accessed. e.g nil.

Potential fixes: Make sure the value you’re attempting to index is not one that cannot be indexed similarly to tables.

**Attempt to perform arithmetic (X) on Y and Z:**

This error means you attempted to do math on two data types that don't support the operation provided.

Potential fixes: Make sure the data type you’re using can be converted to a number. If it supports metatables, make sure you implement those correctly if applicable.

**Unexpected Unicode character: U+2028. Did you mean ' '?**

This error means you pressed shift + enter to start a new line.

Potential fixes: You can either undo to before the line is created or rewrite the line. Alternatively, you can delete the whitespace character on the line indicated by the error.

**X is not a valid member of Y:**

This error means the thing you’re trying to access (whether that be a child, property or something else) does not belong to Y.

Potential fixes: Make sure you’re indexing the correct object. Also make sure you have access to the object you’re attempting to index. e.g. The object is stored in ServerStorage and you're attempting to index it in a LocalScript.

**Bad Argument #X, expected Y, got Z**

This error means the data type you provided (Z), was not the data type that was expected in the function (Y).

Potential fixes: Adjust Z to fit Y’s data type.

**Attempt to resume a dead coroutine**

This error means that the coroutine that you tried to resume is no longer running, most likely because the code enclosed has finished running.

Potential fixes: Create a new coroutine or use a loop inside the thread to keep it from dying.

**Expected end, got eof**

This error only means that you left out an end.

Potential fixes: Add an extra end to close off a function or assignment

**Attempt to concatenate X with Y**

This error means you attempted to join two things via the .. operation that are not compatible.

Potential fixes: Make sure the two things you're trying to join can actually be concatenated. Only strings can be concatenated, but Lua automatically converts numbers.

**Malformed number/string**

This error means that you added something extra or forgot to include something to your number/string.
Example: 6.hello or "Hi!

Potential fixes: Change the number or string so that it doesn’t have something extra or missing.

**Attempt to call an X value**

This error means you attempted to call a value that isn’t a function or a table that doesn't have a __call metamethod attached.

Potential fixes: Make sure the value you are attempting to call is a function or in case of a table, make sure it has a __call metamethod attached when applicable.

**Warnings**

Sometimes, you may not get an error during runtime, but a red or blue underline on a line supplied by the script analysis tool.

A reference to these warnings can be found here: [https://developer.roblox.com/en-us/articles/The-Script-Analysis-Tool](https://developer.roblox.com/en-us/articles/The-Script-Analysis-Tool)

# Troubleshooting
In progress.

# Online References
Using Google is an important skill for researching and learning the API. Here are a few websites geared towards learning the Roblox API:

[https://developer.roblox.com/en-us/](https://developer.roblox.com/en-us/)

[https://robloxapi.github.io/ref/](https://robloxapi.github.io/ref/)

[https://devforum.roblox.com/](https://devforum.roblox.com/) 

# Asking Good Questions
When asking a question in any help channel, you need to make sure you’re telling us about your problem in detail.

- What is your script meant to do?
- What is your script doing instead?
- Have you playtested yet?
- Are there any errors? If so, what are they?
- Which lines are producing the error?

You should also make sure you’re only posting code that’s relevant to the problem. It’s hard to help if half your script doesn’t pertain to the problem.


# Bot Guide
Being reworked. Expect this to return in the future.

# if you can see this im not done with the docs
come back later when im finished
