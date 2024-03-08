<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Code with GitHub Copilot

_GitHub Copilot can help you code by offering autocomplete-style suggestions right in VS Code and Codespaces._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Leverage Codespaces with VS Code for Copilot

_Welcome to "Develop With AI Powered Code Suggestions Using GitHub Copilot and VS Code"! :wave:_

GitHub Copilot is an AI pair programmer that helps you write code faster and with less work. It draws context from comments and code to suggest individual lines and whole functions instantly. GitHub Copilot is powered by OpenAI Codex, a generative pretrained language model created by OpenAI.

**Copilot works with many code editors including VS Code, Visual Studio, JetBrains IDE, and Neovim.**

Additionally, GitHub Copilot is trained on all languages that appear in public repositories. For each language, the quality of suggestions you receive may depend on the volume and diversity of training data for that language.

Using Copilot inside a Codespace shows just how easy it is to get up and running with GitHub's suite of [Collaborative Coding](https://github.com/features#features-collaboration) tools.

> **Note**
> This skills exercise will focus on leveraging GitHub Codespace. It is recommended that you complete the GitHub skill, [Codespaces](https://github.com/skills/code-with-codespaces), before moving forward with this exercise.

### :keyboard: Activity: Enable Copilot inside a Codespace

**We recommend opening another browser tab to work through the following activities so you can keep these instructions open for reference.**

Before you open up a codespace on a repository, you can create a development container and define specific extensions or configurations that will be used or installed in your codespace. Let's create this development container and add copilot to the list of extensions.

1. Navigating back to your **Code** tab of your repository, click the **Add file** drop-down button, and then click `Create new file`.
1. Type or paste the following in the empty text field prompt to name your file.
   ```
   .devcontainer/devcontainer.json
   ```
1. In the body of the new **.devcontainer/devcontainer.json** file, add the following content:
   ```
   {
       // Name this configuration
       "name": "Codespace for Skills!",
       "customizations": {
           "vscode": {
               "extensions": [
                   "GitHub.copilot"
               ]
           }
       }
   }
   ```
1. Select the option to **Commit directly to the `main` branch**, and then click the **Commit new file** button.
1. Navigate back to the home page of your repository by clicking the **Code** tab located at the top left of the screen.
1. Click the **Code** button located in the middle of the page.
1. Click the **Codespaces** tab on the box that pops up.
1. Click the **Create codespace on main** button.

   **Wait about 2 minutes for the codespace to spin itself up.**

1. Verify your codespace is running. The browser should contain a VS Code web-based editor and a terminal should be present such as the below:
   ![Screen Shot 2023-03-09 at 9 09 07 AM](https://user-images.githubusercontent.com/26442605/224102962-d0222578-3f10-4566-856d-8d59f28fcf2e.png)
1. The `copilot` extension should show up in the VS Code extension list. Click the extensions sidebar tab. You should see the following:
   ![Screen Shot 2023-03-09 at 9 04 13 AM](https://user-images.githubusercontent.com/26442605/224102514-7d6d2f51-f435-401d-a529-7bae3ae3e511.png)

**Wait about 60 seconds then refresh your repository landing page for the next step.**

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/community/discussions/categories/github-education) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
Inspiration
The inspiration behind the Command Line Game project stemmed from a desire to create a simple yet entertaining game that could be played directly from the command line interface. Drawing inspiration from classic text-based games and the nostalgia they evoke, we aimed to develop a game that would provide an enjoyable and immersive experience for users, reminiscent of the early days of computer gaming.

What it does
The Command Line Game allows users to navigate through a series of text-based scenarios, making decisions that affect the outcome of the game. Players are presented with choices at various points in the game, leading to different branching paths and multiple possible endings. The game leverages the simplicity and versatility of the command line interface to deliver an engaging interactive experience.

How we built it
We built the Command Line Game primarily using Python, taking advantage of its simplicity and readability. The game logic was implemented using basic programming constructs such as conditionals, loops, and functions. We structured the game into modular components to facilitate code organization and maintainability.

Additionally, we utilized text-based prompts and user input handling to create an interactive gameplay experience. The game's narrative and scenarios were crafted with creativity and attention to detail, aiming to captivate players and immerse them in the game world.

Challenges we ran into
One of the main challenges we encountered was designing the branching narrative structure of the game. Ensuring that each decision point had meaningful consequences and contributed to the overall story required careful planning and iteration. We also faced difficulties in managing the game state and tracking player progress across different story paths.

Another challenge was implementing user input validation to handle unexpected inputs gracefully. We had to anticipate various edge cases and errors to provide users with clear feedback and prevent the game from crashing or entering an inconsistent state.

Accomplishments that we're proud of
We're proud of successfully creating a fully functional text-based game that delivers an engaging and immersive experience to players. We achieved our goal of capturing the essence of classic text adventures while adding our own unique twists and story elements. Additionally, we're proud of overcoming the technical challenges and refining the game mechanics to ensure smooth gameplay and enjoyable storytelling.

What we learned
Through developing the Command Line Game, we gained valuable experience in game design, narrative development, and Python programming. We learned how to structure and organize a complex interactive system, balancing player choice with predetermined story arcs. Additionally, we honed our skills in user interface design, focusing on creating an intuitive and user-friendly experience within the constraints of the command line interface.

What's next for Command Line Game
In the future, we plan to expand the Command Line Game with additional storylines, characters, and gameplay mechanics. We aim to introduce more dynamic elements such as randomized events, character interactions, and inventory management to enhance replayability and immersion. Furthermore, we'll continue to refine and optimize the game based on user feedback and iterate on our design to create an even more captivating and enjoyable gaming experience.

Built With
html
javascript
