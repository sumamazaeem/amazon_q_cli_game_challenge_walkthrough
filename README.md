# 🚀 DevOps Workshop: Build a Web Game with Amazon Q CLI & Deploy for FREE! 👕
## Unleash Your Inner Game Developer & Score Awesome Swag!

Welcome to an exciting hands-on workshop where you'll dive into the world of DevOps by building your very own web-based game! We'll leverage the power of **Amazon Q CLI**, AWS's generative AI-powered assistant, to help us code, and then deploy our creation to the world for **free** using Kinsta's static site hosting.

**The Grand Prize?** Not just an awesome game and new skills, but by completing the workshop and deploying your game, you’ll be eligible to claim an **exclusive free T-shirt!** 🏆

➡️ **Check the Full T-Shirt Eligibility & Official AWS Announcement:** [Build Games with Amazon Q CLI and score a T-shirt](https://community.aws/content/2xIoduO0xhkhUApQpVUIqBFGmAc/build-games-with-amazon-q-cli-and-score-a-t-shirt)

---

## 🛠️ What You'll Learn & Do:

*   Set up your AWS Builder ID and install Amazon Q CLI.
*   Use Amazon Q CLI to brainstorm and generate HTML, CSS, and JavaScript code for a web game.
*   See a real-world example: My own **Whack-a-Mole game** built using this approach!
*   Push your game code to a GitHub repository.
*   Deploy your game globally using Kinsta's free static site hosting.
*   Share your creation and claim your well-deserved swag!

---

## ✅ Prerequisites

Before we blast off, make sure you have the following:

*   **For Windows Users:**
    *   Install Windows Subsystem for Linux (WSL version 2). [How-to Guide](https://learn.microsoft.com/en-us/windows/wsl/install)
    *   Install Ubuntu (or your preferred Linux distro) from the Microsoft Store within WSL.
    *   You'll be working from the Ubuntu (or your distro's) terminal.
*   **For Linux/Mac Users:**
    *   You're all set! Just use your standard terminal.
*   A GitHub account. [Sign up for GitHub](https://github.com/join)
*   A passion for learning and building cool stuff!

---

## 🗺️ Your Workshop Journey: Step-by-Step

Let's get building! Follow these steps to create and deploy your game.

### 1. 🆔 Create Your AWS Builder ID

Your AWS Builder ID is your personal profile for engaging with AWS tools and communities.
*   Sign up here: [https://community.aws/builderid](https://community.aws/builderid)

### 2. 🤖 Install Amazon Q CLI

Amazon Q CLI will be your AI co-pilot for this adventure.
*   Follow the official AWS instructions: [AWS Q CLI Installation Guide](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line-installing.html)
*   **Key steps:** Download the appropriate `amazonq` app image for your OS, make it executable (`chmod +x amazonq`), and optionally move it to a directory in your PATH (e.g., `/usr/local/bin/`) for easier access.
*   Verify installation by running `amazonq --version` or starting a chat with `/q`.

### 3. 🎮 Build Your Game (HTML, CSS, JavaScript)

This is where the magic happens! Use Amazon Q CLI as your AI coding companion to generate the foundation for a simple browser-based game.

*   **Start a chat with Amazon Q CLI:**
    ```
    /q
    ```
*   **Example Prompt to Amazon Q CLI:**
    ```
    Write me a simple game using HTML, CSS, and JavaScript that I can deploy on a website. Make it a Whack-a-Mole game with a scoring system and a timer.
    ```
    Feel free to get creative! Think Tic-Tac-Toe, a simple Memory Game, a basic Pong clone, etc.

*   **Refine & Iterate:** Amazon Q might give you a great starting point. You can then ask follow-up questions to refine features, add styling, or debug issues. For example:
    *   `How can I add a reset button to this game?`
    *   `Suggest some CSS to make the game board look more appealing.`
    *   `My score isn't updating correctly, can you look at this JavaScript function? [paste function]`

*   **Structure:** Your game should typically consist of three core files:
    *   `index.html`: The main structure of your game.
    *   `style.css`: For all the visual styling.
    *   `script.js`: The game logic and interactivity.

#### ✨ **Inspiration Corner: My Whack-a-Mole Game!** ✨

To show you what's possible, I built a classic **Whack-a-Mole game** using the same principles outlined in this workshop, with assistance from Amazon Q CLI!

*   🕹️ **Play the Game:** [https://amazonqcligame.sumamazaeem.com/](https://amazonqcligame.sumamazaeem.com/)
*   💻 **See the Code & How it Was Built:** [https://github.com/sumamazaeem/amazon_q_cli_game](https://github.com/sumamazaeem/amazon_q_cli_game)

In my Whack-a-Mole game, Amazon Q CLI could have helped with:
*   **Generating the HTML grid:** `/q create an HTML structure for a 3x3 grid of divs for a Whack-a-Mole game, including elements for score and timer.`
*   **Developing JavaScript functions:** `/q write JavaScript functions to: 1. Randomly make a 'mole' appear in a grid cell. 2. Handle clicks on moles to increment score. 3. Implement a 30-second countdown timer.`
*   **Suggesting CSS for visual feedback:** `/q provide CSS to style a 'mole' when it's active and when it's 'whacked'.`

This iterative prompting and refinement is key to effectively using Amazon Q CLI!

#### 📚 Resources for Web Game Development:

*   [W3Schools HTML Game Example](https://www.w3schools.com/graphics/game_intro.asp)
*   [MDN Web Docs: Game development](https://developer.mozilla.org/en-US/docs/Games)
*   [FreeCodeCamp: How to Code a Simple Game and Host it on Your Website](https://www.freecodecamp.org/news/how-to-code-a-simple-game/)

### 4. 💾 Push Your Code to GitHub

Version control is a DevOps best practice!
1.  Create a new **public** repository on GitHub (e.g., `my-q-cli-game`).
2.  Initialize a Git repository in your local game project folder:
    ```
    git init
    git add index.html style.css script.js # Add all your game files
    git commit -m "Initial game version"
    git branch -M main
    git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
    git push -u origin main
    ```
    *(Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub details)*

### 5. 🚀 Deploy Your Game for Free Using Kinsta

Kinsta offers an amazing **free tier for static site hosting**, allowing you to deploy up to 100 static sites (like your HTML/CSS/JS game) without spending a dime! It's fast, reliable, and integrates beautifully with GitHub.

**Here’s your detailed Kinsta deployment guide:**

1.  **Create a Kinsta Account:**
    *   Go to [Kinsta.com](https://kinsta.com).
    *   Look for their "Static Site Hosting" and sign up for the **free tier**.
    *   You'll typically sign up with your GitHub, Google, or email account.
    *   *(Optional Visual Guide: [Kinsta Static Site Hosting Tutorial](https://www.youtube.com/watch?v=4FenNvp3uCY) - note: Kinsta's UI might have evolved, but the core steps of connecting GitHub and deploying remain similar.)*

2.  **Connect to GitHub & Add Your Site:**
    *   Once logged into your Kinsta dashboard (MyKinsta):
        *   On the left sidebar, navigate to **"Static Sites"**.
        *   Click the **"Add site"** button.
    *   **Connect Git provider:**
        *   Choose **GitHub** (or your preferred Git provider if you used something else).
        *   Authorize Kinsta to access your GitHub repositories. You might be prompted to install the Kinsta GitHub App on specific repositories or all.
    *   **Select Repository:**
        *   From the dropdown, select the GitHub repository containing your game (e.g., `my-q-cli-game`).
        *   Select the **default branch** (usually `main`).
        *   Check "Deploy on commit" if you want Kinsta to automatically redeploy when you push changes to this branch (recommended!).
    *   **Build settings:**
        *   For a simple HTML, CSS, and JavaScript game where `index.html` is in the root of your repository:
            *   **Build command:** You can often leave this blank.
            *   **Publish directory:** `.` (a single dot, representing the root directory). Kinsta is usually smart enough to detect this for basic HTML/CSS/JS projects.
        *   Give your site a **Display Name** (e.g., "My Awesome Q Game").
    *   Click **"Continue"**.

3.  **Deploy!**
    *   Review the settings and click **"Deploy site"** (or similar phrasing like "Create site").
    *   Kinsta will now pull your code from GitHub, build (if necessary), and deploy your static site. This process is usually very quick (a minute or two).
    *   You'll see progress updates in the Kinsta dashboard.

4.  **Access Your Live Game! 🥳**
    *   Once deployment is complete, Kinsta will provide you with a public URL (e.g., `your-game-name.kinsta.page`).
    *   Visit this URL, and your game should be live for the world to see!

### 6. 📢 Share Your Work & Claim Your T-Shirt!

You built it, you deployed it, now show it off!
*   Write a blog post (on platforms like dev.to, Hashnode, Medium, or your personal blog) or create a video (YouTube, TikTok, LinkedIn) about your experience building and deploying the game.
    *   Talk about how you used Amazon Q CLI.
    *   Share what you learned.
    *   Include a link to your deployed game and your GitHub repo.
*   Share your deployed game and your story/blog/video on social media (LinkedIn, Twitter/X, etc.) using the hashtag **`#AmazonQCLI`**.
*   **Important:** Fill out the T-shirt redemption form. You'll find the link to the form in the [official AWS announcement](https://community.aws/content/2xIoduO0xhkhUApQpVUIqBFGmAc/build-games-with-amazon-q-cli-and-score-a-t-shirt).

---

##💡 Pro Tips for Success

*   **Start Simple:** Don't try to build a massive RPG for your first game. Simple mechanics are easier to implement and debug.
*   **Iterate with Q CLI:** Don't expect the first prompt to Amazon Q CLI to generate perfect, finished code. Use it as a starting point and ask follow-up questions.
*   **Test Locally:** Before pushing to GitHub and deploying, always test your game thoroughly in your local browser. Open the `index.html` file directly.
*   **Browser DevTools are Your Friend:** Use your browser's developer tools (usually F12) to inspect HTML elements, debug JavaScript (Console and Debugger tabs), and experiment with CSS.
*   **Make Your Repo Public:** Kinsta (and other static hosting providers) need your GitHub repository to be public to access the code.
*   **Have Fun!** This is a learning experience. Enjoy the process of creation.

---

##🔗 Useful Links

*   **Main Challenge Page:** [Official AWS Announcement and Rules](https://community.aws/content/2xIoduO0xhkhUApQpVUIqBFGmAc/build-games-with-amazon-q-cli-and-score-a-t-shirt)
*   **Amazon Q Developer Guide:** [Amazon Q Developer User Guide](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/what-is.html)
*   **Kinsta Static Site Hosting:** [Kinsta Static Site Hosting](https://kinsta.com/static-site-hosting/)
*   **My Whack-a-Mole Game (Example):**
    *   Live Game: [https://amazonqcligame.sumamazaeem.com/](https://amazonqcligame.sumamazaeem.com/)
    *   GitHub Repo: [https://github.com/sumamazaeem/amazon_q_cli_game](https://github.com/sumamazaeem/amazon_q_cli_game)
*   **HTML/CSS/JS Game Dev Resources:**
    *   [MDN Web Docs: Games](https://developer.mozilla.org/en-US/docs/Games)
    *   [freeCodeCamp Game Dev Articles](https://www.freecodecamp.org/news/tag/game-development/)

---

##❓ FAQ

*   **What kind of game should I build?**
    Any simple game that runs in the browser using HTML, CSS, and JavaScript. Think tic-tac-toe, memory games, simple arcade clones (like the Whack-a-Mole example!), number guessing, etc.
*   **Can I use game libraries or frameworks?**
    For this challenge, focusing on plain HTML, CSS, and JavaScript with Amazon Q CLI's assistance is recommended for simplicity and to meet the spirit of the challenge. However, if you're comfortable, small utility libraries are fine.
*   **Why HTML/CSS/JS?**
    These are fundamental web technologies, making your game easily deployable on static hosting and accessible from any device with a web browser.
*   **Is Kinsta's static hosting really free?**
    Yes! Kinsta offers a generous free tier for static sites, which is perfect for projects like this. It includes features like global CDN, custom domains (if you have one), and HTTPS.
*   **What if I get stuck with Kinsta deployment?**
    Kinsta has excellent documentation. Usually, for simple static sites, the default settings work. Ensure your `index.html` is in the root or specify the correct "Publish directory." If Kinsta can't find `index.html` in the root, try setting the "Publish directory" to the folder containing your `index.html`.

---

##🎉 Happy Building & Good Luck! 🎉

We can't wait to see the amazing games you create with Amazon Q CLI! If you have questions during the workshop, don't hesitate to ask.

Now, go forth and code!
