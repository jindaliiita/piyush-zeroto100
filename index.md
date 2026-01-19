---
layout: default
title: Home
---

# Dev Day Lab - Zero to 100: Prompt, Build & Go Live with your High-Performance Personal Website with AI

A hands-on lab where you'll be building your very own personal website from the ground up with ease. You'll be using Adobe Experience Manager with AI tools like Cursor, and by the end, you'll be walking away with your own live site — a keepsake you can share and continue evolving.

<div class="button-container" style="margin: 2rem 0;">
  <a href="https://main--piyush-zeroto100--jindaliiita.aem.live/" class="btn btn-primary" style="background: #0969da; color: white; padding: 12px 24px; text-decoration: none; border-radius: 6px; display: inline-block; font-weight: 600;">View Live Site →</a>
  <a href="https://github.com/jindaliiita/piyush-zeroto100" class="btn btn-secondary" style="background: #21262d; color: white; padding: 12px 24px; text-decoration: none; border-radius: 6px; display: inline-block; font-weight: 600; margin-left: 1rem;">GitHub Repository →</a>
</div>

---

## Prerequisites

Before starting this lab, ensure you have:

- A personal GitHub account
- A laptop (Mac, Windows Or Linux) with an installed IDE — preferably an AI-enabled editor (Cursor is strongly recommended; VS Code is also acceptable)
- Node.js (version 20 or higher) and npm installed on your local system

### Checking and Upgrading Node.js

Check your current Node.js version:

```bash
node --version
```

If your version is lower than 20.x.x, you'll need to upgrade:

- **Mac/Linux**: Use [nvm (Node Version Manager)](https://github.com/nvm-sh/nvm#installing-and-updating) or download from [nodejs.org](https://nodejs.org/)
- **Windows**: Use [nvm-windows](https://github.com/coreybutler/nvm-windows#installation--upgrades) or download from [nodejs.org](https://nodejs.org/)

```bash
nvm install 20 # To install Node v20
node -v # Must now show Node v20.x.y installed
```

---

## Exercise 1: Bootstrap a Live Personal Site

**Objective**: Set up your GitHub repository, configure DA (Document Authoring), add your personal content, and publish your site.

**Outcome**: You will have a live personal website running on AEM Edge Delivery Services.

### Step 1: Create Your Repository from Boilerplate

1. Visit the [Dev Day Boilerplate repository](https://github.com/meejain/zeroto100)
2. Click **"Use this template"** → **"Create a new repository"**
3. Choose your GitHub personal user as the owner
4. Provide the repository name
5. Set the repository to **public** (recommended)
6. Click **"Create repository"**

### Step 2: Install AEM Code Sync

1. Visit [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync/installations/new)
2. Select the "owner" same as where you create the repo in the previous steps
3. IMPORTANT: Under **Repository access**, select **"Only select repositories"**
4. Choose your newly created repository
5. Click **"Save"**

Your site is now live at:
- **Preview**: `https://main--<repo>--<owner>.aem.page/`
- **Production**: `https://main--<repo>--<owner>.aem.live/`

> **Note**: Replace `<repo>` with your repository name and `<owner>` with your GitHub user/org.

### Step 3: Author and Manage Content

1. Navigate to [DA.live](https://da.live/start)
2. Add your newly created github repository link
3. Select the **No Sample Content** option
4. Import sample content from the provided URLs
5. Edit and customize your content

### Step 4: Preview and Publish Content

1. In DA, Click the **Preview** button to preview your changes
2. Once satisfied with the preview, click the **Publish** button to make your content live
3. Your content will now be available on both preview and live URLs

**Congratulations!** 🎉 You have successfully bootstrapped your live personal website with default blocks on AEM Edge Delivery Services.

---

## Exercise 2: Know the Development Flow for EDS

**Objective**: Set up local development environment, make changes to code, and experience live reload.

**Outcome**: You will understand the local development workflow and see real-time changes reflected in your browser.

### Step 1: Install AEM CLI

```bash
npm install -g @adobe/aem-cli
```

### Step 2: Clone Your Repository

```bash
git clone https://github.com/<owner>/<repo>
cd <repo>
```

### Step 3: Start Local Development Server

```bash
aem up
```

This starts a local server at `http://localhost:3000/`

### Step 4: Make Changes and See Live Reload

Make changes to your CSS/JS files and watch the browser automatically reload!

---

## Exercise 3: Setup AI Tooling & Build Blocks

**Objective**: Configure AI tooling (MCP servers) and build blocks using AI assistance.

**Outcome**: You will be able to leverage AI to accelerate your development work in EDS.

### Step 1: Configure MCP Servers

1. Get your access tokens (Helix and DA Live)
2. Configure MCP servers in your IDE (Cursor or VS Code)
3. Enable the tools in your AI assistant

### Step 2: Build Blocks Using AI

Use AI prompts to:
- Create new blocks
- Modify existing blocks
- Debug issues
- Optimize performance

---

## Resources

- [AEM Edge Delivery Services Documentation](https://www.aem.live/)
- [Original Lab Repository](https://github.com/meejain/zeroto100)
- [DA.live Documentation](https://docs.da.live/)

---

<div style="background: #f6f8fa; padding: 2rem; border-radius: 6px; margin-top: 2rem;">
  <h3>🎯 What You'll Accomplish</h3>
  <ul>
    <li>✅ Build and deploy a custom block on AEM Edge Delivery Services</li>
    <li>✅ Publish a live personal website</li>
    <li>✅ Learn EDS development patterns and best practices</li>
    <li>✅ Use AI to accelerate your EDS development</li>
    <li>✅ Achieve a perfect Lighthouse score (100/100)</li>
  </ul>
</div>
