# ePostit

ePostit is an Outlook Add-In that will allow users to create post-it summaries of important emails to help better search for information lost in email threads. Runs on both Outlook.com as well as Outlook.

## Running the ePostit Add-in on Outlook.com and/or Outlook
To be able to use the add-in on Outlook.com and/or Outlook, you need to have an Outlook mail account.
First download this project onto your computer. Then type `npm start ` in terminal and press enter. You should see a webpage popup with a Connected to BrowserSync message in the top right corner. If you see some Insecure Site error or some other error, see [below](https://github.com/sarmxzh/ePostit#insecure-site-issues-when-initiating-the-project).

### For Outlook.com
- Open **Outlook.com**
- Click on the **Settings** icon on the top right corner of your screen.
- Click on **Manage Add-Ins**
- Go to **My Add-ins**
- Click on **Add a custom add-in**, **add from file**, and navigate to where you downloaded the project
- Find, select, and load the 'post-it-tag-manifest.xml' file (found in the `src` folder)

### For Outlook on Desktop
- Open **Outlook**
- Select the **Store** button in the Ribbon
- Click on **Add-Ins**, then select **My add-ins**
- Select **Custom add-ins**, **Add a custom add-in link**, and then select **Add from file**
- Select and load the 'post-it-tag-manifest.xml' file (found in the `src` folder)

The ePostit add-in should now be in your add-ins for Outlook.com. To see them, click on any message and there should be a logo, or logos (depending on how many addins you have), next to the Reply All button.

## Insecure Site issues when initiating the project
In the case that you may run into insecure site issues see [this issue](https://github.com/OfficeDev/generator-office/blob/master/src/docs/ssl.md) and [this issue](https://github.com/OfficeDev/generator-office/issues/244), and follow the steps outlined in them for verifying the security certificates. If there are still issues with it coming up as an insecure site, try running the project with incognito mode.

## Want to Contribute?
All contributions are welcome! Please see [Contributing.md](https://github.com/sarmxzh/ePostit/blob/master/CONTRIBUTING.md) for more information.

## License
[MIT License](https://github.com/sarmxzh/ePostit/blob/master/LICENSE)
