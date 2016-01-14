## Welcome to EVENTNAME

![](http://i.giphy.com/osicrp6ErKw9i.gif)

We've prepared this document to serve as a short walkthrough that will have you
up and running by the end of it. In order to create a chatbot we'll be depending
on a few pieces of existing technology. This will allow us to build our bot
with greatly improved speed and ease collaboration efforts so that everyone can
get involved. All of our work will utilize Node.js, so let's start there.

### Step 1: *Install Node.js*

If you do not yet have Node.js installed on your computer please do so by
visiting their [website](http://nodejs.org). This will a Javascript runtime
so that we can execute our code.

### Step 2: *Download this starter kit*

In order to help speed things up we've prepared this demo bot. Inside are
examples of many of the pieces of functionality you can find in your bot.
Our demo bot is build on top of [Botkit](https://github.com/howdyai/botkit),
a Slack specific framework built by [Howdy](http://howdy.ai/). Please download
the lastest release [here](https://github.com/davidsicher/demo-bot/releases).

### Step 3: *Install dependencies*

After downloading the project, enter the directory and install the dependencies
via the node package manager.

    $ cd ~/Downloads/demo-bot-x.x.x       // change into the project directory
    $ npm install                         // install the dependencies

### Step 4: *Register your bot*

Now that you have your bot available we'll want to connect it to Slack. As a
first step, let's register our bot. Visit the custom integrations page at
[https://slack.com/apps/manage/custom-integrations](https://slack.com/apps/manage/custom-integrations).
Select bots, add new, and follow the prompts. When completed you'll have an API
token that you can use for you're bot to connect.

### Step 5: *Edit your settings*

Next we'll create a file in the root diretory of this project called `.env`.
The file name should include the dot prefix and its contents should look like
this:

    token=xoxb-fffffffffff-PfN6HCc7L6kVHqTU3eTS1Csc

### Step 6: *SHIP IT*

You officially have a capable chat bot. Test it out by running the following:

    $ npm start

After the bot has loaded and the output has stopped you should notice that
your bot is online and available inside your Slack team. Open up `index.js` and
get hackin'!

![](http://i.giphy.com/CDMz3fckRXXDG.gif)
