## Purpose

Many AI outputs fail due to vague or poorly structured instructions. This tool enforces a clear framework so you can:

- Define a **Persona/Role**
- Provide relevant **Context**
- State a precise **Objective**
- Identify the **Audience**
- Specify **Boundaries & Style**
- Optionally include an **Example**

The result is a clean, consolidated master prompt ready to copy or export.

## Key Features

### Structured Prompt Framework
Segmented input fields guide users through best-practice prompt design. Each section can be included or excluded from the final output.

### Live Master Prompt Preview
- Real-time rendering of the consolidated prompt  
- Clear section headings  
- Word and character count  

### Privacy by Design
- 100% client-side execution  
- No server-side storage  
- No data transmission  
- Uses browser `localStorage` only  

### Accessibility-Focused
- Keyboard navigation support  
- Visible focus states  
- ARIA live regions for status updates  
- Skip-to-content link  
- Modal focus trapping  

### Productivity Enhancements
- Autosave with status indicator  
- Fullscreen editing per section  
- Copy to clipboard (keyboard shortcut supported)  
- Export as Markdown (`.md`)  
- Optional Example section toggle  
- Clear/reset function  

## How It Works

All content is processed directly in the browser. The app:

1. Stores inputs locally via `localStorage`
2. Dynamically composes the master prompt
3. Updates the preview in real time
4. Allows copying or exporting the final result

No installation or configuration is required.

## Technical Overview

- Single-page HTML application  
- Vanilla JavaScript (no external frameworks)  
- CSS-based responsive layout  
- WCAG-conscious design decisions  
- Markdown export via Blob API  

## Deployment

The app can be:

- Hosted on GitHub Pages  
- Deployed on any static hosting service  
- Used locally by opening the HTML file  
