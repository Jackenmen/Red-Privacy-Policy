# Privacy policy for private Red instance

This repository contains the source of the GitHub Pages website for Red's privacy policy.

The privacy policy is available at:
${SITE_URL}

## Instructions

1.  Go to: ${REPO_URL}/settings/pages
1.  Select "Source" and choose "GitHub Actions". The page will refresh.
1.  Go to: ${REPO_URL}/edit/main/index.md. An editor with sample privacy policy will open.
1.  Update the privacy policy as you see fit. At minimum, you will need to update the following:
    -   In line 11:
        Replace "BotUsername#1234 (User ID: 1234567890123456789)" with your bot's username, discriminator, and user ID.
    -   In line 44:
        Replace "\<insert contact information here\>" with information about how users can reach out to you to
        request access to their data or request a data deletion. Usually, at least an e-mail address should be offered.
1.  Once you're done, click "Commit changes..." button at the top and then confirm by clicking "Commit changes".
1.  If you've kept the link to "Additional Data Statements" from the sample policy, you will need to upload
    the `3rd-party.html` file. You can generate one for your bot by running the `[p]mydata 3rdparty` command. \
    To upload the file:
    1.  Go to: ${REPO_URL}/upload/main.
    1.  Add the `3rd-party.html` by dragging and dropping or by choosing it with a file picker.

        **NOTE:** The file needs to be named exactly `3rd-party.html` (e.g. not `3rd-party (1).html` or similar).
        If the file on your computer is named differently, you need to rename it before choosing it.
    1.  Click the "Commit changes" button once the file finishes uploading.

The privacy policy should now be available at:
${SITE_URL}
