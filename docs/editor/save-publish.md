# Saving and Publishing your work

On Scribo, you work on two different versions:

- Development
- Production

## Managing versions

Every change that you save on the editor will change what we call the "Development Version". This version is the one that you see by clicking on the Preview button at the top right of the editor or accessing the URL:

https://app.scribo.dev/YOUR_TEAM_NAME

Clicking on the "Publish" button will take a snapshot of the current "Development Version" and mark it as the new "Production Version" of your team's application. This version will be available at:

https://YOUR_TEAM_NAME.scribo.dev

This distinction helps you develop new features without impacting your production application.

## Limitations

Since Scribo limits you to having two versions, working simultaneously on multiple new features can be challenging. To solve this problem, we recommend you to switch to our [GitHub Sync Integration](/editor/GitHub-sync) or use a "Feature Flag" approach, like hiding some functionality using conditions and parameters on the URL.
