# Red-Privacy-Policy

> [!NOTE]
> If you've just created a repository from a template,
> wait about 20 seconds and then refresh the page to see the updated README
> with further setup instructions.

This is a repository template for hosting a privacy policy of your own instance of [Red](https://github.com/Cog-Creators/Red-DiscordBot).
It contains a workflow for publishing the privacy policy along with any other Markdown or HTML files
as a GitHub Pages website.

The repository comes with a sample privacy policy in the `index.md` file
which describes data collected by Red's core cogs and can be used as a starting point for your own instance.
This file is hosted as the main page on the generated GitHub Pages website.

The sample privacy policy links to the `3rd-party.html` file for information about data
that's collected in addition to what's described in the main document.
You can generate the `3rd-party.html` file for your own bot by running its `[p]mydata 3rdparty` command
and uploading its result to this repository.

As a bot owner, you are responsible for the privacy policy you've published
and need to ensure yourself that you're compliant with Discord's ToS and any applicable laws.
If you choose to use the sample privacy policy, you must, at the very least, review the contents
of the `3rd-party.html` to make sure it describes everything that's collected accurately
and, if it isn't, make the necessary changes yourself.
Remember that the 3rd-party data statements may change whenever new cogs are installed or existing cogs are updated
and that what `[p]mydata 3rdparty` command generates depends on the cogs that are currently loaded.

## How to set this up?

1.  Login to your GitHub account or register, if you don't have one already.
1.  Go to https://github.com/Cog-Creators/Red-Privacy-Policy/generate.
1.  Set a name for the repository. This name should probably contain something identifying the specific bot
    that this policy will apply to as a single repository created from this template can only represent one bot.
1.  Keep visibility set to "Public".
1.  Click on "Create repository".
1.  After the repository is created, you'll be presented with the repository page.
    Wait about 20 seconds, then refresh the page. You should now see a new README page.
1.  Continue by following the step-by-step instructions in the new repository's README.
