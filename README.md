# Are you a robot?

A chatbot is a kind of software, written to facilitate or ‘simulate’ conversations between a computer program and a human-agent. A popular, flexible scripting language for producing this kind of software is ‘Rivescript’ which you will be using to write your chatbots.

Scripting chatbots can be a form of creative research, writing and design simultaneously –
one that asks you (the designer) to empathise, evaluate and develop an ‘identity’ other than your own and which can ‘speak’ on it’s own terms.

## Downloading the project

### Option 1: Using Github for collaborative coding (Recommended)

Github is a free hosting provider used for software development and distributed 'version control' of files and code. If you would like to use github to track changes in your project you can follow these steps, or skip to part 1.0

To use Github for this project you will need to:

1. Create an account with Github (you can use your UAL address or a personal email).
2. Download the github desktop application and log in.
3. Copy or 'clone' this project repository onto your computer from the application. By selecting `File > Clone Repository > URL` and pasting in the URL: https://github.com/jclarke-arts/are-you-a-robot
4. Once you have made changes in your code, you can then 'upload' these to Github and share them with your team. To do this you will need to write a short summary of your changes, 'commit' these changes and 'push' them to your shared Github repository in the Github desktop app.

### Option 2: Downloading from Github

If you do not wish to set up a Github account, you can download the files directly from this page (https://github.com/jclarke-arts/are-you-a-robot). To do this you will need to:

1. Click the green 'Code' button, and select 'Download ZIP'.
2. Once the download is complete, you can unzip it with the project files ready to use.

### Option 3: Downloading from moodle

The project files are also available to download as a ZIP file from moodle.

### Option 4: Email me

If you are having difficulties downloading the project files, simply email me at [j.clarke@arts.ac.uk](mailto:j.clarke@arts.ac.uk) and I will send them to you directly.

## Project Setup Using Visual Studio Code (Recommended)

Visual Studio Code (VSC) is an industry standard 'Integrated Development Environment' (IDE) produced by Microsoft. To download this program you will need to:

1. Visit the Visual Studio Code website: https://code.visualstudio.com/
2. Download the appropriate package for your operating system (Mac or Windows) and add it to your 'Applications' folder.
3. Once downloaded, open the program and select `File > Open...` – navigate to the `are-you-a-robot` folder. You can then open the whole folder (not just one file inside!) and see all of the files on the left-hand side.

#### Extensions

One of the most powerful things about VSC is the 'Extensions' system, these extensions will allow you to do things like:

1. Run a local development server to open your website in a browser
2. 'Live Share' your code-writing session, to collaborate on the project with others.
3. Add syntax highlighting for Rivescript's `.rive` files.

To do this you will need to navigate to the extensions tab by selecting `View > Extensions`, and from here we can install the appropriate extensions.

##### Live Server

To use the 'Live Server' extension that will allow you to view your project in the browser you will need to:

1. Search the marketplace for `Live Server` – a few options will appear but the correct one has over 11+ million downloads.
2. Click the green 'install' button and restart the application (open and close).
3. Once you have opened the `are-you-a-robot` folder again, select the `index.html` file.
4. In the bottom right of the screen, select the 'Go Live' button. This should automatically open a window in your default browser with your project, ready to go!

##### Live Share

To use the 'Live Share' extension that will allow you to share an editing-session with collaborators (similar to Google docs), you will need to:

1. Search the marketplace for `Live Share` – a few options will appear but the correct one has over 4+ million downloads.
2. Click the green 'install' button.
3. Click the 'Live Share' button at the bottom left of the screen and authenticate (log in) using either GitHub (recommended) or your UAL email address.
4. Once authenticated you can use the 'Live Share' button to recieve a URL that will look like this: `https://prod.liveshare.vsengsaas.visualstudio.com/join?B9EAF2D227AECD2517A0C2953FF7149C67A1`
5. You can then send this URL to your collaborators who will then be able to view and edit your code in real-time, just like Google docs!

##### Rivescript syntax highlighting

To add 'syntax' highlighting for

## Manual Project Setup

If, for whatever reason, you cannot or would prefer not to use VSC, there are manual ways to set up your 'development environment'. It is, however, a bit more work and you will not be able to use features like 'live share' that are VSC specific.

### Using 'Atom'

Atom is another, open-source IDE, similar to VSC, which can be used to build this project. To download this program and open the project you will need to:

1. Visit the Atom website: https://atom.io/
2. Download the program appropriate to your operating system (Mac or Windows)
3. Once downloaded select `File > Open...` and select the `are-you-a-robot` folder. You can then open the whole folder (not just one file inside)!

#### Mac Users

If you are on a mac, you will be able to set up a local testing using a PHP or Python server from the command line. To do this you will need to:

1. Navigate to the `are-you-a-robot` folder stored on your computer.
2. Right click the folder and select `Services > New Terminal at Folder`. This will open up a new window in the application 'Terminal' (on the line next to the cursor you will have something that looks like: `Jacks-MacBook-Pro:are-you-a-robot jackclarke$ `)

At this stage, you will run a command to start your 'development server', this simply allows you to view your files (and changes) in the browser. You can do this using either `PHP` or `Python`, both of which come pre-installed on macOS – if one option doesn't work, try the other! If neither work, email me 🙂.

To use **PHP** (recommended):

1. Type in: `php -S localhost:8000` and press the `Enter` key (you will see some text printed with one line saying: `Listening on http://localhost:8000` ).
2. Open your browser and navigate to the website: [http://localhost:8000](http://localhost:8000). Your bot should be ready to chat!

To use **Python**:

1. Type in `python -m SimpleHTTPServer` and press the `Enter` key (you will see some text printed with one line saying: `Listening on http://localhost:8000` ).
2. Open your browser and navigate to the website: [http://localhost:8000](http://localhost:8000). Your bot should be ready to chat!

Once you are down quit your development server by simply closing the terminal window `(Cmd + Q)` and clicking 'Terminate'; or by using the command `Ctrl + C`.

#### Windows Users

If you are on a Windows, you will be able to set up a local testing using a Node, PHP or Python server from the command line. In contrast to macOS, Windows does not come with these languages pre-installed so you will need to install one to set up a development server from the command line.

To install **Node** (recommended) you will need to:

1. Go to [https://nodejs.org/en/download/](https://nodejs.org/en/download/) and download the Windows installer `(.msi)` for your operating system (either 32-bit or 64-bit, if you are unsure, email me or follow [these](https://support.microsoft.com/en-us/windows/32-bit-and-64-bit-windows-frequently-asked-questions-c6ca9541-8dce-4d48-0415-94a3faa2e13d) instructions).
2. Once downloaded, run the file and follow the setup wizard, selecting all of the default options.
3. Open a 'Command Prompt' or 'PowerShell' application window and run `node -v` to ensure that it has installed correctly. It will return a number, such as `14.16.1` if it has installed correctly.

To now run your development server you will need to:

1. Navigate to the `are-you-a-robot` folder stored on your computer.
2. Press the `shift` key and right-click on the folder to open a PowerShell window directly to that folder. This will open up a new window in the application 'Powershell'.
3. Here you can type in the command `npx http-server` and hit `Enter`. After some time the command line will print `Starting up http-server...`
4. Now you can open your browser and navigate to the website: [http://localhost:8000](http://localhost:8000). Your bot should be ready to chat!

## Editing the chatbot

Once you are all set up you can now _edit your chatbot!_ To do this you will need to:

1. Overwrite the `.rive` files in the `/brain` folder with new Rivescript code. Remember to [look at the documentation](https://www.rivescript.com/docs/tutorial) if you can't remember how to do something!
2. Once overwritten, go to your development website (most likely [http://localhost:8000](http://locahost:8000)) and refresh the page. Your changes should now be implemented in your chatbot! If not, try a 'hard refresh' – this can be done in most browsers, by pressing `Cmd/Ctrl + Shift + R` instead of just `Cmd/Ctrl + R`.
3. Repeat! 🔁
