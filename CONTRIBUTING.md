
# Contributing to InFlow

We're thrilled you're considering contributing to InFlow!

Please take a moment to review this document to understand how to contribute effectively.

---

## Got a Question or Idea?

Before opening a Pull Request, consider these options:

* **Telegram:** Join our community on [Telegram]([https://t.me/+FRALUDsi24k4MWQ0]) for real-time chat, quick help, and to connect with other contributors.

---

## Getting Started

To contribute to InFlow, follow these steps:

1.  **Fork the Repository:** Click the "Fork" button at the top right of this repository's page. This creates a copy of the repository in your GitHub account.
2.  **Clone Your Fork:**
    ```bash
    git clone [https://github.com/](https://github.com/)[YourGitHubUsername]/[YourRepoName].git
    cd [YourRepoName]
    ```
3.  **Install Dependencies:** We use `npm` as our package manager. Then, install project dependencies:
    ```bash
    npm i
    ```
4.  **Create a New Branch:** Always create a new branch for your work. Use a descriptive name like `feat/add-user-profile` or `fix/button-alignment`.
    ```bash
    git checkout -b your-branch-name
    ```
5.  **Run the Development Server:**
    ```bash
    npm run dev
    ```
    Open [http://localhost:3000](http://localhost:3000) in your browser to see the project running.

---

## Design Guidelines & Consistency

We prioritize a consistent and beautiful user experience. Our UI is built with **Next.js**, **Shadcn UI**, and **Tailwind CSS**, following a strict design system defined in Figma.

* **Figma is Our Source of Truth:** All UI components, colors, typography, and spacing are in our Figma design file.
    * **View our Figma Design System:** [https://www.figma.com/design/Ohc0np4T3zacWJwQ8ZRsG4/InFlow-App?node-id=1-319&t=pELjmmgYTAV00C7T-1]
* **Shadcn UI Customization:** When you add a Shadcn UI component, you'll find its code in `components/ui`. Customize these components and their Tailwind classes to precisely match the Figma designs.
* **Refer to Figma** *before* implementing any UI changes or new components. Your Pull Request will be reviewed against these design guidelines.

---

## Your First Contribution (Good First Issues)

Look for issues labeled `good first issue`. These are typically smaller, well-defined tasks perfect for getting familiar with the codebase.

---

## Submitting a Pull Request (PR)

1.  **Sync Your Fork:** Before pushing changes, pull the latest from the `main` branch of the original repository to your local `main` branch, then rebase your feature branch on top of it.
    ```bash
    git checkout main
    git pull upstream main # (assuming you've added the original repo as 'upstream')
    git checkout your-branch-name
    git rebase main
    ```

2.  **Commit Your Changes:**
    * Write clear, concise, and descriptive commit messages. We follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for better commit history.
    * Examples: `feat: add user profile page`, `fix: correct button alignment on mobile`, `docs: update contributing guide`.
3.  **Push to Your Fork:**
    ```bash
    git push origin your-branch-name
    ```
4.  **Open a Pull Request:** Go to your fork on GitHub. You should see a "Compare & pull request" button.
    * **Target Branch:** Ensure you're merging into the `main` branch of the original repository.
    * **Fill Out the Template:** Please include:
        * A clear description of your changes.
        * Why these changes are necessary.
        * Screenshots or GIFs for any UI changes.
        * References to any linked issues (e.g., `Closes #123`).
        * Confirmation that you've tested your changes locally.
        * Confirmation that your changes adhere to our design guidelines.
5.  **Address Review Feedback:** We'll review your PR. Be open to feedback and suggestions. We might ask for changes to meet our coding standards or design requirements.

---

##  Thank You!

Your efforts help us build a better social platform for everyone. We appreciate your patience and dedication. If you have any questions along the way, don't hesitate to ask on  [Telegram]([https://t.me/+FRALUDsi24k4MWQ0]) or by commenting on your PR/issue.
