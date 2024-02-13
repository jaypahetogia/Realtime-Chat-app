# Realtime-Chat-app
A web app of a private realtime chat app. It allows its users to login and chat with other users online. A new user is able to register using their email.
VSCode as our plaTorm for coding
- React.js as the language, using both .js and .jsx for easier syntax and components handling - Scss and mixin for addi2onal structure and features/customiza2ons
- Installed Yarn instead of using npm since yarn is faster
- Firestore to handle authen2ca2on, storage/database, and connec2ons
- Node.js for server-side

Running the Applica5on
1. Using VSCode, open the folder containing the React applica2on
2. Open the vscode terminal via “control + back2ck” shortcut, or go to View>Terminal
3. If you do not have Node.js yet, go ahead and download the latest version online (due to
compa2ble issues, our app has been configured to use Node.js version 16)
4. Downgrade your Node.js version to 16 using Node Version Manager (NVM), a tool that
allows you to manage mul2ple Node.js versions. Here's a step-by-step guide on how to do it: o installNVM(NodeVersionManager):Ifyouhaven'talreadyinstalledNVM,youcan
install it by running the following command in your terminal:
curl -o- hEps://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash - ACer running the installa2on command, you might need to close and reopen your
terminal or run the following command to get access to the nvm command: export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && prinT %s "${HOME}/.nvm" || prinT %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
- Once NVM is installed, you can install Node.js version 16 by running: nvm install 16
This command will download and install Node.js version 16.x.x (the latest 16.x version available).
- ACer installa2on, you can switch to the newly installed version by running: nvm use 16
- To confirm that you are now using Node.js version 16, run: node -v
This command will display the currently ac2ve Node.js version, which should be 16.x.x.
5. Run: yarn start
This will execute and begin the applica2on in a new window of your web browser
