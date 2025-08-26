# FiftyBit-ResearchRadar

Welcome to **FiftyBit-ResearchRadar**, an open-source platform dedicated to helping students find and share PhD, RA, and internship opportunities around the world. Our mission is to make the search for academic positions simpler and more transparent for everyone.

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/sobit-nep/fiftybit-researchradar)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### ✨ [**View the Live Project Here!**](https://researchradar.netlify.app/)

---

## We Need Your Help! 🙏

This project thrives on community contributions. The more opportunities we have listed, the more useful this tool becomes for students everywhere. If you know of a research opening, we encourage you to add it to our list.

The entire process is managed through GitHub, and you don't need to be a coding expert to help out.

---

## How to Add an Opportunity

Contributing is as simple as adding a new entry to our central data file. Follow these easy steps to submit your first contribution.

### Step 1: Fork the Repository

First, you'll need your own copy of this project. Click the **"Fork"** button at the top-right of the repository page. This will create a copy of the project in your own GitHub account.



### Step 2: Edit the `data.json` File

In your forked repository, navigate to the **`data.json`** file. This file contains all the research opportunities listed on the website.

Click the **pencil icon** to start editing the file directly in your browser.



### Step 3: Add the New Opportunity

Scroll to the bottom of the `data.json` file. Carefully add a new entry for the opportunity you want to share. It's crucial to follow the exact JSON format.

Copy the template below and place it **before the final `]` bracket**. Make sure to add a comma `,` after the preceding entry.

**✏️ Copy this template:**

```json
{
  "University": "Name of University",
  "Faculty": "Professor's Name",
  "Research Interests": "Keywords like AI, Robotics, NLP, etc.",
  "Notes": "e.g., 26 Fall or 2025 Spring/Fall",
  "Homepage": "URL to the professor's or lab's homepage",
  "Positions": "e.g., 1-2 PhDs with RA, Interns",
  "Requirements": "e.g., TOEFL, no GRE",
  "How to Reach out": "Professor's email address"
}
