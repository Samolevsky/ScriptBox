# ScriptBox

**Version 0.2.3.9** | A powerful Adobe Illustrator CEP extension by [Samolevsky.com](https://samolevsky.com)

## What is ScriptBox?

ScriptBox is a comprehensive toolbox and scripts manager for Adobe Illustrator that brings over 200 automation scripts to your fingertips. Designed to streamline your design workflow, ScriptBox organizes powerful automation tools into an intuitive interface, helping you work faster and more efficiently.

## Key Features

- **200+ Automation Scripts** organized into 11 categories for easy discovery
- **Built-in Code Editor** for writing and testing custom JSX scripts
- **Panels Manager** for quick access to all Illustrator panels
- **Favorites System** to organize your most-used scripts and panels
- **External Scripts Support** to integrate your custom script libraries
- **Tasks Manager** to track your design workflow and to-do lists
- **Video Tutorials** library for learning and reference
- **Reference Images** manager for organizing design inspiration
- **Multiple View Modes** (list, compact, grid) for personalized browsing
- **Smart Search** across scripts, panels, and features
- **One-Click Execution** for instant script running

## Script Categories

ScriptBox includes 11 specialized categories covering every aspect of Illustrator automation:

- **Arrange** (12 scripts) - Advanced object positioning, distribution, and alignment tools including grid arrangers, radial arrangers, and smart object replacers
- **Artboard** (11 scripts) - Comprehensive artboard management including batch operations, smart resizing, and content cropping
- **Color** (20 scripts) - Powerful color manipulation tools from randomizers to gradient managers and contrast checkers
- **Generator** (10 scripts) - Create complex patterns and shapes including QR codes, barcodes, fractals, and geometric patterns
- **Optimize** (12 scripts) - Document cleanup and optimization tools for streamlining files and managing symbols
- **Path** (24 scripts) - Extensive path editing capabilities including corner effects, smart connectors, and bezier handle tools
- **Randomize** (11 scripts) - Add controlled randomness to colors, positions, rotations, scales, and more
- **Rename** (7 scripts) - Batch renaming tools for layers, artboards, symbols, and swatches
- **Select** (30 scripts) - Advanced selection tools to find objects by any attribute imaginable
- **Text** (19 scripts) - Comprehensive text manipulation from randomizers to formatters and content swappers
- **Transform** (10 scripts) - Smart transformation tools including progressive transforms and aspect ratio adjusters
- **Utility** (18 scripts) - Miscellaneous productivity tools including calculators, grid generators, and workflow helpers

Plus a **Games** category (4 scripts) for when you need a creative break!

## Getting Started

1. Install ScriptBox as a CEP extension in Adobe Illustrator
2. Open the panel via **Window > Extensions > ScriptBox**
3. Browse scripts by category or use the search function
4. Click any script to run it instantly
5. Star your favorites for quick access

> **Tip:** New to ScriptBox? Start by exploring the Arrange and Color categories—they contain some of the most immediately useful scripts for everyday design work.

## Additional Tools

Beyond scripts, ScriptBox includes a **Code Editor** for writing custom JSX code, a **Panels Manager** for one-click access to all Illustrator panels, and productivity features like **Tasks**, **Videos**, and **Reference Images** to keep your workflow organized.

---


# ScriptBox User Guide

**Version:** 0.2.3.9  
**Last Updated:** October 2025  
**Author:** Samolevsky.com

---

## Table of Contents

1. [Getting Started](#1-getting-started)
   - [System Requirements](#system-requirements)
   - [Installation](#installation)
   - [First Launch](#first-launch)

2. [Interface Overview](#2-interface-overview)
   - [Tab Navigation](#tab-navigation)
   - [View Modes](#view-modes)
   - [Search Functionality](#search-functionality)

3. [Using Scripts](#3-using-scripts)
   - [Browsing Scripts](#browsing-scripts)
   - [Running Scripts](#running-scripts)
   - [Script Categories](#script-categories)
   - [Script Descriptions](#script-descriptions)

4. [External Scripts](#4-external-scripts)
   - [Adding Custom Script Folders](#adding-custom-script-folders)
   - [Managing External Scripts](#managing-external-scripts)
   - [Removing Scripts](#removing-scripts)

5. [Code Editor](#5-code-editor)
   - [Writing Custom Scripts](#writing-custom-scripts)
   - [Running Code](#running-code)
   - [Loading Scripts from URLs](#loading-scripts-from-urls)
   - [Saving Scripts](#saving-scripts)

6. [Panels Manager](#6-panels-manager)
   - [Opening Panels](#opening-panels)
   - [Searching Panels](#searching-panels)
   - [Panel Favorites](#panel-favorites)

7. [Favorites System](#7-favorites-system)
   - [Adding to Favorites](#adding-to-favorites)
   - [Organizing Favorites](#organizing-favorites)
   - [Managing Favorites](#managing-favorites)

8. [Additional Features](#8-additional-features)
   - [Tasks Manager](#tasks-manager)
   - [Video Tutorials](#video-tutorials)
   - [Reference Images](#reference-images)
   - [Info & Updates](#info--updates)

9. [Tips & Best Practices](#9-tips--best-practices)

10. [Troubleshooting](#10-troubleshooting)

---

## 1. Getting Started

Welcome to ScriptBox! This section will guide you through the installation process and help you get up and running with your new productivity toolkit for Adobe Illustrator.

### System Requirements

Before installing ScriptBox, ensure your system meets the following requirements:

- **Adobe Illustrator:** Version 18.0 (CC 2014) or later
- **Operating System:** Windows or macOS (any version compatible with your Illustrator version)
- **CEP Support:** Your Illustrator installation must support CEP (Common Extensibility Platform) extensions

ScriptBox is compatible with all modern versions of Adobe Illustrator CC and works seamlessly across both Windows and Mac platforms.

### Installation

Follow these steps to install ScriptBox as a CEP extension:

1. **Download the Extension**
   - Obtain the ScriptBox extension package from your source
   - Extract the files if they're in a compressed archive

2. **Locate Your CEP Extensions Folder**
   
   The installation location depends on your operating system:
   
   **Windows:**
   ```
   C:\Program Files (x86)\Common Files\Adobe\CEP\extensions\
   ```
   
   **macOS:**
   ```
   /Library/Application Support/Adobe/CEP/extensions/
   ```
   
   If the `extensions` folder doesn't exist, create it manually.

3. **Copy the ScriptBox Folder**
   - Copy the entire ScriptBox folder into the CEP extensions directory
   - Ensure all files and subfolders are included

4. **Enable Unsigned Extensions (if necessary)**
   
   If you're using an unsigned version of ScriptBox, you may need to enable unsigned extensions:
   
   **Windows:**
   - Open the Registry Editor
   - Navigate to: `HKEY_CURRENT_USER\Software\Adobe\CSXS.9`
   - Create a new String value named `PlayerDebugMode` with value `1`
   - Repeat for CSXS.10, CSXS.11, etc., depending on your Illustrator version
   
   **macOS:**
   - Open Terminal
   - Run: `defaults write com.adobe.CSXS.9 PlayerDebugMode 1`
   - Repeat for CSXS.10, CSXS.11, etc., depending on your Illustrator version

5. **Restart Adobe Illustrator**
   - Close Illustrator completely if it's running
   - Launch Illustrator again to load the extension

### Opening ScriptBox

Once installed, you can access ScriptBox from within Adobe Illustrator:

1. Open Adobe Illustrator
2. Go to **Window** > **Extensions** > **ScriptBox**
3. The ScriptBox panel will appear in your workspace

You can dock the panel anywhere in your Illustrator workspace, resize it to your preference, or keep it floating for easy access.

### First Launch

When you open ScriptBox for the first time, here's what you'll see:

**The Toolbox Tab**
- By default, ScriptBox opens to the Toolbox tab
- You'll see a collection of folders representing different script categories
- Each folder contains multiple scripts organized by function

**Quick Orientation:**
1. **Explore the Categories** - Click on any folder to expand it and see the scripts inside
2. **Try a Script** - Hover over any script to see its description, then click to run it
3. **Check Out the Tabs** - Notice the tab icons at the top of the panel (9 tabs total)
4. **Adjust Your View** - Use the view mode icons to switch between list, compact, and grid views
5. **Search for Scripts** - Use the search bar to quickly find specific scripts

### Verifying Successful Installation

To confirm ScriptBox is working correctly:

1. **Panel Appears** - You should see the ScriptBox panel when you navigate to Window > Extensions > ScriptBox
2. **Scripts Load** - The Toolbox tab should display folders with script categories
3. **Test a Script** - Try running a simple script like "Calculator" from the Utility category
4. **No Error Messages** - If scripts run without errors, your installation is successful

If you encounter any issues, refer to the [Troubleshooting](#10-troubleshooting) section at the end of this guide.

---

## 2. Interface Overview

ScriptBox features a clean, intuitive interface designed to give you quick access to hundreds of scripts and tools. Understanding the interface layout will help you navigate efficiently and make the most of all available features.

### Tab Navigation

ScriptBox organizes its features into **9 distinct tabs**, each accessible via icon buttons at the top of the panel. The tab navigation system allows you to quickly switch between different areas of functionality.

**The 9 Tabs:**

1. **Toolbox** (Toolbox Icon)
   - Your main hub for accessing the 200+ built-in scripts
   - Scripts are organized into 11 categories (Arrange, Artboard, Color, etc.)
   - This is the default tab that appears when you first open ScriptBox
   - Perfect for browsing and running automation scripts

2. **External Scripts** (Folder Icon)
   - Manage and run custom scripts from external folders
   - Add your own script collections or third-party scripts
   - Keep your personal scripts separate from the built-in library
   - Ideal for teams sharing custom automation tools

3. **Panels Manager** (Panels Icon)
   - Quick access to all Adobe Illustrator panels
   - Open any Illustrator panel with a single click
   - No more navigating through Window menus
   - Includes all native Illustrator panels (Layers, Swatches, Pathfinder, etc.)

4. **Favorites** (Star Icon)
   - Your personalized collection of most-used scripts and panels
   - Combines both scripts and panels in one convenient location
   - Drag-and-drop to reorder items
   - Saves time by eliminating repetitive searching

5. **Code Editor** (Code Icon)
   - Built-in JSX script editor with syntax highlighting
   - Write, test, and run custom scripts directly in ScriptBox
   - Load scripts from URLs or local files
   - Save your work as .jsx files for future use

6. **Tasks** (Checklist Icon)
   - Simple task manager for tracking your design workflow
   - Create to-do lists for projects
   - Check off completed tasks
   - Keep your work organized without leaving Illustrator

7. **Videos** (Video Icon)
   - Access tutorial videos and learning resources
   - Add links to your favorite ScriptBox tutorials
   - Build a custom library of video references
   - Quick access to visual learning materials

8. **Reference** (Image Icon)
   - Visual moodboard for design inspiration
   - Add reference images directly to the panel
   - Keep inspiration close while you work
   - Organize visual references for current projects

9. **Info** (Info Icon)
   - View current version information
   - Check for updates
   - Access support resources and documentation
   - See special thanks and supporter credits

**Switching Between Tabs:**
- Simply click any tab icon at the top of the panel to switch views
- The active tab is highlighted to show your current location
- Each tab remembers your last settings (view mode, scroll position, etc.)

### View Modes

ScriptBox offers **three different view modes** to match your workflow preferences and screen space. You can switch between these modes in most tabs (Toolbox, External Scripts, Panels Manager, and Favorites).

**View Mode Options:**

1. **List View** (Default)
   - Displays items in a vertical list with full names
   - Shows script/panel names clearly with icons
   - Best for: Detailed browsing and reading full names
   - Ideal when: You have plenty of vertical space
   - Provides: Maximum readability and clarity

2. **Compact View**
   - Condensed list format with smaller spacing
   - Fits more items on screen at once
   - Best for: Quick scanning of many items
   - Ideal when: You want to see more options without scrolling
   - Provides: Efficient use of vertical space

3. **Grid View**
   - Displays items as a grid of icons with labels
   - Visual, icon-focused layout
   - Best for: Visual recognition and browsing
   - Ideal when: You have horizontal space and prefer icons
   - Provides: Quick visual identification of scripts/panels

**Switching View Modes:**
- Look for the view mode icons in the top-right corner of applicable tabs
- Click the icon representing your preferred view (list, compact, or grid)
- Your preference is saved per tab
- Different tabs can use different view modes simultaneously

**View Mode Availability:**
- **Available in:** Toolbox, External Scripts, Panels Manager, Favorites
- **Not available in:** Code Editor, Tasks, Videos, Reference, Info (these tabs have fixed layouts optimized for their specific functions)

### Search Functionality

ScriptBox includes powerful search capabilities to help you quickly find exactly what you need without browsing through categories or lists.

**Where Search is Available:**

Search functionality is integrated into several tabs:

- **Toolbox Tab:** Search through all 200+ built-in scripts
- **External Scripts Tab:** Search your custom script collections
- **Panels Manager Tab:** Find specific Illustrator panels quickly
- **Favorites Tab:** Filter your favorite items

**How to Use Search:**

1. **Locate the Search Bar**
   - The search field appears at the top of applicable tabs
   - Look for the text input field with a search icon or placeholder text

2. **Enter Your Search Term**
   - Start typing any part of the script, panel, or item name
   - Search is typically case-insensitive
   - Results filter in real-time as you type

3. **View Filtered Results**
   - Only items matching your search term will display
   - Folders/categories containing matches remain visible
   - Non-matching items are hidden from view

4. **Clear Your Search**
   - Delete your search text to see all items again
   - Or click the clear button (X) if available
   - The full list returns immediately

**Search Tips:**

- **Be Specific:** Type "align" to find alignment-related scripts
- **Use Partial Words:** Typing "rand" will find all randomizer scripts
- **Search by Category:** Type "color" to see all color-related tools
- **Quick Access:** Search is faster than expanding multiple folders
- **Case Doesn't Matter:** "GRID" and "grid" produce the same results

**Search Behavior by Tab:**

- **Toolbox:** Searches script names and can find items within collapsed folders
- **External Scripts:** Searches through your custom script names
- **Panels Manager:** Searches all Illustrator panel names
- **Favorites:** Filters both scripts and panels in your favorites list

### Window Resizing and Responsive Behavior

ScriptBox is designed to be flexible and adapt to your workspace needs. The panel can be resized and will adjust its layout accordingly.

**Resizing the Panel:**

1. **Docked Panel Resizing**
   - When docked, drag the panel edges to resize
   - Drag horizontally to adjust width
   - Drag vertically to adjust height
   - The panel will snap to other panels and workspace edges

2. **Floating Panel Resizing**
   - When floating, drag any corner or edge to resize
   - Maintain aspect ratio by dragging corners (if desired)
   - Resize freely to fit your screen layout

3. **Minimum Size**
   - ScriptBox has a minimum width and height to ensure usability
   - Content remains accessible even at smaller sizes
   - Some elements may stack or adjust at smaller widths

**Responsive Layout Behavior:**

ScriptBox intelligently adapts to different panel sizes:

- **Wide Panels:** Grid view can display more columns
- **Narrow Panels:** Grid view adjusts to fewer columns or switches to single column
- **Tall Panels:** More items visible without scrolling
- **Small Panels:** Content remains accessible with scrolling
- **Tab Icons:** Always visible regardless of panel size
- **Search Bar:** Adjusts width to fit available space

**Best Practices for Panel Size:**

- **For Grid View:** Use a wider panel to see more items side-by-side
- **For List View:** A narrower panel works well since items stack vertically
- **For Code Editor:** Maximize width for comfortable code editing
- **For Reference Images:** Larger panel size shows images in better detail
- **General Use:** Find a size that balances ScriptBox with your other panels

**Docking Recommendations:**

- Dock ScriptBox alongside your Layers or Swatches panel for easy access
- Keep it floating if you frequently move it between monitors
- Dock vertically on the side of your screen for list-based tabs
- Consider a horizontal dock at the bottom for grid view layouts

The interface is designed to work efficiently at various sizes, so adjust it to fit your personal workflow and screen real estate.

---

## 3. Using Scripts

The Toolbox tab is the heart of ScriptBox, providing instant access to over 200 automation scripts designed to streamline your Adobe Illustrator workflow. These scripts handle everything from simple object arrangement to complex path manipulation, saving you countless hours of manual work.

### Browsing Scripts

ScriptBox organizes its extensive script library into a clean, hierarchical folder structure that makes finding the right tool intuitive and fast.

**Understanding the Folder Structure:**

When you open the Toolbox tab, you'll see **11 main category folders**, each containing related scripts:

- **Arrange** - Object positioning and distribution tools
- **Artboard** - Artboard management and manipulation
- **Color** - Color manipulation and management utilities
- **Games** - Entertainment features for creative breaks
- **Generator** - Pattern and shape creation tools
- **Optimize** - Document cleanup and optimization
- **Path** - Path editing and manipulation tools
- **Randomize** - Tools for adding controlled randomness
- **Rename** - Batch renaming utilities
- **Select** - Advanced selection tools
- **Text** - Text manipulation and formatting
- **Transform** - Object transformation utilities
- **Utility** - Miscellaneous productivity tools

**Expanding and Collapsing Folders:**

1. **Expand a Category**
   - Click on any folder name or the arrow icon next to it
   - The folder expands to reveal all scripts within that category
   - Scripts appear as individual items with icons and names

2. **Collapse a Category**
   - Click the folder name or arrow icon again
   - The folder collapses, hiding its contents
   - This keeps your interface clean and focused

3. **Multiple Folders**
   - You can have multiple folders expanded simultaneously
   - Expand only the categories you're currently working with
   - Collapse folders you're not using to reduce scrolling

**Navigation Tips:**

- **Use Search:** If you know what you're looking for, use the search bar instead of browsing
- **Explore by Task:** Think about what you want to accomplish, then open the relevant category
- **Learn Gradually:** Start with one or two categories and expand your knowledge over time
- **Favorites:** Once you find scripts you use often, add them to Favorites for instant access

**Folder Organization Logic:**

Scripts are grouped by their primary function:
- **Action-based:** Arrange, Transform, Randomize (what the script does)
- **Target-based:** Artboard, Path, Text, Color (what the script affects)
- **Purpose-based:** Optimize, Select, Rename, Generator (the script's goal)
- **Utility:** General productivity tools that don't fit other categories

This logical organization helps you develop an intuitive sense of where to find specific tools as you become more familiar with ScriptBox.

### Running Scripts

Running scripts in ScriptBox is designed to be as simple as possible—just one click and the script executes.

**The Click-to-Run Mechanism:**

1. **Locate Your Script**
   - Browse to the category folder containing the script you need
   - Or use the search function to find it quickly

2. **Click the Script**
   - Simply click once on the script name or icon
   - The script executes immediately in Adobe Illustrator
   - No need to double-click or use additional menus

3. **Script Execution**
   - Most scripts will open a dialog box with options and settings
   - Some scripts execute immediately if they don't require user input
   - Follow the on-screen prompts to configure the script's behavior

4. **Complete the Action**
   - Adjust settings in the script's dialog (if applicable)
   - Click OK or Run to apply the script
   - Or click Cancel to exit without making changes

**What Happens When You Run a Script:**

- **Interactive Scripts:** Open a dialog with options, sliders, checkboxes, and preview features
- **Instant Scripts:** Execute immediately and apply their effect to your selection or document
- **Selection-Based Scripts:** Work on currently selected objects (select objects first)
- **Document-Wide Scripts:** Affect the entire document or all artboards
- **Generator Scripts:** Create new objects or patterns in your document

**Before Running Scripts:**

- **Save Your Work:** Always save before running unfamiliar scripts
- **Read Descriptions:** Hover over scripts to see what they do (see Script Descriptions below)
- **Check Selection:** Many scripts require objects to be selected first
- **Understand Scope:** Know whether the script affects selection, layer, artboard, or document

**After Running Scripts:**

- **Undo if Needed:** Use Cmd/Ctrl+Z to undo if results aren't what you expected
- **Adjust Settings:** Run the script again with different settings to refine results
- **Save Favorites:** If you use a script frequently, add it to your Favorites

**Script Execution Tips:**

- **Test on Copies:** For destructive operations, test on duplicated objects first
- **Batch Processing:** Many scripts can process multiple objects simultaneously
- **Combine Scripts:** Use multiple scripts in sequence for complex workflows
- **Learn Shortcuts:** Some scripts have keyboard shortcuts you can assign in Illustrator

### Script Descriptions

Every script in ScriptBox includes a helpful description that explains what it does, helping you choose the right tool for your task.

**Viewing Script Descriptions:**

1. **Hover Over Any Script**
   - Move your mouse cursor over any script name in the Toolbox
   - Wait a moment (approximately 1 second)
   - A tooltip appears with the script's description

2. **Read the Description**
   - The tooltip provides a concise explanation of the script's function
   - Descriptions include what the script does and often mention key features
   - Some descriptions note whether selection is required

3. **Tooltip Behavior**
   - Tooltips appear automatically on hover
   - They disappear when you move your mouse away
   - No clicking required—just hover and read

**What Descriptions Tell You:**

- **Primary Function:** What the script does in simple terms
- **Key Features:** Special capabilities or options the script offers
- **Input Requirements:** Whether you need to select objects first
- **Output:** What the script creates or modifies

**Using Descriptions Effectively:**

- **Compare Similar Scripts:** Hover over multiple scripts in a category to find the best fit
- **Learn New Tools:** Read descriptions to discover scripts you didn't know existed
- **Verify Before Running:** Confirm a script does what you expect before clicking
- **Explore Categories:** Browse descriptions to understand what each category offers

**Example Descriptions:**

- "Create multiple copies of selected objects with precise spacing and alignment options"
- "Automatically resize artboards to fit their contained artwork perfectly"
- "Apply random colors to selected objects from current swatches"
- "Generate QR codes with custom text, URLs, and styling options"

### Accessing Individual Script User Guides

Many scripts include detailed user guides that provide in-depth instructions, examples, and tips for getting the most out of each tool.

**How to Access User Guides:**

1. **Look for User Guide Files**
   - In your ScriptBox installation folder, navigate to the `scripts` directory
   - Each category folder contains both script files (.jsx) and user guide files (.url)
   - User guide files are named: "Script Name • User Guide.url"

2. **Open a User Guide**
   - Double-click the .url file to open the guide in your web browser
   - Or right-click and select "Open" or "Open with Browser"
   - The guide opens on the ScriptBox website with detailed documentation

3. **What User Guides Include**
   - Step-by-step instructions with screenshots
   - Detailed explanations of all options and settings
   - Usage examples and common workflows
   - Tips and best practices
   - Troubleshooting information

**When to Use User Guides:**

- **Learning New Scripts:** Read the guide before using complex scripts for the first time
- **Advanced Features:** Discover hidden features and advanced options
- **Troubleshooting:** Find solutions if a script isn't working as expected
- **Optimization:** Learn tips for getting better results
- **Workflow Ideas:** See examples of how to combine scripts effectively

**User Guide Availability:**

- Most scripts include user guides, especially complex or feature-rich tools
- Simpler scripts may not have dedicated guides if their function is self-explanatory
- User guides are continuously updated with new tips and examples

### Script Categories

ScriptBox includes **11 main categories** plus a bonus **Games** category, totaling over 200 scripts. Below is a detailed overview of each category with examples of what you can accomplish.

---

#### Arrange (12 Scripts)

The Arrange category focuses on positioning, distributing, and organizing objects in your workspace.

**What You Can Do:**
- Create precise grids and patterns with multiple copies
- Arrange objects in circular or radial formations
- Swap positions between objects
- Distribute objects with proportional spacing
- Replace objects while maintaining positions

**Featured Scripts:**

- **Cloner:** Create multiple copies of selected objects with precise spacing and alignment options. Perfect for creating grids, patterns, or repeated elements with exact control.

- **Grid Arranger:** Arrange selected objects in a perfect grid with customizable rows and columns. Ideal for organizing icons, creating tile patterns, or laying out design elements systematically.

- **Radial Arranger:** Arrange objects in a circular or radial pattern around a center point. Great for creating circular menus, clock faces, or decorative radial designs.

- **Seamless Pattern Maker:** Create seamless repeating patterns from selected objects with customizable spacing and alignment. Essential for textile design, backgrounds, and repeating motifs.

- **Smart Object Replacer:** Replace the selected objects with content from the clipboard, document symbols, or other selected objects, with options to match colors, opacity, and size.

- **Swap Two Objects:** Instantly swap the positions of two selected objects. Simple but incredibly useful for quick layout adjustments.

**Common Use Cases:**
- Creating product grids for catalogs
- Building icon sets with consistent spacing
- Designing circular badges or seals
- Organizing UI elements systematically
- Creating repeating background patterns

---

#### Artboard (11 Scripts)

Artboard scripts help you manage, organize, and manipulate artboards efficiently, especially useful for multi-page documents.

**What You Can Do:**
- Automatically resize artboards to fit content
- Create artboards from selected objects
- Navigate between artboards quickly
- Duplicate artboards with their contents
- Organize and reindex artboards by position

**Featured Scripts:**

- **Fit Artboards to Artwork Bounds:** Automatically resize artboards to fit their contained artwork perfectly. Eliminates excess whitespace and ensures tight bounds around your designs.

- **Create Artboards from Selection:** Generate artboards automatically based on selected objects. Each selected object gets its own artboard sized to fit.

- **Multi-Artboard Duplicator:** Duplicate artboards along with their contents in bulk. Perfect for creating variations or multiple pages with similar layouts.

- **Re-index Artboards by Position:** Automatically reorder the artboard indices based on their spatial positioning. Keeps your artboard numbering logical and organized.

- **Smart Artboard Aligner:** Align selected objects to artboards with customizable positioning and optional resizing options. Ensures consistent placement across multiple artboards.

- **Artboard Content Cropper:** Crop or mask artboard content to fit within artboard boundaries, with options to process all artboards, selected ones, or just selected objects.

**Common Use Cases:**
- Preparing multi-page documents for export
- Creating social media template sets
- Organizing presentation slides
- Building design system documentation
- Managing icon sets across multiple artboards

---

#### Color (20 Scripts)

Color scripts provide powerful tools for manipulating, analyzing, and managing colors throughout your designs.

**What You Can Do:**
- Randomize colors with various methods
- Convert between color spaces (RGB, CMYK, HSL)
- Create gradients from selections
- Adjust opacity and color channels
- Check color contrast for accessibility
- Manage swatches and color libraries

**Featured Scripts:**

- **Color Randomizer:** Apply random colors to selected objects from current swatches. Great for exploring color combinations quickly.

- **Hue Saturation Lightness:** Adjust HSL values of selected objects with precise control. More intuitive than RGB adjustments for many color modifications.

- **Contrast Checker:** Analyze color contrast ratios between background and foreground elements according to WCAG accessibility standards. Essential for accessible design.

- **Selection to Gradient Swatch:** Extract colors from selected objects and create a customizable gradient swatch from them. Perfect for creating harmonious gradients from existing designs.

- **Average Colors:** Calculate and apply the average color values across selected objects, with options to average fills, strokes, gradients, and opacity.

- **Smart Swatch Randomizer:** Randomly apply colors from your document's swatch library to the fills and strokes of selected objects.

- **Gradient to Solid Color:** Convert gradient fills to solid colors using the dominant or average color from the gradient.

- **Swap Fill and Stroke Colors:** Instantly swap fill and stroke colors of selected objects.

**Common Use Cases:**
- Exploring color variations quickly
- Ensuring accessibility compliance
- Creating cohesive color palettes
- Converting between color modes for print/web
- Managing document color libraries
- Creating custom gradients from artwork

---

#### Games (4 Scripts)

A fun bonus category! Take creative breaks with classic games built right into Illustrator.

**What You Can Do:**
- Play classic board and puzzle games
- Take mental breaks without leaving your workspace
- Challenge yourself during rendering or processing time

**Available Games:**

- **Checker:** Play a classic checkers game directly within Adobe Illustrator
- **Connect Four:** Enjoy the Connect Four game with a visual interface in Illustrator
- **Minesweeper:** Classic minesweeper puzzle game integrated into your design workspace
- **Tic Tac Toe:** Simple tic-tac-toe game for quick breaks during design work

**Why Games?**
- Mental breaks improve creativity and productivity
- Stay in your workspace during processing time
- Fun way to test ScriptBox's capabilities
- Demonstrates the power of JSX scripting

---

#### Generator (10 Scripts)

Generator scripts create new shapes, patterns, and design elements from scratch with customizable parameters.

**What You Can Do:**
- Generate geometric patterns and shapes
- Create barcodes and QR codes
- Build fractal trees and spirals
- Generate stars, squircles, and custom polygons
- Create mathematical patterns and waves

**Featured Scripts:**

- **QR Code Generator:** Generate QR codes with custom text, URLs, and styling options. Perfect for adding scannable codes to designs, posters, or packaging.

- **Barcode Generator:** Generate UPC-12 and EAN-13 barcodes with automatic check digit calculation, customizable fonts and tracking adjustment.

- **Star Shape Generator:** Create customizable star and polygon shapes with adjustable parameters like number of sides, size, inner radius, rotation, colors, stroke width, and corner rounding.

- **Fractal Tree Generator:** Generate customizable fractal trees with adjustable parameters like branching levels, divisions, angles, scaling, position, and stroke.

- **Sine Wave Generator:** Generate customizable sine wave patterns with adjustable size, repetitions, stroke properties, and color.

- **Squircle Generator:** Create squircle shapes (square-circle hybrids) with adjustable corner radius. Popular in modern UI design.

- **Bento Grid Generator:** Create modern bento-style grid layouts with customizable cells. Perfect for contemporary web and app design layouts.

**Common Use Cases:**
- Adding functional codes to packaging design
- Creating decorative patterns and backgrounds
- Building geometric illustrations
- Generating organic shapes for nature-themed designs
- Creating modern UI elements
- Producing mathematical visualizations

---

#### Optimize (12 Scripts)

Optimize scripts help clean up documents, manage complexity, and improve file performance.

**What You Can Do:**
- Remove unused swatches, symbols, and styles
- Break symbol links and release clipping masks
- Close open paths automatically
- Group objects by attributes or artboards
- Unlock and unhide hidden elements
- Convert global and spot colors

**Featured Scripts:**

- **Document Cleaner:** Remove unused swatches, styles, symbols and other document clutter automatically. Essential for keeping files lean and organized.

- **Clipping Mask Manager:** Release, modify, or merge clipping masks with advanced options for fill/stroke styling and preview highlighting.

- **Group by Attributes:** Automatically group selected objects based on shared visual attributes like fill color, stroke color, stroke weight, opacity, and blending modes.

- **Visibility Manager:** Find and unhide hidden layers and objects through an interactive panel with search functionality.

- **Unlock Assistant:** Identify and selectively unlock locked layers and objects through an interactive interface.

- **Break Symbol Links:** Break symbol links by converting symbol instances into regular editable artwork.

- **Detach Global Colors:** Convert Spot colors and Global colors to regular RGB colors.

**Common Use Cases:**
- Preparing files for client handoff
- Reducing file size before export
- Cleaning up inherited or legacy files
- Organizing complex documents
- Troubleshooting file issues
- Preparing files for print production

---

#### Path (24 Scripts)

The largest category! Path scripts provide extensive tools for editing, manipulating, and enhancing vector paths.

**What You Can Do:**
- Modify bezier handles and anchor points
- Create connections between objects
- Apply corner effects and rounding
- Convert dashes to paths
- Trim, split, and extend paths
- Create arrowheads and decorative elements
- Generate triangulated meshes

**Featured Scripts:**

- **Smart Corner Rounder:** Intelligently round corners of paths with customizable radius settings. Works on any path type with precise control.

- **Path Arrowhead Maker:** Add customizable arrowheads to selected paths, choosing shape, size, arrow style, or a document symbol.

- **Metaball Shape Connector:** Create smooth, organic "metaball" connectors between two or more selected circles. Perfect for creating blob-like organic shapes.

- **Triangulator:** Convert selected Illustrator shapes into a low-poly triangulated mesh with adjustable point distribution, colors, and strokes.

- **Smart Connector:** Connect selected objects by drawing lines between centers or anchor points with adjustable amount, stroke, opacity, and randomness.

- **Dash to Paths:** Convert dashed strokes into individual path objects for advanced editing.

- **Path Effects:** Preview and apply a variety of adjustable path distortion effects to your selected paths.

- **Bezier Handle Converter:** Convert bezier handles on selected anchor points by either removing existing handles to create sharp corners or adding smooth handles to create curved transitions.

**Common Use Cases:**
- Creating technical diagrams with connectors
- Designing infographics with arrows and flow lines
- Building low-poly illustrations
- Creating organic, flowing shapes
- Refining path details and curves
- Converting strokes for special effects
- Adding decorative path elements

---

#### Randomize (11 Scripts)

Randomize scripts add controlled chaos to your designs, perfect for creating organic, natural-looking variations.

**What You Can Do:**
- Randomize colors, opacity, and blending modes
- Add random rotation and scaling
- Scatter objects randomly
- Randomize stroke properties and dash patterns
- Add jitter to anchor points
- Randomize text properties

**Featured Scripts:**

- **Random Scatter:** Randomly scatter selected objects by moving them to random positions within customizable horizontal and vertical ranges.

- **Random Point Jitter:** Add random displacement to anchor points for organic effects. Great for creating hand-drawn or natural looks.

- **Random Recolor:** Randomly recolor selected objects with customizable color schemes, adjustable value ranges, and options to recolor text by frames, words, or characters individually.

- **Random Scale:** Randomly scale selected objects with customizable size ranges, adjustable reference points, and options to scale group items or compound path elements individually.

- **Text Color Randomiser:** Apply random colors to selected text frames using RGB, CMYK, or HSL color modes, with options to randomize by text frames, sentences, lines, words, or individual characters.

- **Gradient Rotation Randomizer:** Randomly rotate linear gradients within selected objects using customizable angle ranges.

**Common Use Cases:**
- Creating natural-looking arrangements
- Adding organic variation to patterns
- Designing hand-drawn style illustrations
- Creating dynamic text effects
- Breaking up rigid, mechanical layouts
- Generating unique variations quickly
- Adding visual interest to repetitive elements

---

#### Rename (7 Scripts)

Rename scripts help you organize and manage your document by batch renaming layers, artboards, symbols, and other elements.

**What You Can Do:**
- Batch rename layers with patterns and numbering
- Rename artboards systematically
- Update symbol names in bulk
- Rename swatches and graphic styles
- Convert layer name case formats
- Apply prefixes, suffixes, and sequential numbering

**Featured Scripts:**

- **Layers Batch Renamer:** Rename multiple layers using sequential numbering and custom patterns. Essential for organizing complex documents.

- **Artboards Batch Renamer:** Rename multiple artboards using patterns, numbering, and prefixes. Perfect for multi-page documents.

- **Symbols Batch Renamer:** Rename multiple document symbols simultaneously. Keeps symbol libraries organized.

- **Layer Name Case Converter:** Convert layer names between different case formats (uppercase, lowercase, title case).

- **Items Batch Renamer:** Batch rename selected objects with various naming conventions.

**Common Use Cases:**
- Organizing complex layer structures
- Preparing files for development handoff
- Standardizing naming conventions across projects
- Managing large symbol libraries
- Creating systematic artboard naming for exports
- Cleaning up inherited files with poor naming

---

#### Select (30 Scripts)

The second-largest category! Select scripts provide powerful selection tools that go far beyond Illustrator's native capabilities.

**What You Can Do:**
- Select by color, size, opacity, rotation, and more
- Filter by stroke properties and dash patterns
- Select by font, text size, or text content
- Choose objects by layer order or artboard
- Select random objects or specific percentages
- Find similar objects automatically
- Select by blending mode or attributes

**Featured Scripts:**

- **Smart Selector:** Quickly select Illustrator objects by type, appearance, attributes, and other properties. A powerful all-in-one selection tool.

- **Select by Attribute:** Select objects based on specific attributes like fill color, stroke weight. Highly customizable filtering.

- **Select Similar Objects:** Select all objects similar to the selected one by matching fill/stroke, size, opacity, blending mode, dash pattern, or geometry.

- **Select by Font:** Select text objects using specific fonts or font families. Essential for font management and updates.

- **Select Off-Artboard Objects:** Find and select objects positioned outside artboard boundaries. Great for cleaning up documents.

- **Random Objects Selector:** Randomly select a specified number or percentage of objects. Useful for creating varied effects.

- **Select by Size Match:** Select all objects that match the selected object's size (width, height, or area) within a chosen tolerance.

- **Selection Inspector:** Analyze and display detailed information about current selection.

**Common Use Cases:**
- Finding all objects with specific properties
- Selecting elements for batch modifications
- Cleaning up documents by finding stray objects
- Managing typography across documents
- Creating selection sets for complex operations
- Analyzing document composition
- Preparing objects for specific treatments

---

#### Text (19 Scripts)

Text scripts provide extensive tools for manipulating, formatting, and managing text in your designs.

**What You Can Do:**
- Randomize text properties (size, color, spacing, rotation)
- Generate placeholder text and page numbers
- Split and merge text frames
- Create bulleted lists
- Add sequential numbering
- Swap text content between frames
- Fine-tune typography with advanced controls

**Featured Scripts:**

- **Sequential Text Numbering:** Automatically add sequential numbers, letters (A-Z), or Roman numerals to selected text frames. Perfect for numbered lists or page elements.

- **Text Splitter:** Split selected text frames into separate lines, words, or characters. Essential for creating animated text or individual text elements.

- **Placeholder Text Generator:** Generate customizable placeholder text wireframes—set lines, words, height, spacing, corner radius, alignment, and color.

- **Multi-Text Editor:** Edit multiple text objects simultaneously with batch operations. Saves time when updating repeated text.

- **Type Randomizer:** Randomize font size, leading, tracking, scale, baseline shift, and rotation on selected text with adjustable ranges per character, word, line, or entire text frame.

- **Text Frame Merger:** Merge multiple selected text frames into a single text frame.

- **Page Number Generator:** Automatically generate page numbers across multiple artboards in your document.

**Common Use Cases:**
- Creating dynamic text effects
- Building wireframes and mockups
- Managing multi-page documents
- Creating kinetic typography
- Batch updating text properties
- Generating numbered lists and sequences
- Fine-tuning typography across selections

---

#### Transform (10 Scripts)

Transform scripts provide advanced transformation capabilities beyond Illustrator's standard transform tools.

**What You Can Do:**
- Scale objects to exact dimensions
- Adjust aspect ratios precisely
- Create isometric projections
- Apply progressive transformations
- Create glitch and slice effects
- Modify stroke weights proportionally
- Apply zig-zag effects to paths

**Featured Scripts:**

- **Smart Scale:** Resize selected objects to exact dimensions, add/subtract values, or scale by percentage. More flexible than native scaling.

- **Progressive Transform:** Progressively transform multiple selected objects relative to a chosen reference point—scaling, rotating, moving, and adjusting opacity/stroke with live preview and optional randomness.

- **Isometrify:** Convert flat objects to isometric perspective with customizable angles. Perfect for creating isometric illustrations and diagrams.

- **Path Glitcher:** Create a glitch effect by slicing the selected paths into adjustable horizontal/vertical fragments and randomly offsetting them.

- **Object Slicer:** Split the selected object into customizable angled slices with randomizable widths and offsets.

- **Aspect Ratio Tweaker:** Adjust the aspect ratio of selected objects while keeping either width or height fixed.

- **Adjust Stroke Weight by Percentage:** Modify stroke weights by percentage values while maintaining proportions.

**Common Use Cases:**
- Creating precise technical drawings
- Building isometric illustrations
- Designing progressive patterns and sequences
- Creating glitch art and digital effects
- Adjusting designs to specific dimensions
- Creating sliced and fragmented effects
- Maintaining proportions during scaling

---

#### Utility (18 Scripts)

Utility scripts include miscellaneous productivity tools that don't fit neatly into other categories but are incredibly useful.

**What You Can Do:**
- Manage multiple open documents
- Create custom grids and layouts
- Copy objects as PNG images
- Transfer symbols and layers between documents
- Count and analyze objects
- Add labels and annotations
- Manage tasks and notes
- Access scripts folder quickly

**Featured Scripts:**

- **Grid Generator:** Generate customizable artboard-aligned grids (standard, column, baseline, modular, isometric, hex, or dot) with controls for size, cell spacing, color, stroke, opacity, margins, and more.

- **Copy as PNG:** Copy selected objects to the clipboard as a PNG with configurable scale, background (transparent/white/black), margin, and anti-aliasing.

- **Objects Counter:** Count and analyze selected objects with detailed statistics and reporting. Great for inventory and documentation.

- **Cross-Document Layer Duplicator:** Copy selected layers (and their contents) from one document to one or more open documents, preserving structure, order, and positions, with optional name prefix/suffix.

- **Symbol Transfer:** Copy selected symbols from one open document to one or more other open documents with search and filtering capabilities.

- **Sequential Object Labeler:** Quickly add sequential number labels to selected objects with customizable text styling, offsets, and optional frames.

- **Documents Saver:** View, filter, and selectively close multiple open documents with options to save or discard changes.

- **Calculator:** Built-in calculator for design measurements and calculations.

**Common Use Cases:**
- Creating layout grids for design systems
- Sharing assets between documents
- Exporting quick previews
- Managing complex multi-document projects
- Documenting designs with labels
- Organizing workspace and files
- Performing design calculations
- Tracking project tasks

---

### Tips for Using Scripts Effectively

**Start Simple:**
- Begin with straightforward scripts like "Swap Two Objects" or "Calculator"
- Gradually explore more complex tools as you become comfortable
- Read descriptions before trying unfamiliar scripts

**Combine Scripts:**
- Many workflows benefit from using multiple scripts in sequence
- Example: Use "Select by Color" then "Random Scatter" for varied layouts
- Example: Use "Grid Arranger" then "Color Randomizer" for colorful patterns

**Use Favorites:**
- Add your most-used scripts to Favorites for instant access
- Build custom collections for specific project types
- Organize favorites by workflow rather than category

**Experiment Safely:**
- Always save before trying destructive operations
- Test on duplicated objects first
- Use Cmd/Ctrl+Z to undo unwanted results

**Learn Gradually:**
- Focus on one category at a time
- Master a few scripts before moving to the next category
- Revisit categories as your skills grow—you'll discover new uses

With over 200 scripts at your fingertips, ScriptBox transforms Adobe Illustrator into an even more powerful design tool. Take time to explore, experiment, and discover which scripts best fit your unique workflow.

---

## 4. External Scripts

The External Scripts tab allows you to extend ScriptBox beyond its built-in library by adding your own custom scripts or third-party script collections. This powerful feature lets you integrate personal automation tools, team-shared scripts, or community-developed utilities directly into your ScriptBox workflow.

**Why Use External Scripts?**

- **Expand Your Toolkit:** Add unlimited custom scripts without modifying ScriptBox's core library
- **Team Collaboration:** Share script collections across your team by pointing to a shared folder
- **Personal Automation:** Keep your custom workflow scripts separate from built-in tools
- **Third-Party Integration:** Use scripts from the Illustrator community or marketplace
- **Organized Workflow:** Maintain different script collections for different projects or clients

The External Scripts tab works just like the Toolbox tab—browse folders, search for scripts, and run them with a single click. The key difference is that you control what scripts appear here by choosing which folder to load.

### Adding Custom Script Folders

To use external scripts, you first need to tell ScriptBox where your custom scripts are located. ScriptBox can load any folder containing .jsx, .js, or .jsfl script files.

**Method 1: Using the Folder Button**

1. **Open the External Scripts Tab**
   - Click the External Scripts tab icon (folder icon) at the top of the ScriptBox panel
   - You'll see a drop hint message if no folder is currently set

2. **Click the Folder Button**
   - Look for the folder icon button in the top-right corner of the search bar
   - Click this button to open a folder selection dialog

3. **Select Your Scripts Folder**
   - Navigate to the folder containing your custom scripts
   - Select the folder (not individual files)
   - Click "Select Folder" or "Choose" to confirm

4. **Scripts Load Automatically**
   - ScriptBox immediately scans the selected folder
   - All .jsx, .js, and .jsfl files are detected and listed
   - Subfolders are displayed as collapsible categories
   - Your scripts are now ready to use

**Method 2: Drag and Drop**

For even faster setup, you can drag a folder directly into the External Scripts tab:

1. **Open the External Scripts Tab**
   - Click the External Scripts tab icon

2. **Locate Your Scripts Folder**
   - Open your file system (Finder on Mac, File Explorer on Windows)
   - Navigate to the folder containing your scripts

3. **Drag the Folder**
   - Click and hold on the folder
   - Drag it over the ScriptBox panel
   - Drop it anywhere in the External Scripts tab area

4. **Folder Loads Instantly**
   - ScriptBox automatically sets this as your external scripts folder
   - All scripts are loaded and displayed immediately

**What Happens After Adding a Folder:**

- **Folder Structure Preserved:** Subfolders in your scripts folder appear as collapsible categories in ScriptBox
- **Automatic Organization:** Scripts are automatically organized by their folder structure
- **Folder Name Displayed:** The main folder name appears at the top of the scripts list
- **Persistent Setting:** Your folder path is saved—you don't need to set it again each time you open Illustrator
- **Search Enabled:** You can immediately search through your external scripts
- **Favorites Compatible:** External scripts can be added to your Favorites tab

**Supported File Types:**

ScriptBox recognizes and loads the following script file types:
- **.jsx** - ExtendScript files (most common for Illustrator scripts)
- **.js** - JavaScript files
- **.jsfl** - Flash/Animate script files (if compatible with Illustrator)

**Folder Organization Tips:**

- **Use Subfolders:** Organize scripts into subfolders by category (e.g., "Text Tools", "Color Scripts", "Path Utilities")
- **Clear Naming:** Use descriptive folder and file names for easy identification
- **Remove Extensions:** ScriptBox automatically removes file extensions from display names
- **Consistent Structure:** Maintain a consistent folder structure across projects or team members

**Example Folder Structure:**

```
My Custom Scripts/
├── Text Tools/
│   ├── Advanced Text Formatter.jsx
│   ├── Text Case Converter.jsx
│   └── Find and Replace Plus.jsx
├── Color Utilities/
│   ├── Color Harmony Generator.jsx
│   └── Palette Exporter.jsx
└── Path Tools/
    ├── Advanced Path Cleaner.jsx
    └── Curve Smoother.jsx
```

This structure would appear in ScriptBox with "My Custom Scripts" as the main folder, containing three collapsible subfolders (Text Tools, Color Utilities, Path Tools), each with their respective scripts.

### Managing External Scripts

Once you've added a custom scripts folder, ScriptBox provides several tools for managing and working with your external scripts.

**Browsing External Scripts**

The External Scripts tab functions similarly to the Toolbox tab:

1. **View Your Scripts**
   - The main folder name appears at the top
   - Subfolders are displayed as collapsible categories
   - Individual scripts are listed within their folders

2. **Expand and Collapse Folders**
   - Click any folder name to expand and see its contents
   - Click again to collapse and hide the scripts
   - Multiple folders can be expanded simultaneously

3. **View Modes**
   - External Scripts supports List View and Compact View
   - The view mode syncs with your Toolbox view preference
   - Switch between views using the Toolbox tab's view toggle
   - Grid view is not available for External Scripts

**Running External Scripts**

Running external scripts works exactly like running built-in scripts:

1. **Click to Run**
   - Simply click any script name to execute it
   - The script runs immediately in Adobe Illustrator
   - Follow any on-screen prompts or dialogs

2. **Script Behavior**
   - Scripts may open dialog boxes with options
   - Some scripts execute instantly without dialogs
   - Selection-based scripts work on currently selected objects
   - Results depend on the individual script's functionality

**Searching External Scripts**

The search functionality helps you quickly find specific scripts in large collections:

1. **Use the Search Bar**
   - Type any part of a script name in the search field at the top
   - Results filter in real-time as you type
   - Search is case-insensitive

2. **Search Behavior**
   - Only matching scripts are displayed
   - Folders containing matches remain visible
   - Non-matching items are hidden
   - Clear the search to see all scripts again

3. **Search Tips**
   - Search works across all subfolders
   - Partial words work (e.g., "text" finds "Text Formatter")
   - Faster than manually browsing through folders

**Adding External Scripts to Favorites**

External scripts can be added to your Favorites tab for even quicker access:

1. **Hover Over a Script**
   - Move your mouse over any external script
   - A star icon (favorite icon) appears on the right

2. **Click the Star Icon**
   - Click the star to add the script to Favorites
   - The script is now accessible from the Favorites tab
   - External scripts in Favorites show a placeholder icon

3. **Access from Favorites**
   - Switch to the Favorites tab to see all your favorite scripts
   - External scripts appear alongside built-in scripts and panels
   - Click to run directly from Favorites

**Refreshing the Scripts Folder**

If you add, remove, or modify scripts in your external folder while ScriptBox is open, use the Refresh button to update the list:

1. **Locate the Refresh Button**
   - Look at the bottom of the External Scripts tab
   - The Refresh button shows a circular arrow icon

2. **Click Refresh**
   - Click the Refresh button
   - ScriptBox rescans your external scripts folder
   - The scripts list updates to reflect any changes

3. **When to Refresh**
   - After adding new scripts to your folder
   - After removing scripts from your folder
   - After renaming scripts or folders
   - After reorganizing your folder structure
   - If scripts don't appear as expected

**Removing Individual Scripts from the List**

You can temporarily hide specific scripts from the External Scripts list without deleting them from your folder:

1. **Hover Over a Script**
   - Move your mouse over the script you want to hide
   - A close icon (X) appears on the right side

2. **Click the Close Icon**
   - Click the X icon
   - The script is removed from the ScriptBox list
   - The script file remains in your folder (not deleted)

3. **Restore Hidden Scripts**
   - Click the Refresh button to restore all hidden scripts
   - Or remove and re-add the entire folder
   - Hidden scripts reappear in the list

**Managing Multiple Script Sources**

While ScriptBox supports one external scripts folder at a time, you can manage multiple script collections:

**Switching Between Folders:**

1. **Remove Current Folder**
   - Click the X icon next to the main folder name at the top
   - Or click the "Remove" button at the bottom

2. **Add Different Folder**
   - Use the folder button or drag-and-drop method
   - Select a different scripts folder
   - The new folder's scripts replace the previous list

**Organizing Multiple Collections:**

- **Master Folder Approach:** Create a master folder with subfolders for different collections
  ```
  All My Scripts/
  ├── Personal Scripts/
  ├── Team Scripts/
  ├── Client A Scripts/
  └── Community Scripts/
  ```
  Point ScriptBox to "All My Scripts" to access everything at once

- **Project-Based Switching:** Keep separate folders for different projects and switch between them as needed

- **Symbolic Links:** Use symbolic links (shortcuts) to combine multiple script locations into one folder that ScriptBox can read

**Best Practices for Managing External Scripts:**

- **Regular Backups:** Keep backups of your custom scripts folder
- **Version Control:** Consider using Git or similar tools for script version management
- **Documentation:** Include README files in your script folders to document what each script does
- **Testing:** Test new scripts on non-critical documents before using them in production
- **Organization:** Maintain a clear folder structure for easy navigation
- **Naming Conventions:** Use consistent, descriptive names for scripts and folders

### Removing Scripts

ScriptBox provides two levels of script removal: removing individual scripts from the list or removing the entire external scripts folder.

**Removing Individual Scripts**

To temporarily hide specific scripts without deleting them from your computer:

1. **Locate the Script**
   - Browse or search for the script you want to remove
   - The script must be visible in the list

2. **Hover Over the Script**
   - Move your mouse over the script name
   - A close icon (X) appears on the right side of the script

3. **Click the Close Icon**
   - Click the X icon
   - The script immediately disappears from the ScriptBox list

4. **What Happens:**
   - The script is hidden from ScriptBox's interface
   - The actual script file remains in your folder (not deleted)
   - The script is added to a "removed scripts" list
   - The script won't appear even after refreshing

5. **Restore Individual Scripts:**
   - To restore a hidden script, you must remove and re-add the entire folder
   - Or manually edit the removed scripts list (advanced users only)
   - The Refresh button alone won't restore individually removed scripts

**When to Remove Individual Scripts:**

- Scripts you don't use but want to keep in your folder
- Duplicate scripts with similar functionality
- Scripts that aren't compatible with your Illustrator version
- Experimental scripts you're not ready to delete permanently
- Scripts that clutter your list but might be useful later

**Removing the External Scripts Folder**

To completely disconnect your external scripts folder from ScriptBox:

**Method 1: Using the Folder Name Close Icon**

1. **Locate the Main Folder Name**
   - Look at the top of the External Scripts list
   - You'll see your main folder name with an X icon next to it

2. **Click the X Icon**
   - Click the X icon next to the folder name
   - A confirmation may appear (depending on your version)

3. **Folder Removed**
   - All external scripts disappear from the list
   - The drop hint message reappears
   - Your folder path is cleared from ScriptBox

**Method 2: Using the Remove Button**

1. **Locate the Remove Button**
   - Scroll to the bottom of the External Scripts tab
   - Look for the "Remove" button with an X icon

2. **Click Remove**
   - Click the "Remove" button
   - The external scripts folder is disconnected

3. **Folder Removed**
   - All scripts are cleared from the interface
   - The tab returns to its initial state

**What Happens When You Remove the Folder:**

- **Scripts Cleared:** All external scripts disappear from the ScriptBox interface
- **Favorites Updated:** External scripts are automatically removed from your Favorites tab
- **Files Untouched:** Your actual script files and folders remain on your computer (nothing is deleted)
- **Settings Cleared:** The folder path is removed from ScriptBox's settings
- **Removed Scripts List Cleared:** The list of individually removed scripts is reset
- **Ready for New Folder:** You can immediately add a different folder if desired

**After Removing the Folder:**

- The External Scripts tab shows the drop hint message again
- The Refresh button becomes disabled (grayed out)
- The Remove button becomes disabled
- You can add a new folder using the folder button or drag-and-drop

**Re-adding the Same Folder:**

If you remove a folder and later re-add it:
- All scripts reappear in the list
- Previously hidden individual scripts reappear (the removed scripts list was cleared)
- You'll need to hide unwanted scripts again if desired
- Favorites must be re-added manually

**Important Notes:**

- **No File Deletion:** Removing scripts or folders in ScriptBox never deletes files from your computer
- **Safe Operation:** You can safely remove and re-add folders without risk of data loss
- **Favorites Impact:** Removing the external scripts folder removes those scripts from Favorites
- **No Undo:** There's no undo button, but you can simply re-add the folder to restore the list

**Troubleshooting Script Removal:**

- **Script Won't Remove:** Ensure you're clicking the correct close icon (individual script, not folder)
- **Folder Won't Remove:** Try using the Remove button at the bottom instead of the folder name icon
- **Scripts Reappear:** If you only want to hide scripts temporarily, use individual script removal, not the Refresh button
- **Favorites Not Updating:** Manually remove external scripts from Favorites if they don't clear automatically

---

## 5. Code Editor

The Code Editor tab transforms ScriptBox into a powerful development environment, allowing you to write, test, and run custom JSX scripts directly within Adobe Illustrator. Whether you're prototyping new automation ideas, testing code snippets, or running scripts from online resources, the Code Editor provides everything you need without leaving your workspace.

### Accessing the Code Editor

Getting to the Code Editor is simple:

1. **Click the Code Editor Tab**
   - Look for the code icon (</>) in the tab navigation at the top of the ScriptBox panel
   - It's the 5th tab from the left
   - Click once to switch to the Code Editor view

2. **First-Time Initialization**
   - The first time you open the Code Editor, it may take a moment to initialize
   - The ACE editor library loads and configures itself automatically
   - Once loaded, the editor is ready for immediate use

3. **Editor Interface**
   - The editor appears with syntax highlighting enabled
   - A default "hello world" example is pre-loaded to help you get started
   - Control buttons appear below the editor for running, saving, and managing your code

### Editor Interface Elements

The Code Editor interface consists of several key components designed for efficient script development:

**Script URL Input Field**
- Located at the top of the Code Editor tab
- Allows you to paste URLs to remote scripts
- Includes a clear button (×) that appears when text is entered
- Perfect for loading scripts from GitHub, Gists, or other online sources

**Code Editor Area**
- Large text editing area with syntax highlighting
- Supports JavaScript/JSX syntax with color-coded elements
- Line numbers displayed on the left for easy reference
- Auto-indentation and code formatting assistance
- Resizes automatically when you resize the ScriptBox panel

**Editor Control Buttons**

Four essential buttons below the editor provide core functionality:

1. **Run Button** (Play icon)
   - Executes the code currently in the editor
   - If the editor is empty, attempts to load and run code from the URL field
   - Keyboard shortcut: Cmd+Enter (Mac) or Ctrl+Enter (Windows)

2. **Clear Button** (Delete icon)
   - Clears all code from the editor
   - Resets to a clean slate with just a comment: `// js input`
   - Useful for starting fresh without manually selecting and deleting

3. **Open Button** (File icon)
   - Opens a file browser to select a .jsx or .js file from your computer
   - Loads the selected file's content into the editor
   - Perfect for editing existing scripts or loading templates

4. **Save Button** (Download icon)
   - Saves the current editor content as a .jsx file
   - Opens a save dialog where you can choose the filename and location
   - Automatically adds .jsx extension if not specified

**Syntax Highlighting Features**

The editor provides professional-grade syntax highlighting:

- **Keywords:** JavaScript keywords (var, function, if, for, etc.) are highlighted
- **Strings:** Text in quotes appears in a distinct color
- **Comments:** Single-line (//) and multi-line (/* */) comments are clearly marked
- **Numbers:** Numeric values are color-coded
- **Functions:** Function names and calls are visually distinguished
- **Operators:** Mathematical and logical operators are highlighted
- **Theme Adaptation:** Syntax colors automatically adjust to match your Illustrator theme (light or dark)

**Additional Features**

- **Auto-completion:** Basic code completion suggestions as you type
- **Bracket Matching:** Automatically highlights matching brackets and parentheses
- **Smart Indentation:** Automatically indents code based on context
- **Soft Tabs:** Uses spaces instead of tabs for consistent formatting (2 spaces per indent)
- **Word Wrap:** Long lines wrap to fit the editor width
- **Undo/Redo:** Full undo/redo support with Cmd/Ctrl+Z and Cmd/Ctrl+Shift+Z

### Writing Custom JSX Scripts

The Code Editor is your workspace for creating custom automation scripts using Adobe's ExtendScript (JSX) language.

**Getting Started with JSX**

1. **Clear the Editor**
   - Click the Clear button to start with a blank slate
   - Or select all existing code and delete it

2. **Write Your Script**
   - Type or paste your JSX code into the editor
   - Use standard JavaScript syntax with Illustrator's DOM objects
   - Access Illustrator objects through the `app` object

3. **Basic Script Structure**

```javascript
// Access the active document
var doc = app.activeDocument;

// Work with selections
if (doc.selection.length > 0) {
    var selectedItem = doc.selection[0];
    // Manipulate the selected item
    selectedItem.fillColor = doc.swatches[0].color;
}

// Create new objects
var rect = doc.pathItems.rectangle(100, 100, 200, 150);
```

**Common JSX Patterns**

**Working with Selections:**
```javascript
// Check if anything is selected
if (app.activeDocument.selection.length > 0) {
    // Loop through selected items
    for (var i = 0; i < app.activeDocument.selection.length; i++) {
        var item = app.activeDocument.selection[i];
        // Do something with each item
    }
}
```

**Creating Shapes:**
```javascript
var doc = app.activeDocument;
// Create a rectangle (top, left, width, height)
var rect = doc.pathItems.rectangle(100, 100, 200, 150);

// Create an ellipse (top, left, width, height)
var circle = doc.pathItems.ellipse(100, 100, 100, 100);
```

**Modifying Colors:**
```javascript
var item = app.activeDocument.selection[0];
var newColor = new RGBColor();
newColor.red = 255;
newColor.green = 0;
newColor.blue = 0;
item.fillColor = newColor;
```

**Tips for Writing Scripts**

- **Test Incrementally:** Run your script frequently to catch errors early
- **Use Comments:** Document your code with comments for future reference
- **Save Your Work:** Save useful scripts as .jsx files for reuse
- **Check Selection:** Always verify that objects are selected before manipulating them
- **Handle Errors:** Use try-catch blocks for robust error handling
- **Start Simple:** Begin with basic operations and build complexity gradually

**Learning Resources**

- Adobe Illustrator Scripting Guide (official documentation)
- ExtendScript Toolkit documentation
- Online JSX script repositories and forums
- Built-in ScriptBox scripts (examine them for examples)

### Running Code

Executing your scripts is straightforward with multiple options available.

**Running Scripts from the Editor**

1. **Using the Run Button**
   - Write or paste your code in the editor
   - Click the Run button (play icon) below the editor
   - The script executes immediately in Adobe Illustrator
   - Results appear in your document or as dialogs (depending on the script)

2. **Using Keyboard Shortcut**
   - Press Cmd+Enter (Mac) or Ctrl+Enter (Windows)
   - Faster than clicking for frequent testing
   - Works from anywhere within the editor

3. **Execution Feedback**
   - The script runs in the Illustrator environment
   - Any alerts or prompts defined in your script will appear
   - Check your document for visual changes
   - Console messages appear in the output area (if debug mode is enabled)

**Running Scripts from URLs**

If the editor is empty or contains only the placeholder comment, clicking Run will attempt to load and execute code from the URL field:

1. Paste a script URL in the URL input field at the top
2. Leave the editor empty or clear it
3. Click the Run button
4. The script loads from the URL and executes automatically

**What Happens When You Run Code**

- **Code Validation:** The editor checks for basic syntax errors
- **Execution:** Code is sent to Illustrator's ExtendScript engine
- **Document Changes:** Any modifications to your document take effect immediately
- **Undo Support:** You can undo script actions with Cmd/Ctrl+Z
- **Error Handling:** Syntax errors or runtime errors display as alerts

**Execution Tips**

- **Save Before Running:** Always save your document before running untested scripts
- **Test on Copies:** Test destructive operations on duplicated objects first
- **Check Requirements:** Ensure required objects are selected or available
- **Read Error Messages:** Error alerts provide clues about what went wrong
- **Iterative Testing:** Make small changes and test frequently

**Common Execution Scenarios**

- **Selection-Based Scripts:** Select objects first, then run the script
- **Document-Wide Scripts:** No selection needed; script affects entire document
- **Generator Scripts:** Create new objects without requiring selection
- **Utility Scripts:** Perform calculations or display information
- **Batch Operations:** Process multiple objects or artboards automatically

### Loading Scripts from URLs

The Code Editor can load scripts directly from the internet, making it easy to run scripts shared online or stored in cloud repositories.

**How to Load Scripts from URLs**

1. **Find a Script URL**
   - Locate a JSX script hosted online (GitHub, Gist, personal website, etc.)
   - Copy the direct URL to the raw script file
   - For GitHub: Click "Raw" button to get the raw file URL

2. **Paste the URL**
   - Click in the URL input field at the top of the Code Editor
   - Paste the script URL (Cmd/Ctrl+V)
   - The URL appears in the input field

3. **Load and Run**
   - Click the "Run script from pasted link" button (play icon next to URL field)
   - Or click the Run button below the editor if the editor is empty
   - The script downloads, loads into the editor, and executes automatically

**What Happens When Loading from URL**

1. **Download:** ScriptBox fetches the script content from the URL
2. **Load to Editor:** The script code appears in the Code Editor
3. **Execute:** The script runs immediately in Illustrator
4. **Available for Editing:** The loaded code remains in the editor for modification or re-running

**Supported URL Types**

- **GitHub Raw URLs:** `https://raw.githubusercontent.com/user/repo/main/script.jsx`
- **GitHub Gist URLs:** `https://gist.githubusercontent.com/user/id/raw/script.jsx`
- **Direct File URLs:** Any publicly accessible .jsx or .js file
- **HTTP/HTTPS:** Both protocols are supported

**URL Loading Tips**

- **Use Raw URLs:** For GitHub, always use the "Raw" file URL, not the page URL
- **Check Accessibility:** Ensure the URL is publicly accessible (no authentication required)
- **Verify Content:** The URL should point directly to a script file, not an HTML page
- **Clear URL Field:** Use the × button to clear the URL after loading
- **Save Useful Scripts:** After loading, save scripts you want to keep locally

**Example URLs**

Valid URL format:
```
https://raw.githubusercontent.com/username/repository/main/scripts/my-script.jsx
```

Invalid URL format (GitHub page, not raw file):
```
https://github.com/username/repository/blob/main/scripts/my-script.jsx
```

**Troubleshooting URL Loading**

- **Failed to Load:** Check that the URL is correct and publicly accessible
- **Wrong Content:** Ensure the URL points to a raw script file, not an HTML page
- **CORS Errors:** Some servers may block cross-origin requests
- **Network Issues:** Verify your internet connection is active

**Use Cases for URL Loading**

- **Quick Testing:** Try scripts from online tutorials without downloading
- **Shared Scripts:** Run scripts shared by colleagues via URL
- **Script Libraries:** Access your personal script library stored in cloud repositories
- **Community Scripts:** Test scripts from forums or community resources
- **Version Control:** Always run the latest version from your Git repository

### Opening Existing Script Files

Load scripts from your local file system to edit or run them in the Code Editor.

**How to Open Script Files**

1. **Click the Open Button**
   - Look for the Open button (file icon) below the editor
   - Click once to open the file browser

2. **Select Your Script**
   - A file selection dialog appears
   - Navigate to the folder containing your script
   - Select a .jsx or .js file
   - Click "Open" or "Select"

3. **File Loads into Editor**
   - The script content appears in the Code Editor
   - Previous content is replaced
   - The file is ready to edit or run

**Supported File Types**

- **.jsx files:** Adobe ExtendScript files (primary format)
- **.js files:** Standard JavaScript files
- **Text-based:** Any text file containing JavaScript code

**What You Can Do After Opening**

- **Edit the Code:** Modify the script as needed
- **Run the Script:** Execute it immediately with the Run button
- **Save Changes:** Save the modified version with a new name
- **Test Variations:** Experiment with different parameters or logic

**Opening Files Tips**

- **Organize Your Scripts:** Keep scripts in a dedicated folder for easy access
- **Use Descriptive Names:** Name files clearly to identify their purpose
- **Backup Important Scripts:** Keep copies of valuable scripts
- **Version Your Scripts:** Use version numbers in filenames (e.g., script-v2.jsx)

**Common Workflows**

**Editing Existing Scripts:**
1. Open the script file
2. Make your modifications in the editor
3. Test by running the script
4. Save with a new name or overwrite the original

**Creating Script Templates:**
1. Open a template script
2. Customize for your specific needs
3. Save as a new file with a descriptive name
4. Reuse the template for similar tasks

**Debugging Scripts:**
1. Open the problematic script
2. Add console.log() statements or alerts
3. Run and observe the output
4. Fix issues and test again

### Saving Scripts as .jsx Files

Preserve your custom scripts by saving them as .jsx files for future use.

**How to Save Scripts**

1. **Write or Edit Your Code**
   - Ensure your script is complete and tested
   - The editor should contain the code you want to save

2. **Click the Save Button**
   - Look for the Save button (download icon) below the editor
   - Click once to initiate the save process

3. **Choose Save Location**
   - A save dialog appears
   - Navigate to your desired save location
   - Enter a filename (e.g., "my-custom-script")
   - The .jsx extension is added automatically if not specified

4. **Confirm Save**
   - Click "Save" in the dialog
   - The file is saved to your chosen location
   - A confirmation message appears

**Save Behavior**

- **CEP Environment:** Uses native file save dialog (recommended)
- **Fallback Methods:** If the dialog fails, attempts browser download
- **Clipboard Fallback:** As a last resort, copies code to clipboard
- **Automatic Extension:** Adds .jsx extension if you don't specify one

**Saving Best Practices**

**Organize Your Scripts:**
- Create a dedicated folder for custom scripts (e.g., "My Illustrator Scripts")
- Use subfolders to categorize scripts by function
- Keep related scripts together

**Naming Conventions:**
- Use descriptive names that explain what the script does
- Include version numbers for scripts you update frequently
- Use hyphens or underscores instead of spaces
- Examples: `batch-resize-v2.jsx`, `color_randomizer_custom.jsx`

**Version Control:**
- Save new versions with incremented numbers
- Keep old versions until the new one is thoroughly tested
- Document changes in comments at the top of the file

**Documentation:**
- Add comments at the top explaining what the script does
- Include usage instructions
- Note any requirements (selection needed, specific object types, etc.)
- Add your name and date for reference

**Example Script Header:**
```javascript
/**
 * Custom Color Randomizer
 * Author: Your Name
 * Date: October 2025
 * Description: Applies random colors from document swatches to selected objects
 * Requirements: At least one object must be selected
 * Usage: Select objects, then run this script
 */
```

**What to Save**

- **Working Scripts:** Save any script that works correctly
- **Templates:** Save script templates for common tasks
- **Experiments:** Save interesting experiments even if incomplete
- **Snippets:** Save useful code snippets for future reference
- **Modified Built-ins:** Save customized versions of built-in scripts

**Reusing Saved Scripts**

After saving, you can:
- Open the script again using the Open button
- Add the script folder to External Scripts for easy access
- Share the script file with colleagues
- Store scripts in version control (Git)
- Build a personal script library over time

### Clearing the Editor

Reset the Code Editor to start fresh with a clean slate.

**How to Clear the Editor**

1. **Click the Clear Button**
   - Look for the Clear button (delete icon) below the editor
   - Click once to clear all content

2. **Editor Resets**
   - All code is removed from the editor
   - A simple comment placeholder appears: `// js input`
   - The cursor is positioned at the start
   - Ready for new code

**When to Clear the Editor**

- **Starting a New Script:** Begin with a blank canvas
- **After Testing:** Clear test code before writing production scripts
- **Removing Examples:** Clear the default example to start fresh
- **Quick Reset:** Faster than manually selecting and deleting all code

**Alternative Clearing Methods**

- **Manual Selection:** Select all (Cmd/Ctrl+A) and delete
- **Open New File:** Opening a file replaces existing content
- **Load from URL:** Loading a URL replaces existing content

**Clear vs. Save**

- **Clear:** Removes content without saving (cannot be undone)
- **Save First:** If you want to keep the current code, save before clearing
- **No Confirmation:** Clear happens immediately without confirmation dialog

**Tips**

- **Save Important Code:** Always save valuable scripts before clearing
- **Use Undo:** If you accidentally clear, use Cmd/Ctrl+Z immediately
- **Quick Workflow:** Clear → Write → Test → Save → Clear → Repeat

### Drag and Drop Functionality

The Code Editor supports drag and drop for .jsx and .js files, making it even easier to load scripts.

**How to Use Drag and Drop**

1. **Locate Your Script File**
   - Find the .jsx or .js file in your file system
   - Open Finder (Mac) or File Explorer (Windows)

2. **Drag the File**
   - Click and hold the file
   - Drag it over the ScriptBox panel
   - Drop it onto the Code Editor area

3. **File Loads Automatically**
   - The script content appears in the editor
   - Previous content is replaced
   - Ready to edit or run

**Supported File Types for Drag and Drop**

- .jsx files (Adobe ExtendScript)
- .js files (JavaScript)

This feature provides the fastest way to load local scripts into the editor without using the Open button or file dialogs.

---

---

## 6. Panels Manager

The Panels Manager tab provides instant access to all Adobe Illustrator panels with a single click. Instead of navigating through the Window menu repeatedly, you can browse, search, and open any Illustrator panel directly from ScriptBox. This feature dramatically speeds up your workflow by eliminating the need to hunt through menus for the panels you need.

### Opening Panels

The Panels Manager gives you quick access to every native Adobe Illustrator panel, from commonly used ones like Layers and Swatches to specialized panels like Flattener Preview and SVG Interactivity.

**Browsing Available Panels:**

When you open the Panels Manager tab, you'll see a comprehensive list of all available Illustrator panels:

1. **View All Panels**
   - The Panels Manager displays every native Illustrator panel
   - Panels are listed alphabetically for easy browsing
   - Each panel shows its name and an icon
   - The list includes both common and specialized panels

2. **Panel Categories**
   
   The Panels Manager includes all Illustrator panels across various categories:
   
   - **Essential Panels:** Layers, Swatches, Color, Stroke, Gradient, Transparency
   - **Typography Panels:** Character, Paragraph, Glyphs, OpenType, Tabs
   - **Object Panels:** Align, Pathfinder, Transform, Appearance, Graphic Styles
   - **Color Management:** Color Guide, Kuler (Adobe Color Themes), Recolor Artwork
   - **Symbols & Libraries:** Symbols, Brushes, Swatches, Graphic Styles, CC Libraries
   - **Document Panels:** Artboards, Links, Document Info, Attributes
   - **Advanced Panels:** Flattener Preview, Separations Preview, SVG Interactivity
   - **Workflow Panels:** Actions, Navigator, Info, Asset Export

3. **View Modes**
   
   Like other ScriptBox tabs, the Panels Manager supports multiple view modes:
   
   - **List View:** Displays panels in a vertical list with full names and icons
   - **Compact View:** Shows more panels on screen with reduced spacing
   - **Grid View:** Displays panels as a grid of icons with labels
   
   Switch between view modes using the view toggle icons in the top-right corner of the tab.

**The Click-to-Open Mechanism:**

Opening panels is incredibly simple—just one click and the panel appears in your Illustrator workspace:

1. **Locate the Panel You Need**
   - Browse through the alphabetical list
   - Or use the search function (see Searching Panels below)

2. **Click the Panel Name**
   - Simply click once on any panel name or icon
   - The panel opens immediately in Adobe Illustrator
   - No need to navigate through Window menus

3. **Panel Behavior**
   - If the panel is already open, clicking it brings it to the front
   - If the panel is closed, clicking it opens it in your workspace
   - Panels open in their last-used position and size
   - Panels can be docked or left floating as you prefer

4. **Multiple Panels**
   - Open as many panels as you need
   - Click multiple panels in succession to open them all
   - Arrange panels in your workspace as desired
   - ScriptBox remains accessible while panels are open

**Common Panels and Their Uses:**

Here are some of the most frequently accessed panels available through the Panels Manager:

- **Layers:** Manage layer hierarchy, visibility, and locking
- **Swatches:** Access and manage color swatches and patterns
- **Color:** Adjust fill and stroke colors with various color models
- **Pathfinder:** Combine shapes using boolean operations
- **Align:** Align and distribute objects precisely
- **Transform:** View and modify object transformations numerically
- **Appearance:** Manage multiple fills, strokes, and effects
- **Stroke:** Customize stroke weight, caps, joins, and dashes
- **Gradient:** Create and edit gradient fills
- **Transparency:** Adjust opacity and blending modes
- **Character/Paragraph:** Format text with precise typography controls
- **Artboards:** Manage multiple artboards in your document
- **Symbols:** Create and manage reusable symbol instances
- **Brushes:** Access and customize brush libraries
- **Graphic Styles:** Apply and manage saved appearance styles

**Benefits of Using Panels Manager:**

- **Speed:** Open panels with one click instead of navigating menus
- **Discovery:** Browse all available panels to discover ones you didn't know existed
- **Efficiency:** Combine with Favorites for instant access to your most-used panels
- **Workflow:** Keep ScriptBox open and access panels without interrupting your flow
- **Consistency:** Always know where to find any panel, regardless of Illustrator version

### Searching Panels

When you know which panel you need, the search function helps you find it instantly without scrolling through the entire list.

**How to Search for Panels:**

1. **Locate the Search Bar**
   - The search field appears at the top of the Panels Manager tab
   - Look for the text input field with a search icon or placeholder text

2. **Enter Your Search Term**
   - Start typing any part of the panel name
   - For example, type "lay" to find "Layers"
   - Or type "path" to find "Pathfinder"
   - Search is case-insensitive, so "LAYERS" and "layers" work the same

3. **View Filtered Results**
   - Results filter in real-time as you type
   - Only panels matching your search term are displayed
   - Non-matching panels are hidden from view
   - The list updates instantly with each keystroke

4. **Clear Your Search**
   - Delete your search text to see all panels again
   - Or click the clear button (X) if available
   - The complete panel list returns immediately

**Search Tips and Tricks:**

- **Partial Matching:** Type just a few letters to find panels quickly
  - "char" finds "Character"
  - "trans" finds both "Transform" and "Transparency"
  - "art" finds both "Artboards" and "Appearance"

- **Common Abbreviations:** Try common abbreviations
  - "cc" finds "CC Libraries"
  - "svg" finds "SVG Interactivity"

- **Multiple Results:** If your search returns multiple panels, refine your search term
  - "trans" shows both Transform and Transparency
  - "transf" narrows it down to just Transform

- **Fast Access:** For frequently used panels, searching is often faster than scrolling
  - Type "sw" and hit Enter to open Swatches instantly
  - Type "lay" and click to open Layers immediately

**When to Use Search:**

- **You Know the Panel Name:** Searching is faster than browsing when you know what you want
- **Large Lists:** When viewing all panels feels overwhelming, search narrows it down
- **Muscle Memory:** Once you learn panel names, searching becomes second nature
- **Speed Workflows:** Combine search with Favorites for lightning-fast panel access

**Search Behavior:**

- **Real-Time Filtering:** Results appear as you type, no need to press Enter
- **Substring Matching:** Searches anywhere in the panel name, not just the beginning
- **Case Insensitive:** Uppercase and lowercase letters are treated the same
- **Instant Reset:** Clearing the search immediately restores the full list
- **No Results:** If no panels match, the list appears empty—try a different search term

### Panel Favorites

Just like scripts, you can add your most frequently used Illustrator panels to your Favorites tab for instant access. This eliminates the need to search or browse for panels you use constantly.

**Adding Panels to Favorites:**

1. **Hover Over a Panel**
   - In the Panels Manager tab, move your mouse over any panel name
   - A star icon (favorite icon) appears on the right side of the panel

2. **Click the Star Icon**
   - Click the star to add the panel to your Favorites
   - The star fills in or changes color to indicate it's been favorited
   - The panel is now accessible from the Favorites tab

3. **Confirmation**
   - The panel immediately appears in your Favorites tab
   - You can continue adding more panels to Favorites
   - There's no limit to how many panels you can favorite

**Accessing Favorite Panels:**

1. **Switch to the Favorites Tab**
   - Click the Favorites tab icon (star icon) at the top of ScriptBox
   - Your favorite panels appear alongside favorite scripts
   - Panels and scripts are mixed together in the order you added them

2. **Open from Favorites**
   - Click any favorite panel to open it in Illustrator
   - Works exactly like clicking from the Panels Manager
   - Faster because you don't need to search or browse

3. **Organize Your Favorites**
   - Drag and drop to reorder favorite panels
   - Place your most-used panels at the top
   - Group related panels together for efficient workflows

**Removing Panels from Favorites:**

1. **From the Favorites Tab:**
   - Hover over the favorite panel you want to remove
   - Click the star icon or remove icon that appears
   - The panel is removed from Favorites but remains in Panels Manager

2. **From the Panels Manager Tab:**
   - Hover over a favorited panel (indicated by a filled star)
   - Click the star icon to unfavorite it
   - The panel is removed from your Favorites tab

**Best Practices for Panel Favorites:**

- **Start with Essentials:** Add panels you use in every project first
  - Layers, Swatches, Pathfinder, Align are common choices
  - Add typography panels if you work with text frequently
  - Include color panels if color work is central to your workflow

- **Keep It Focused:** Don't favorite every panel—just the ones you truly use often
  - Too many favorites defeats the purpose of quick access
  - Aim for 5-10 favorite panels for optimal efficiency
  - Less frequently used panels can stay in Panels Manager

- **Organize by Workflow:** Arrange favorite panels in the order you typically use them
  - Place panels for your most common tasks at the top
  - Group related panels together (e.g., all color panels, all text panels)
  - Adjust the order as your workflow evolves

- **Combine with Script Favorites:** Mix panels and scripts in Favorites for complete workflow optimization
  - Example: Favorite the Pathfinder panel alongside shape-related scripts
  - Example: Favorite Character panel with text manipulation scripts
  - Create a one-stop location for all your most-used tools

- **Review Regularly:** Periodically review your favorites and adjust
  - Remove panels you no longer use frequently
  - Add new panels as your workflow changes
  - Keep your Favorites tab lean and relevant

**Common Panel Favorites Combinations:**

Different workflows benefit from different favorite panels:

**For Illustration Work:**
- Layers
- Swatches
- Pathfinder
- Stroke
- Appearance

**For Typography Projects:**
- Character
- Paragraph
- Glyphs
- OpenType
- Swatches

**For UI/UX Design:**
- Layers
- Align
- Transform
- Artboards
- Asset Export

**For Logo Design:**
- Pathfinder
- Align
- Swatches
- Appearance
- Graphic Styles

**For Print Production:**
- Swatches
- Separations Preview
- Flattener Preview
- Links
- Document Info

**View Modes in Favorites:**

The Favorites tab supports the same view modes as other tabs:

- **List View:** See full names of favorite panels and scripts
- **Compact View:** Fit more favorites on screen at once
- **Grid View:** Visual, icon-based layout for quick recognition

Choose the view mode that works best for your favorite panels and scripts collection.

---

## 7. Favorites System

The Favorites system is one of ScriptBox's most powerful productivity features, allowing you to create a personalized collection of your most-used scripts and panels. Instead of searching through categories or navigating menus repeatedly, you can access your essential tools instantly from a single, customized tab.

**Why Use Favorites?**

- **Save Time:** Access frequently-used scripts and panels with one click
- **Reduce Searching:** No more browsing through categories for common tools
- **Personalize Your Workflow:** Build a collection that matches your specific needs
- **Combine Resources:** Keep both scripts and panels together in one place
- **Stay Organized:** Arrange items in the order that makes sense for your workflow
- **Boost Productivity:** Eliminate repetitive navigation and focus on creating

Whether you're a designer who uses the same 10 scripts daily or someone who frequently switches between specific panels, the Favorites system adapts to your unique workflow.

### Adding to Favorites

Adding scripts and panels to your Favorites is quick and intuitive—just click the star icon next to any item you want to save.

**Adding Scripts to Favorites:**

1. **Navigate to the Toolbox Tab**
   - Open the Toolbox tab to browse the built-in script library
   - Or use the External Scripts tab for custom scripts

2. **Locate the Script You Want**
   - Browse through categories or use the search function
   - Expand folders to see individual scripts

3. **Click the Star Icon**
   - Hover over the script you want to add
   - Look for the star icon (☆) next to the script name
   - Click the star icon once
   - The star fills in (★) to indicate the script is now favorited

4. **Confirmation**
   - The script is immediately added to your Favorites
   - No additional confirmation needed
   - The filled star remains visible whenever you see that script

**Adding Panels to Favorites:**

1. **Navigate to the Panels Manager Tab**
   - Click the Panels Manager tab icon at the top of ScriptBox
   - You'll see a list of all available Adobe Illustrator panels

2. **Find the Panel You Want**
   - Browse the list of panels
   - Or use the search function to find specific panels quickly

3. **Click the Star Icon**
   - Hover over the panel name
   - Click the star icon (☆) next to the panel
   - The star fills in (★) to show it's been favorited

4. **Instant Access**
   - The panel is now available in your Favorites tab
   - You can still open it from the Panels Manager as well

**Tips for Adding Favorites:**

- **Start Small:** Begin with 5-10 items you use most frequently
- **Add as You Go:** Favorite items when you notice you're using them repeatedly
- **Don't Overdo It:** Too many favorites defeats the purpose—keep it focused
- **Mix Scripts and Panels:** Combine both for a complete workflow toolkit
- **Review Regularly:** Periodically assess whether favorited items are still useful

**What Can Be Favorited:**

- ✓ Built-in scripts from the Toolbox tab
- ✓ External scripts from custom folders
- ✓ Adobe Illustrator panels from the Panels Manager
- ✗ Tasks, videos, or reference images (these have their own dedicated tabs)

### Accessing the Favorites Tab

Once you've added items to your Favorites, accessing them is simple and fast.

**Opening the Favorites Tab:**

1. **Locate the Favorites Icon**
   - Look at the tab icons at the top of the ScriptBox panel
   - Find the star icon (★) among the 9 tabs
   - It's typically the 4th tab from the left

2. **Click the Favorites Tab**
   - Click once on the star icon
   - The Favorites tab opens, displaying all your favorited items

3. **View Your Collection**
   - All favorited scripts and panels appear in one unified list
   - Items are displayed with their icons and names
   - Both scripts and panels are shown together

**Using Items from Favorites:**

- **Run Scripts:** Click any script in your Favorites to execute it immediately
- **Open Panels:** Click any panel in your Favorites to open it in Illustrator
- **Quick Access:** No need to remember which category a script is in
- **One-Click Workflow:** Your most common actions are always one click away

**Favorites Tab Features:**

- **Unified View:** Scripts and panels together in one place
- **Visual Icons:** Each item displays its distinctive icon for quick recognition
- **Search Function:** Filter your favorites if your collection grows large
- **View Modes:** Switch between list, compact, and grid views
- **Persistent:** Your favorites are saved and persist between Illustrator sessions

**When to Use Favorites:**

- **Daily Workflow:** Start your day by opening your Favorites tab
- **Repetitive Tasks:** When performing the same actions multiple times
- **Project-Specific Work:** Favorite tools relevant to your current project
- **Learning Phase:** Keep new scripts you're learning in Favorites for easy practice
- **Client Work:** Favorite tools specific to recurring client needs

### Organizing Favorites

The Favorites system includes powerful organization features, allowing you to arrange items in the exact order that matches your workflow.

**Reordering Favorites with Drag-and-Drop:**

1. **Open the Favorites Tab**
   - Navigate to the Favorites tab to see your collection

2. **Click and Hold**
   - Click on any item you want to move
   - Hold down the mouse button

3. **Drag to New Position**
   - While holding the mouse button, drag the item up or down
   - You'll see a visual indicator showing where the item will be placed
   - Other items shift to make room for the dragged item

4. **Release to Drop**
   - Release the mouse button when the item is in the desired position
   - The item locks into its new location
   - The new order is automatically saved

5. **Repeat as Needed**
   - Continue rearranging items until your Favorites are organized perfectly
   - There's no limit to how many times you can reorder

**Organization Strategies:**

**By Frequency:**
- Place most-used items at the top
- Less frequent items toward the bottom
- Ensures fastest access to common tools

**By Workflow Stage:**
- Group items by when you use them in your process
- Example: Setup tools first, then editing tools, then export tools
- Mirrors your natural workflow progression

**By Project Type:**
- Organize by the type of work you're doing
- Example: Logo design tools together, illustration tools together
- Switch focus by scrolling to the relevant section

**By Category:**
- Keep similar items grouped together
- Example: All color scripts together, all text scripts together
- Maintains logical organization even in Favorites

**Mixed Approach:**
- Combine strategies that work for you
- Example: Most-used items at top, then organized by category
- Personalize to match your unique workflow

**Visual Organization Tips:**

- **Use View Modes:** Switch to grid view for visual organization by icon
- **Recognize Patterns:** Notice which items you always use together
- **Seasonal Adjustment:** Reorder based on current project needs
- **Keep It Fresh:** Don't be afraid to reorganize as your workflow evolves

### Managing Favorites

Managing your Favorites collection is simple, allowing you to add, remove, and maintain an optimal set of tools.

**Removing Items from Favorites:**

There are two ways to unfavorite items:

**Method 1: From the Favorites Tab**

1. Open the Favorites tab
2. Locate the item you want to remove
3. Click the filled star icon (★) next to the item
4. The star becomes unfilled (☆)
5. The item is immediately removed from your Favorites
6. The item still exists in its original location (Toolbox or Panels Manager)

**Method 2: From the Original Location**

1. Navigate to where the item originally appears (Toolbox or Panels Manager)
2. Find the favorited item (it will have a filled star ★)
3. Click the filled star icon
4. The star becomes unfilled (☆)
5. The item is removed from your Favorites tab

**Both methods work identically—use whichever is more convenient.**

**Maintaining Your Favorites:**

**Regular Review:**
- Periodically review your Favorites (monthly or quarterly)
- Remove items you no longer use frequently
- Add new items you've discovered
- Keep your collection lean and relevant

**Quality Over Quantity:**
- Aim for 10-20 favorites rather than 50+
- Too many favorites reduces their effectiveness
- Focus on truly frequent items
- Use search for occasionally-used scripts

**Adapt to Projects:**
- Adjust favorites based on current project types
- Remove project-specific tools when projects end
- Add new tools as you start new types of work
- Keep core tools that apply to all projects

**Learn and Evolve:**
- As you master scripts, you may need them less in Favorites
- Add newly discovered scripts you want to practice
- Your Favorites should evolve with your skill level
- Don't be attached to old favorites if they're no longer useful

**View Modes for Favorites:**

The Favorites tab supports all three view modes, allowing you to choose the display that works best for your collection:

**List View:**
- Default view with full item names
- Best for: Reading full script/panel names clearly
- Ideal when: You have a moderate number of favorites (10-30)
- Shows: Icon, full name, and star icon for each item

**Compact View:**
- Condensed spacing fits more items on screen
- Best for: Larger collections of favorites (20-40)
- Ideal when: You want to see many items without scrolling
- Shows: Same information as list view but with tighter spacing

**Grid View:**
- Visual grid layout with icons and labels
- Best for: Visual recognition and icon-based navigation
- Ideal when: You recognize items by their icons
- Shows: Larger icons in a grid pattern with names below

**Switching View Modes in Favorites:**

1. Open the Favorites tab
2. Look for view mode icons in the top-right corner
3. Click your preferred view mode icon
4. The display updates immediately
5. Your preference is saved for future sessions

**Choosing the Right View Mode:**

- **Use List View if:** You prefer reading names and have moderate favorites
- **Use Compact View if:** You have many favorites and want to minimize scrolling
- **Use Grid View if:** You're a visual person who recognizes icons quickly
- **Experiment:** Try different views to see which feels most natural
- **Switch Freely:** Change views anytime based on your current needs

**Favorites Best Practices:**

✓ **Do:**
- Keep your collection focused and relevant
- Reorder items to match your workflow
- Remove items you haven't used in months
- Add items as soon as you notice repeated use
- Use view modes that match your working style

✗ **Don't:**
- Favorite everything "just in case"
- Let your Favorites become cluttered
- Forget to remove outdated items
- Ignore the organization features
- Stick with one view mode if another works better

**Troubleshooting Favorites:**

**Item Won't Add to Favorites:**
- Ensure you're clicking the star icon, not the item name
- Check that the item type supports favorites (scripts and panels only)
- Try refreshing ScriptBox by closing and reopening the panel

**Can't Reorder Items:**
- Ensure you're clicking and holding on the item itself
- Try dragging more slowly and deliberately
- Check that you're in the Favorites tab (not another tab)

**Favorites Not Saving:**
- Ensure ScriptBox has write permissions to its settings folder
- Try closing and reopening Illustrator
- Check that your ScriptBox installation is complete

**Star Icon Not Visible:**
- Hover over items to ensure the star icon appears
- Check your view mode—some views show stars differently
- Ensure you're using a recent version of ScriptBox

The Favorites system is designed to grow and adapt with you, becoming more valuable the longer you use ScriptBox. Take a few minutes to set up your initial favorites, and you'll quickly wonder how you ever worked without this personalized toolkit.

---

## 8. Additional Features

Beyond scripts and panels, ScriptBox includes several productivity features designed to enhance your workflow and keep you organized. These supplementary tools help you manage tasks, access learning resources, gather inspiration, and stay informed about updates.

### Tasks Manager

The Tasks Manager is a simple, integrated to-do list that helps you track design tasks, project milestones, and workflow steps without leaving Adobe Illustrator.

**Why Use the Tasks Manager?**

- **Stay Focused:** Keep your task list visible while you work
- **No Context Switching:** Manage tasks without opening external apps
- **Project Organization:** Track multiple projects and their tasks
- **Quick Reference:** See what's next without breaking your creative flow
- **Simple and Lightweight:** No complex features—just straightforward task tracking

**Accessing the Tasks Manager:**

1. Click the **Tasks** tab icon (checklist icon) at the top of the ScriptBox panel
2. The Tasks interface appears with your task list
3. The tab displays all your current tasks and completed items

**Creating Tasks:**

**To Add a New Task:**

1. Open the Tasks tab
2. Look for the input field or "Add Task" button at the top
3. Type your task description
4. Press Enter or click the Add button
5. Your task appears in the list immediately

**Task Creation Tips:**

- **Be Specific:** Write clear, actionable tasks like "Export artboards as PNG" instead of "Export stuff"
- **Break Down Projects:** Create multiple tasks for complex projects
- **Use Action Verbs:** Start tasks with verbs: "Create," "Design," "Export," "Review"
- **Keep It Short:** Aim for one-line task descriptions
- **Add Context:** Include relevant details like "for client presentation" or "version 2"

**Managing Tasks:**

**Checking Off Completed Tasks:**

1. Locate the task you've completed
2. Click the checkbox next to the task
3. The task is marked as complete
4. Completed tasks may move to a separate section or show a strikethrough

**Unchecking Tasks:**

- If you accidentally check a task or need to redo it
- Click the checkbox again to uncheck it
- The task returns to your active task list

**Editing Tasks:**

Depending on the implementation:
- Click on the task text to edit it
- Or use an edit button/icon next to the task
- Make your changes and save

**Deleting Tasks:**

1. Locate the task you want to remove
2. Look for a delete button (trash icon or X) next to the task
3. Click to delete the task
4. The task is permanently removed from your list

**Organizing Your Tasks:**

**Task Organization Strategies:**

**By Priority:**
- Add priority indicators to task names: "[HIGH]", "[MEDIUM]", "[LOW]"
- Or reorder tasks manually with most important at the top
- Focus on high-priority items first

**By Project:**
- Group related tasks together
- Use project names as prefixes: "Logo Project: Create sketches"
- Keep all tasks for one project consecutive in the list

**By Workflow Stage:**
- Organize tasks by design phase: Concept, Design, Refine, Export
- Move tasks through stages as you progress
- See your workflow progression at a glance

**By Due Date:**
- Add dates to task descriptions: "Export files (due Friday)"
- Keep urgent tasks at the top
- Review and reorder daily

**Tracking Your Progress:**

**View Completed Tasks:**
- Completed tasks typically remain visible (with strikethrough or in a separate section)
- Review what you've accomplished
- Provides motivation and progress tracking

**Clear Completed Tasks:**
- Periodically clean up your completed tasks
- Look for a "Clear Completed" button or similar option
- Keeps your task list focused on active work

**Task Count:**
- Some implementations show task counts (e.g., "5 of 12 tasks completed")
- Provides quick progress overview
- Helps you gauge workload

**Best Practices for Task Management:**

✓ **Do:**
- Review your task list at the start of each work session
- Add tasks as soon as you think of them
- Check off tasks immediately when completed
- Keep your active task list under 20 items
- Break large tasks into smaller, manageable steps
- Clear completed tasks regularly

✗ **Don't:**
- Let your task list become overwhelming with too many items
- Write vague tasks that don't specify clear actions
- Forget to update your list as priorities change
- Use tasks for long-term planning (use project management tools instead)
- Leave completed tasks checked indefinitely

**Common Use Cases:**

- **Daily Workflow:** "Open reference images," "Create color palette," "Design 3 variations," "Export finals"
- **Project Checklist:** "Client approval," "Revise logo," "Create business card," "Prepare print files"
- **Learning Goals:** "Watch gradient tutorial," "Practice pen tool," "Try new script"
- **Maintenance Tasks:** "Clean up layers," "Organize artboards," "Update symbols"
- **Client Deliverables:** "Export web assets," "Package for print," "Send proofs"

**Integration with Your Workflow:**

The Tasks Manager works best when integrated into your daily routine:

1. **Morning Review:** Start each session by reviewing your task list
2. **Add as You Go:** Create tasks when you think of them during work
3. **Check Off Progress:** Mark tasks complete as you finish them
4. **End-of-Day Cleanup:** Review completed tasks and plan tomorrow's priorities
5. **Weekly Reset:** Clear completed tasks and plan the week ahead

The Tasks Manager is intentionally simple—it's not meant to replace full project management software, but rather to provide quick, accessible task tracking right where you're working.

### Video Tutorials

The Video Tutorials feature provides quick access to learning resources, helping you master ScriptBox features and discover new techniques through visual instruction.

**Why Use Video Tutorials?**

- **Visual Learning:** See scripts in action with step-by-step demonstrations
- **Quick Access:** No need to search YouTube or documentation sites
- **Curated Content:** Access tutorials specifically about ScriptBox features
- **Custom Library:** Build your own collection of helpful videos
- **Learn While You Work:** Watch tutorials without leaving Illustrator

**Accessing Video Tutorials:**

1. Click the **Videos** tab icon (video camera icon) at the top of the ScriptBox panel
2. The Videos interface displays available tutorial links
3. Browse the list of video resources

**Viewing Tutorial Videos:**

**To Watch a Tutorial:**

1. Open the Videos tab
2. Browse the list of available tutorials
3. Click on any video link
4. The video opens in your default web browser
5. Watch the tutorial and return to Illustrator to apply what you learned

**What Tutorials Cover:**

Video tutorials typically include:
- **Script Demonstrations:** How to use specific scripts effectively
- **Workflow Tips:** Combining multiple scripts for complex tasks
- **Feature Overviews:** Comprehensive guides to ScriptBox features
- **Best Practices:** Tips from experienced users
- **Problem Solving:** Solutions to common design challenges
- **Advanced Techniques:** Creative uses of scripts you might not have considered

**Adding Custom Video Links:**

One of the most powerful features is the ability to add your own video links, building a personalized learning library.

**To Add a Video Link:**

1. Open the Videos tab
2. Look for an "Add Video" button or input field
3. Enter the video URL (YouTube, Vimeo, or other video platforms)
4. Optionally add a title or description
5. Save the link
6. The video appears in your list

**What Videos to Add:**

**ScriptBox-Related:**
- Official ScriptBox tutorials you find helpful
- Community-created script demonstrations
- Workflow videos featuring ScriptBox
- Tips and tricks from other users

**General Illustrator:**
- Illustrator technique tutorials
- Design principle videos
- Tool demonstrations
- Workflow optimization tips

**Project-Specific:**
- Client reference videos
- Style inspiration videos
- Technique demonstrations for current projects
- Industry-specific tutorials

**Managing Your Video Library:**

**Organizing Videos:**

Depending on the implementation, you may be able to:
- Reorder videos by dragging
- Categorize videos with naming conventions
- Add descriptions or notes to video links
- Create sections for different topics

**Naming Conventions for Organization:**

Use prefixes to categorize your videos:
- **[SCRIPT]** - Specific script tutorials
- **[WORKFLOW]** - Workflow and technique videos
- **[BASICS]** - Fundamental Illustrator skills
- **[ADVANCED]** - Advanced techniques
- **[PROJECT]** - Project-specific references

Examples:
- "[SCRIPT] Color Randomizer Advanced Techniques"
- "[WORKFLOW] Creating Icon Sets with ScriptBox"
- "[BASICS] Pen Tool Mastery"
- "[ADVANCED] Complex Pattern Generation"

**Removing Videos:**

1. Locate the video you want to remove
2. Look for a delete button (trash icon or X) next to the video
3. Click to remove the video from your library
4. The video link is deleted (the actual video online remains unchanged)

**Best Practices for Video Tutorials:**

✓ **Do:**
- Add videos immediately when you find helpful content
- Watch tutorials relevant to your current projects
- Revisit videos when you need a refresher
- Share useful video links with team members
- Organize videos with clear, descriptive names
- Remove outdated or no-longer-relevant videos

✗ **Don't:**
- Add every video you come across (be selective)
- Let your library become cluttered with too many links
- Forget to test links before saving them
- Add videos you'll never watch again
- Ignore organization—it matters as your library grows

**Learning Workflow Suggestions:**

**For Beginners:**
1. Start with overview videos covering ScriptBox basics
2. Watch tutorials for the script categories you use most
3. Follow along with the video in Illustrator
4. Practice each technique multiple times
5. Add videos for scripts you want to learn next

**For Intermediate Users:**
1. Focus on workflow optimization videos
2. Learn advanced features of scripts you already use
3. Watch videos about combining multiple scripts
4. Explore categories you haven't used yet
5. Add technique videos for specific design challenges

**For Advanced Users:**
1. Watch advanced technique demonstrations
2. Learn creative applications of familiar scripts
3. Explore edge cases and unusual uses
4. Add videos about scripting and customization
5. Share your own tutorials with the community

**Common Use Cases:**

- **Onboarding:** New team members can access training videos
- **Skill Development:** Build expertise in specific script categories
- **Problem Solving:** Find solutions to specific design challenges
- **Inspiration:** Discover creative uses of scripts
- **Reference:** Keep technique videos handy for occasional tasks
- **Client Work:** Store style reference videos for specific projects

**Video Tutorial Tips:**

- **Take Notes:** Jot down key points while watching
- **Practice Immediately:** Apply techniques right after watching
- **Bookmark Timestamps:** Note specific sections for quick reference
- **Watch at Different Speeds:** Speed up for review, slow down for complex techniques
- **Repeat as Needed:** Don't hesitate to watch videos multiple times

The Video Tutorials feature transforms ScriptBox from just a tool into a learning platform, helping you continuously improve your skills and discover new possibilities.

### Reference Images

The Reference Images feature turns ScriptBox into a visual moodboard, allowing you to keep inspiration and reference materials right in your workspace while you design.

**Why Use Reference Images?**

- **Visual Inspiration:** Keep reference images visible while you work
- **No App Switching:** View references without leaving Illustrator
- **Project Context:** Maintain visual context for current projects
- **Color Reference:** Sample colors directly from reference images
- **Style Consistency:** Ensure your work matches reference materials
- **Client Assets:** Keep client-provided references accessible

**Accessing Reference Images:**

1. Click the **Reference** tab icon (image icon) at the top of the ScriptBox panel
2. The Reference interface displays your moodboard
3. View all added reference images in a visual grid or gallery

**Adding Reference Images:**

**To Add an Image:**

1. Open the Reference tab
2. Look for an "Add Image" button or drag-and-drop area
3. Choose your method:
   - **Drag and Drop:** Drag image files directly into the Reference tab
   - **Browse:** Click "Add Image" and browse your computer for files
   - **Paste:** Some implementations may support pasting images from clipboard
4. The image appears in your reference collection

**Supported Image Formats:**

Typically supports common image formats:
- **JPEG/JPG** - Photos and complex images
- **PNG** - Images with transparency
- **GIF** - Animated or simple graphics
- **SVG** - Vector graphics (if supported)
- **TIFF** - High-quality images

**What Images to Add:**

**Design Inspiration:**
- Style references for current projects
- Color palette inspiration
- Typography examples
- Layout references
- Texture and pattern samples

**Client Materials:**
- Client-provided reference images
- Brand guidelines screenshots
- Approved design directions
- Product photos
- Logo references

**Technical References:**
- Dimension specifications
- Technical drawings
- Measurement guides
- Grid systems
- Template layouts

**Mood and Style:**
- Mood board images
- Artistic inspiration
- Photography references
- Illustration styles
- Design trends

**Viewing and Using Reference Images:**

**Viewing Images:**

1. Open the Reference tab
2. Browse your image collection
3. Click on any image to view it larger (if supported)
4. Zoom or pan to see details
5. Keep the panel open while you work for constant reference

**Using References While Designing:**

- **Side-by-Side:** Dock ScriptBox alongside your canvas to see references while working
- **Color Sampling:** Use Illustrator's Eyedropper tool to sample colors from reference images
- **Style Matching:** Compare your work to references in real-time
- **Proportion Reference:** Check sizing and proportions against references
- **Detail Checking:** Zoom into reference images to see fine details

**Organizing Reference Images:**

**Organization Strategies:**

**By Project:**
- Keep references for each project separate
- Remove old project references when projects complete
- Add new references as projects begin

**By Type:**
- Group color references together
- Keep typography references separate
- Organize by style or mood

**By Priority:**
- Place most important references first
- Keep frequently referenced images easily accessible
- Archive less critical references

**Naming and Labeling:**

If the feature supports image names or captions:
- Use descriptive names: "Color Palette - Blues," "Logo Reference - Client"
- Add project names: "Website Redesign - Hero Section"
- Include dates for version control: "Approved Design - Oct 2025"

**Managing Reference Images:**

**Removing Images:**

1. Locate the image you want to remove
2. Look for a delete button (trash icon or X) on or near the image
3. Click to remove the image
4. The image is deleted from your reference collection (original file remains on your computer)

**Updating References:**

- Remove outdated references regularly
- Add new references as projects evolve
- Replace low-quality images with better versions
- Update references when client provides new materials

**Clearing All References:**

- Some implementations may offer a "Clear All" option
- Use this when starting a new project
- Or when you want to completely refresh your moodboard

**Best Practices for Reference Images:**

✓ **Do:**
- Keep your reference collection focused on current projects
- Remove references when projects are complete
- Use high-quality images when possible
- Organize references logically
- Update references as projects evolve
- Keep the collection manageable (10-20 images)

✗ **Don't:**
- Add every image you find interesting
- Let old project references clutter your collection
- Use extremely large image files (they may slow performance)
- Forget to remove references when they're no longer relevant
- Ignore organization as your collection grows

**Workflow Integration:**

**Project Start:**
1. Clear previous project references
2. Add client-provided materials
3. Add style and mood references
4. Add color palette inspiration
5. Add technical specifications

**During Design:**
1. Keep Reference tab visible while working
2. Refer to images frequently for consistency
3. Add new references as you discover them
4. Remove references that aren't helpful

**Project Completion:**
1. Review final work against references
2. Ensure all requirements are met
3. Clear references when project is delivered
4. Archive important references externally if needed

**Common Use Cases:**

- **Logo Design:** Keep brand references, competitor logos, and style inspiration visible
- **Illustration:** Reference photos, style examples, and color palettes
- **Web Design:** Layout references, UI patterns, and responsive examples
- **Print Design:** Template specifications, bleed guides, and approved designs
- **Icon Design:** Style consistency references and size specifications
- **Packaging:** Product photos, dimension specs, and approved mockups

**Tips for Effective Reference Use:**

- **Quality Over Quantity:** 5 perfect references beat 50 mediocre ones
- **Specific References:** Choose images that directly relate to your current task
- **Update Regularly:** Refresh references as your design direction evolves
- **Multiple Angles:** Include different perspectives of the same concept
- **Technical + Creative:** Balance inspirational images with technical specifications

**Performance Considerations:**

- **Image Size:** Use reasonably sized images (under 5MB each) for better performance
- **Total Images:** Keep your collection under 30 images for optimal performance
- **File Formats:** JPEGs typically perform better than large PNGs
- **Resolution:** Use screen-resolution images (72-150 DPI) rather than print-resolution

The Reference Images feature transforms ScriptBox into a visual workspace companion, ensuring your inspiration and requirements are always just a glance away.

### Info & Updates

The Info tab is your central hub for version information, updates, support resources, and community acknowledgments.

**Why Use the Info Tab?**

- **Stay Current:** Check for the latest ScriptBox updates
- **Version Tracking:** Know which version you're running
- **Get Support:** Access help resources and contact information
- **Learn More:** Find links to documentation and tutorials
- **Community:** See supporters and contributors

**Accessing the Info Tab:**

1. Click the **Info** tab icon (information icon) at the top of the ScriptBox panel
2. The Info interface displays version and support information
3. Browse available resources and information

**Version Information:**

**What You'll See:**

- **Current Version Number:** The version of ScriptBox you're currently running (e.g., 0.2.3.9)
- **Release Date:** When this version was released
- **Build Information:** Technical details about the build (if applicable)

**Why Version Numbers Matter:**

- **Troubleshooting:** Support may ask for your version number
- **Feature Availability:** Some features are only in newer versions
- **Bug Reports:** Include version info when reporting issues
- **Compatibility:** Ensure compatibility with your Illustrator version
- **Update Decisions:** Know if you're running the latest version

**Checking for Updates:**

**How to Check for Updates:**

1. Open the Info tab
2. Look for an "Check for Updates" button or link
3. Click to check if a newer version is available
4. Follow prompts if an update is available

**Update Information:**

When updates are available, you may see:
- **What's New:** List of new features and improvements
- **Bug Fixes:** Issues resolved in the new version
- **Download Link:** Where to get the latest version
- **Installation Instructions:** How to update

**Update Best Practices:**

✓ **Do:**
- Check for updates monthly
- Read release notes before updating
- Backup your favorites and settings before major updates
- Update when you have time to test the new version
- Report any issues you encounter after updating

✗ **Don't:**
- Update in the middle of critical projects
- Skip reading what's new in updates
- Ignore update notifications indefinitely
- Update without backing up custom scripts

**Accessing Support Resources:**

**Available Resources:**

The Info tab typically provides links to:

**Documentation:**
- User Guide (this document)
- Script documentation
- Video tutorials
- FAQ and troubleshooting guides

**Community:**
- Official website (Samolevsky.com)
- Support forums or discussion boards
- Social media channels
- Community script libraries

**Contact:**
- Support email address
- Bug report submission
- Feature request process
- General inquiries

**Getting Help:**

**When You Need Support:**

1. **Check Documentation First:** Most questions are answered in the User Guide
2. **Search for Solutions:** Look for similar issues in forums or FAQs
3. **Gather Information:** Note your version number, Illustrator version, and OS
4. **Describe the Issue:** Be specific about what's not working
5. **Contact Support:** Use the contact information in the Info tab

**What to Include in Support Requests:**

- **ScriptBox Version:** From the Info tab
- **Illustrator Version:** Help > About Adobe Illustrator
- **Operating System:** Windows or macOS version
- **Issue Description:** What you were trying to do
- **Error Messages:** Exact text of any errors
- **Steps to Reproduce:** How to recreate the issue
- **Screenshots:** Visual documentation of the problem

**Special Thanks and Supporters:**

**Community Acknowledgments:**

The Info tab often includes:

- **Supporters:** People who have supported ScriptBox development
- **Contributors:** Community members who contributed scripts or ideas
- **Testers:** Beta testers who helped improve ScriptBox
- **Translators:** Contributors who helped with localization
- **Special Thanks:** Acknowledgments to key community members

**Why This Matters:**

- **Community Recognition:** Celebrates those who make ScriptBox better
- **Transparency:** Shows the collaborative nature of the project
- **Inspiration:** Encourages others to contribute
- **Gratitude:** Acknowledges the community's role in development

**Additional Information:**

**What Else You Might Find:**

- **License Information:** Terms of use and licensing details
- **Credits:** Development team and contributors
- **Third-Party Libraries:** Acknowledgment of open-source components
- **Privacy Policy:** How ScriptBox handles data (if applicable)
- **Changelog:** Detailed history of updates and changes

**Staying Informed:**

**Best Practices:**

✓ **Do:**
- Check the Info tab when you first install ScriptBox
- Review update information when new versions are released
- Bookmark the official website for easy access
- Subscribe to update notifications if available
- Read release notes to discover new features

✗ **Don't:**
- Ignore version information when seeking support
- Skip reading update notes
- Forget to check for updates regularly
- Overlook support resources when you have questions

**Quick Reference:**

**Common Info Tab Actions:**

1. **Check Version:** Open Info tab, note version number
2. **Check for Updates:** Click "Check for Updates" button
3. **Get Support:** Click support link or copy email address
4. **Visit Website:** Click official website link
5. **View Supporters:** Scroll to see community acknowledgments
6. **Read Changelog:** Review what's new in recent updates

**When to Use the Info Tab:**

- **After Installation:** Verify version and explore resources
- **Before Reporting Issues:** Gather version information
- **Monthly Check-In:** Look for updates and new resources
- **When Stuck:** Access support and documentation links
- **Curiosity:** Learn about the community and contributors

The Info tab ensures you always have access to the information and resources you need to get the most out of ScriptBox, while staying connected to the community and keeping your installation up to date.

---

## 9. Tips & Best Practices

Maximize your productivity with ScriptBox by following these proven workflows, organizational strategies, and power-user techniques. This section shares practical tips gathered from experienced users to help you work smarter and faster.

### Workflow Recommendations for Common Tasks

Streamline your most frequent design tasks by combining ScriptBox features strategically.

**Creating Icon Sets:**

1. **Setup Phase:**
   - Use **Create Artboards from Selection** to generate individual artboards for each icon
   - Apply **Re-index Artboards by Position** to organize them logically
   - Use **Fit Artboards to Artwork Bounds** to ensure consistent sizing

2. **Design Phase:**
   - Keep **Panels Manager** open to quickly access Pathfinder and Align panels
   - Use **Smart Object Replacer** to swap placeholder shapes with final designs
   - Apply **Grid Arranger** to organize icon elements systematically

3. **Refinement Phase:**
   - Use **Select by Size** to find and adjust inconsistent elements
   - Apply **Smart Scale** to resize multiple icons proportionally
   - Use **Color Randomizer** to explore color variations quickly

4. **Export Phase:**
   - Add **Asset Export** panel to Favorites for quick access
   - Use **Artboard Navigator** to review all icons before export

**Building Repeating Patterns:**

1. Start with **Seamless Pattern Maker** to create the base pattern
2. Use **Color Shuffle** to explore different color combinations
3. Apply **Random Rotate** or **Random Scale** for organic variation
4. Use **Cloner** to test pattern repetition
5. Save successful patterns using **Selection to Symbols**

**Batch Processing Documents:**

1. Open **Code Editor** and write a custom script that combines multiple operations
2. Use **External Scripts** to organize your custom batch processing scripts
3. Add frequently used batch scripts to **Favorites** for instant access
4. Use **Documents Manager** to process multiple open files
5. Combine with **Items Batch Renamer** for consistent naming

**Cleaning Up Client Files:**

1. Run **Document Cleaner** to remove unused elements
2. Use **Unlock Assistant** to unlock all locked objects
3. Apply **Visibility Manager** to reveal hidden elements
4. Use **Group by Attributes** to organize similar objects
5. Run **Close Open Paths** to fix incomplete paths
6. Apply **Remove Redundant Points** to optimize file size

**Creating Social Media Templates:**

1. Use **Multi-Artboard Duplicator** to create variations
2. Apply **Smart Artboard Resizer** to adjust for different platforms
3. Use **Text Content Swapper** to update copy across artboards
4. Apply **Selection to Swatches** to maintain brand colors
5. Add **Artboard Content Cropper** to ensure proper boundaries

### Organizing Favorites Effectively

Your Favorites tab is your personal productivity dashboard. Organize it strategically to maximize efficiency.

**Strategic Organization Principles:**

**1. Frequency-Based Ordering:**
- Place your most-used scripts at the top
- Drag-and-drop to reorder items by usage frequency
- Review and reorganize monthly as your workflow evolves
- Keep your top 5-10 scripts immediately visible without scrolling

**2. Task-Based Grouping:**
- Group related scripts together mentally (ScriptBox doesn't have folders in Favorites, but you can order them logically)
- Example order: Selection tools → Arrangement tools → Color tools → Export tools
- Keep scripts you use in sequence near each other
- Place panels you use together adjacent to their related scripts

**3. Workflow-Based Organization:**
- Order favorites to match your typical workflow sequence
- Example: Select by Attribute → Grid Arranger → Color Randomizer → Asset Export panel
- This creates a natural top-to-bottom workflow
- Reduces cognitive load when executing multi-step processes

**Favorites Management Best Practices:**

✓ **Do:**
- Start with 10-15 favorites and expand gradually
- Remove items you haven't used in a month
- Add both scripts AND panels to create a complete workflow hub
- Experiment with different organizations to find what works best
- Use Favorites as your "daily driver" tab

✗ **Don't:**
- Add everything to Favorites (defeats the purpose)
- Forget to remove outdated favorites
- Ignore the drag-and-drop reordering feature
- Keep favorites you only use occasionally
- Let your Favorites list grow beyond 20-25 items

**Recommended Starter Favorites:**

For most users, these are excellent starting favorites:

**Essential Scripts:**
- Grid Arranger (Arrange)
- Smart Object Replacer (Arrange)
- Select by Attribute (Select)
- Color Randomizer (Color)
- Smart Scale (Transform)
- Items Batch Renamer (Rename)

**Essential Panels:**
- Layers
- Align
- Pathfinder
- Swatches
- Properties

**Customization by Role:**

**For UI/UX Designers:**
- Create Artboards from Selection
- Smart Artboard Aligner
- Grid Arranger
- Select by Size
- Align panel
- Asset Export panel

**For Illustrators:**
- Path Effects
- Smart Corner Rounder
- Color Randomizer
- Random Scatter
- Brushes panel
- Appearance panel

**For Print Designers:**
- Multi-Artboard Duplicator
- Text Content Swapper
- Swatch Transfer
- Document Cleaner
- Separations Preview panel
- Document Info panel

### Combining Multiple Scripts for Complex Tasks

The real power of ScriptBox emerges when you chain multiple scripts together to accomplish sophisticated workflows.

**Script Combination Strategies:**

**Pattern 1: Select → Modify → Arrange**

Create complex layouts by combining selection, modification, and arrangement scripts:

1. **Select by Attribute** (Select category)
   - Select all objects with specific properties
2. **Smart Scale** (Transform category)
   - Resize selected objects proportionally
3. **Grid Arranger** (Arrange category)
   - Organize into a perfect grid

**Example Use Case:** Organizing a messy collection of icons into a uniform grid.

**Pattern 2: Generate → Randomize → Optimize**

Create organic, varied designs from generated elements:

1. **Cloner** (Arrange category)
   - Create multiple copies of an object
2. **Random Scatter** (Randomize category)
   - Distribute copies randomly
3. **Random Rotate** (Randomize category)
   - Add rotational variation
4. **Color Randomizer** (Color category)
   - Apply random colors
5. **Remove Redundant Points** (Optimize category)
   - Clean up the final result

**Example Use Case:** Creating an organic confetti or particle effect.

**Pattern 3: Batch Process → Rename → Export**

Prepare multiple elements for delivery:

1. **Select by Artboards** (Select category)
   - Select all objects on specific artboards
2. **Smart Artboard Resizer** (Artboard category)
   - Ensure consistent artboard sizes
3. **Artboards Batch Renamer** (Rename category)
   - Apply systematic naming
4. **Fit Artboards to Artwork Bounds** (Artboard category)
   - Trim excess space
5. Open **Asset Export** panel (via Panels Manager)
   - Export all artboards

**Example Use Case:** Preparing a complete icon set for client delivery.

**Pattern 4: Color Exploration Workflow**

Rapidly explore color variations:

1. **Selection to Swatches** (Color category)
   - Extract colors from reference artwork
2. **Smart Swatch Randomizer** (Color category)
   - Apply random combinations to your design
3. **Hue Saturation Lightness** (Color category)
   - Fine-tune the selected variation
4. **Contrast Checker** (Color category)
   - Verify accessibility compliance

**Example Use Case:** Developing accessible color schemes from inspiration images.

**Pattern 5: Text Processing Pipeline**

Handle complex text manipulation:

1. **Select by Font** (Select category)
   - Select all text with specific fonts
2. **Text Content Swapper** (Text category)
   - Update text content in bulk
3. **Sequential Text Numbering** (Text category)
   - Add numbers or sequential labels
4. **Items Batch Renamer** (Rename category)
   - Rename text frame layers systematically

**Example Use Case:** Updating template documents with new content.

**Advanced Combination Tips:**

- **Save Your Workflow:** Write down successful script combinations for future reference
- **Create Custom Scripts:** Use the Code Editor to combine frequently-used script sequences into a single custom script
- **Use External Scripts:** Save your custom combination scripts in External Scripts for easy access
- **Document Your Process:** Add notes in the Tasks tab about which script combinations work well
- **Share with Team:** Export your custom scripts and share them with colleagues

**Common Multi-Script Workflows:**

| Goal | Script Sequence |
|------|----------------|
| **Organize messy artwork** | Unlock Assistant → Visibility Manager → Group by Attributes → Document Cleaner |
| **Create variations** | Cloner → Random Rotate → Random Scale → Color Shuffle |
| **Prepare for export** | Fit Artboards to Artwork Bounds → Artboards Batch Renamer → Document Cleaner |
| **Build icon grid** | Create Artboards from Selection → Grid Arranger → Smart Artboard Aligner |
| **Color exploration** | Selection to Swatches → Smart Swatch Randomizer → Average Colors |
| **Text updates** | Select by Font → Text Content Swapper → Sequential Text Numbering |

### Keyboard Shortcuts and Navigation Tips

Master these navigation techniques to work faster within ScriptBox and Adobe Illustrator.

**ScriptBox Navigation:**

**Tab Switching:**
- Click tab icons at the top to switch between features
- Remember the tab order: Toolbox → External Scripts → Panels → Favorites → Code Editor → Tasks → Videos → Reference → Info
- Keep your most-used tab (usually Toolbox or Favorites) as your default

**Search Efficiency:**
- Use **Cmd/Ctrl + F** (if available) to jump to search in applicable tabs
- Type partial words for faster results: "rand" finds all randomizer scripts
- Clear search quickly to return to full view
- Search is case-insensitive, so type naturally

**View Mode Switching:**
- Learn which view mode works best for each task
- Switch to Grid view when browsing visually
- Use List view when you need to read full names
- Use Compact view when you want to see many options at once

**Panel Management:**
- Dock ScriptBox in a consistent location for muscle memory
- Resize the panel to fit your most common view mode
- Keep ScriptBox visible while working (don't auto-hide)
- Consider a second monitor for keeping ScriptBox always visible

**Illustrator Integration:**

**Assigning Keyboard Shortcuts to Scripts:**

While ScriptBox scripts don't have built-in shortcuts, you can create them:

1. **Method 1: Illustrator Actions**
   - Record an Action that runs your script
   - Assign a keyboard shortcut to the Action
   - Access via Window → Actions

2. **Method 2: Custom Keyboard Shortcuts**
   - Go to Edit → Keyboard Shortcuts
   - Find your script in the Tools or Menu Commands section
   - Assign a custom shortcut
   - Note: Not all scripts appear in this menu

3. **Method 3: Quick Access**
   - Add frequently-used scripts to Favorites
   - Keep ScriptBox panel visible
   - Single-click execution is often faster than keyboard shortcuts

**Workflow Shortcuts:**

- **Cmd/Ctrl + Z:** Undo script results immediately if not satisfied
- **Cmd/Ctrl + Y:** Toggle between Preview and Outline mode to see script effects
- **Cmd/Ctrl + S:** Save before running destructive scripts
- **Cmd/Ctrl + D:** Duplicate objects before testing scripts on them
- **Cmd/Ctrl + 2:** Lock objects you don't want scripts to affect
- **Cmd/Ctrl + Alt + 2:** Unlock all before running selection-based scripts

**Speed Tips:**

✓ **Fast Techniques:**
- Keep ScriptBox docked in the same location always
- Use Favorites for your top 10 scripts
- Learn 3-5 script names and use search instead of browsing
- Run scripts on duplicates first to test results
- Keep frequently-used panels in Favorites alongside scripts

✗ **Slow Techniques:**
- Constantly resizing or moving the ScriptBox panel
- Browsing through all categories every time
- Not using Favorites
- Running scripts without understanding what they do
- Closing and reopening ScriptBox repeatedly

### Customizing View Modes

Choose the right view mode for each task to optimize your workspace and efficiency.

**View Mode Selection Guide:**

**Use List View When:**
- You're learning ScriptBox and need to read full script names
- You have a narrow panel width
- You're working with scripts that have similar icons
- You want maximum readability
- You're browsing unfamiliar categories

**Use Compact View When:**
- You know script names and want to see more options
- You have limited vertical screen space
- You want to minimize scrolling
- You're working with a long list of favorites
- You need to see many items at once for comparison

**Use Grid View When:**
- You have a wide panel
- You recognize scripts by their icons
- You want a visual, icon-focused interface
- You're browsing the Panels Manager
- You prefer spatial memory over text-based navigation

**Per-Tab Customization:**

Different tabs benefit from different view modes:

**Recommended View Modes by Tab:**

- **Toolbox:** List or Compact (easier to read script names)
- **External Scripts:** List (custom scripts may have less distinctive icons)
- **Panels Manager:** Grid (panel icons are highly recognizable)
- **Favorites:** Compact or Grid (you know these items well)

**Adaptive View Mode Strategy:**

Change view modes based on your current task:

**During Learning Phase:**
- Use List view everywhere
- Read full names and descriptions
- Take time to understand each script

**During Proficiency Phase:**
- Switch to Compact view for frequently-used tabs
- Use Grid view for Panels Manager
- Keep List view for External Scripts

**During Expert Phase:**
- Use Compact or Grid view for everything
- Rely on Favorites tab primarily
- Use search instead of browsing

**View Mode Best Practices:**

✓ **Do:**
- Experiment with all three view modes
- Choose different modes for different tabs
- Adjust view mode based on panel size
- Switch modes when your workflow changes
- Use Grid view for visual browsing

✗ **Don't:**
- Stick with default view mode without trying others
- Use Grid view in a narrow panel (items become too small)
- Use List view when you could fit more items in Compact
- Forget that view modes are per-tab (customize each independently)

**Panel Size and View Mode Relationship:**

| Panel Width | Recommended View Mode |
|-------------|----------------------|
| Narrow (< 250px) | List or Compact |
| Medium (250-400px) | List, Compact, or Grid (2 columns) |
| Wide (> 400px) | Grid (3+ columns) or Compact |

**Visual Preferences:**

**If you prefer:**
- **Text-based navigation** → List or Compact view
- **Visual/icon-based navigation** → Grid view
- **Maximum information density** → Compact view
- **Maximum readability** → List view
- **Balanced approach** → Compact view with occasional Grid for panels

### Managing External Scripts

Extend ScriptBox's capabilities by adding your own scripts and managing external script libraries effectively.

**Setting Up External Scripts:**

**Initial Setup:**

1. **Organize Your Scripts Folder:**
   - Create a dedicated folder for your custom scripts
   - Use subfolders to organize by category or project
   - Name scripts descriptively: "Custom_Grid_Builder.jsx" not "script1.jsx"
   - Keep a README file documenting what each script does

2. **Add to ScriptBox:**
   - Open the External Scripts tab
   - Click "Add Folder" or the folder icon
   - Navigate to your custom scripts folder
   - Select the folder to add it to ScriptBox

3. **Verify Loading:**
   - Check that your scripts appear in the External Scripts tab
   - Test run a simple script to confirm functionality
   - Use the refresh button if scripts don't appear immediately

**Organization Best Practices:**

**Folder Structure:**

```
My Custom Scripts/
├── Client Projects/
│   ├── ClientA_Batch_Export.jsx
│   └── ClientB_Template_Builder.jsx
├── Utilities/
│   ├── Quick_Backup.jsx
│   └── Layer_Organizer.jsx
├── Experimental/
│   ├── Test_Script_1.jsx
│   └── WIP_Pattern_Maker.jsx
└── README.txt
```

**Naming Conventions:**

✓ **Good Names:**
- `Batch_Artboard_Export.jsx`
- `Custom_Color_Palette_Generator.jsx`
- `Project_Template_Setup.jsx`
- `Quick_Alignment_Tool.jsx`

✗ **Poor Names:**
- `script.jsx`
- `test.jsx`
- `new1.jsx`
- `untitled.jsx`

**Managing Multiple Script Sources:**

**Strategy 1: Project-Based Organization**
- Add different folders for different projects
- Keep project-specific scripts separate
- Remove project folders when projects complete
- Archive old project scripts outside ScriptBox

**Strategy 2: Category-Based Organization**
- Mirror ScriptBox's category structure
- Create folders like "My Arrange Scripts", "My Color Scripts"
- Easier to find scripts by function
- Maintains consistency with built-in scripts

**Strategy 3: Team-Based Organization**
- Create a shared network folder for team scripts
- Add the shared folder to everyone's ScriptBox
- Maintain a central script library
- Document scripts thoroughly for team use

**Maintenance and Updates:**

**Regular Maintenance Tasks:**

1. **Monthly Review:**
   - Remove scripts you no longer use
   - Test scripts after Illustrator updates
   - Update script documentation
   - Archive outdated scripts

2. **Version Control:**
   - Keep backup copies of working scripts
   - Date your script versions: `Script_Name_v2_2025-10.jsx`
   - Document changes in comments within the script
   - Consider using Git for script version control

3. **Performance Optimization:**
   - Remove duplicate scripts
   - Delete test scripts after validation
   - Keep only production-ready scripts in active folders
   - Move experimental scripts to a separate folder

**Troubleshooting External Scripts:**

**Scripts Not Appearing:**
- Click the refresh button in External Scripts tab
- Verify the folder path is correct
- Check that files have .jsx extension
- Ensure scripts aren't in nested subfolders (if ScriptBox doesn't support recursion)
- Restart Illustrator if necessary

**Scripts Not Running:**
- Verify script syntax is correct
- Check for Illustrator version compatibility
- Test the script outside ScriptBox
- Review error messages in Illustrator
- Check file permissions (read/execute)

**Performance Issues:**
- Reduce the number of external script folders
- Remove unused scripts from active folders
- Avoid adding folders with hundreds of scripts
- Keep external scripts organized and minimal

**Sharing External Scripts:**

**With Team Members:**
1. Document each script's purpose and usage
2. Include example files or instructions
3. Test scripts on different systems before sharing
4. Use a shared network location or cloud storage
5. Maintain a changelog for script updates

**With the Community:**
1. Add clear comments and documentation
2. Include usage examples in script headers
3. Test thoroughly before sharing
4. Consider sharing on ScriptBox forums or GitHub
5. Provide contact information for support

**Best Practices Summary:**

✓ **Do:**
- Organize scripts into logical folders
- Use descriptive, consistent naming
- Document what each script does
- Test scripts before adding to production folders
- Keep external scripts list manageable (under 50 scripts)
- Back up your custom scripts regularly
- Remove scripts you don't use

✗ **Don't:**
- Add every script you find without testing
- Use cryptic or generic names
- Keep broken or outdated scripts
- Add folders with hundreds of unorganized scripts
- Forget to document custom scripts
- Share untested scripts with team members
- Mix experimental and production scripts

**Advanced Tips:**

**Creating Script Libraries:**
- Build collections of related scripts
- Create "starter packs" for new team members
- Maintain separate libraries for different workflows
- Version your script libraries

**Integration with Code Editor:**
- Write scripts in the Code Editor tab
- Test and refine in the editor
- Save to your External Scripts folder when complete
- Iterate between Code Editor and External Scripts

**Workflow Automation:**
- Combine multiple operations into single custom scripts
- Create project-specific automation scripts
- Build scripts that call other scripts
- Use external scripts for complex, multi-step workflows

By following these tips and best practices, you'll transform ScriptBox from a useful tool into an indispensable part of your creative workflow. Experiment with different approaches, find what works best for your specific needs, and don't hesitate to customize your setup as your skills and projects evolve.

---



## 10. Troubleshooting

Even with careful installation and setup, you may occasionally encounter issues with ScriptBox. This section addresses common problems and provides solutions to get you back on track quickly.

### Extension Doesn't Appear in Illustrator

If ScriptBox doesn't show up in the Window > Extensions menu after installation, try these solutions:

**Solution 1: Verify Installation Location**

1. **Check the CEP Extensions Folder**
   - Ensure you copied ScriptBox to the correct location:
     - **Windows:** `C:\Program Files (x86)\Common Files\Adobe\CEP\extensions\`
     - **macOS:** `/Library/Application Support/Adobe/CEP/extensions/`
   - The folder structure should be: `extensions/ScriptBox/[all files]`
   - Make sure you copied the entire ScriptBox folder, not just its contents

2. **Verify Folder Name**
   - The extension folder should be named exactly "ScriptBox" (case-sensitive on macOS)
   - Avoid spaces or special characters in the folder name
   - Don't add version numbers to the folder name

**Solution 2: Enable Unsigned Extensions**

If you're using an unsigned version of ScriptBox, you must enable debug mode:

**Windows:**
1. Open Registry Editor (Win+R, type `regedit`, press Enter)
2. Navigate to: `HKEY_CURRENT_USER\Software\Adobe\CSXS.9`
3. Create a new String value named `PlayerDebugMode` with value `1`
4. Repeat for CSXS.10, CSXS.11, and any other versions you have installed
5. Close Registry Editor and restart Illustrator

**macOS:**
1. Open Terminal (Applications > Utilities > Terminal)
2. Run these commands (press Enter after each):
   ```
   defaults write com.adobe.CSXS.9 PlayerDebugMode 1
   defaults write com.adobe.CSXS.10 PlayerDebugMode 1
   defaults write com.adobe.CSXS.11 PlayerDebugMode 1
   ```
3. Restart Illustrator

**Solution 3: Check Illustrator Version Compatibility**

1. **Verify Your Illustrator Version**
   - ScriptBox requires Adobe Illustrator 18.0 (CC 2014) or later
   - Check your version: Help > About Illustrator
   - Update Illustrator if you're running an older version

2. **Match CSXS Version**
   - Different Illustrator versions use different CSXS versions:
     - CC 2014-2015: CSXS.5 or CSXS.6
     - CC 2015.3-2017: CSXS.7
     - CC 2018-2019: CSXS.8 or CSXS.9
     - CC 2020-2021: CSXS.9 or CSXS.10
     - CC 2022+: CSXS.10 or CSXS.11
   - Enable PlayerDebugMode for your specific CSXS version

**Solution 4: Check File Permissions**

1. **Windows:**
   - Right-click the ScriptBox folder
   - Select Properties > Security
   - Ensure your user account has Read & Execute permissions
   - Click Edit to modify permissions if needed

2. **macOS:**
   - Open Terminal
   - Run: `sudo chmod -R 755 "/Library/Application Support/Adobe/CEP/extensions/ScriptBox"`
   - Enter your admin password when prompted
   - Restart Illustrator

**Solution 5: Restart and Refresh**

1. **Complete Restart:**
   - Quit Illustrator completely (not just close documents)
   - On macOS, ensure Illustrator isn't running in the background
   - Wait 10 seconds
   - Launch Illustrator again
   - Check Window > Extensions > ScriptBox

2. **Clear CEP Cache (Advanced):**
   - Quit Illustrator
   - Delete CEP cache files:
     - **Windows:** `C:\Users\[YourUsername]\AppData\Local\Temp\cep_cache`
     - **macOS:** `~/Library/Logs/CSXS/`
   - Restart Illustrator

**Solution 6: Verify Manifest File**

1. **Check manifest.xml:**
   - Navigate to the ScriptBox folder
   - Open the `CSXS` subfolder
   - Verify `manifest.xml` exists and isn't corrupted
   - If missing or damaged, reinstall ScriptBox

2. **Validate XML Syntax:**
   - Open manifest.xml in a text editor
   - Check for XML syntax errors
   - Ensure all tags are properly closed
   - Compare with a backup if available

### Scripts Not Running Properly

If scripts fail to execute or produce unexpected results, try these troubleshooting steps:

**Problem: Script Shows Error Message**

**Solution 1: Check Selection Requirements**
- Many scripts require objects to be selected before running
- Read the script description (hover tooltip) to understand requirements
- Select appropriate objects and try again
- Some scripts work on specific object types (paths, text, images)

**Solution 2: Verify Document State**
- Ensure you have an active document open
- Some scripts require artboards to be present
- Check that layers aren't locked or hidden
- Verify objects aren't grouped in unexpected ways

**Solution 3: Check Illustrator Permissions**
- Some scripts need permission to access files or system resources
- Grant permissions when prompted by Illustrator
- On macOS, check System Preferences > Security & Privacy
- Ensure Illustrator has necessary permissions

**Problem: Script Runs But Produces Wrong Results**

**Solution 1: Review Script Settings**
- Many scripts open dialog boxes with options
- Read all options carefully before clicking OK
- Adjust settings to match your intended outcome
- Try running the script again with different settings

**Solution 2: Check Object Properties**
- Verify selected objects have the properties the script expects
- Some scripts only work on paths, not compound paths or groups
- Check fill and stroke settings
- Ensure objects aren't clipping masks or symbols

**Solution 3: Test with Simple Objects**
- Create a simple test object (rectangle, circle)
- Run the script on the test object
- If it works, the issue may be with your original objects
- Simplify complex objects before running scripts

**Problem: Script Freezes or Takes Too Long**

**Solution 1: Reduce Complexity**
- Scripts may slow down with many objects or complex paths
- Try running on fewer objects at a time
- Simplify paths before running scripts (Object > Path > Simplify)
- Break large operations into smaller batches

**Solution 2: Close Other Applications**
- Free up system memory by closing unnecessary programs
- Quit other Adobe applications
- Close browser tabs and background applications
- Restart your computer if memory is critically low

**Solution 3: Update Illustrator**
- Ensure you're running the latest version of Illustrator
- Check for updates: Help > Updates
- Install available updates and restart
- Some scripts may require newer Illustrator features

**Problem: Script Worked Before But Now Fails**

**Solution 1: Check Recent Changes**
- Did you update Illustrator recently?
- Did you modify the script file?
- Did you move or rename script files?
- Restore from backup if you made changes

**Solution 2: Reinstall ScriptBox**
- Back up your favorites and custom scripts
- Remove the ScriptBox folder
- Download a fresh copy
- Reinstall following the installation guide
- Restore your favorites and custom scripts

**Solution 3: Reset Illustrator Preferences**
- Quit Illustrator
- Hold Alt+Ctrl+Shift (Windows) or Opt+Cmd+Shift (macOS) while launching
- Click Yes to delete preferences
- Reconfigure your Illustrator settings
- Test the script again

### External Scripts Not Loading

If custom scripts in the External Scripts tab aren't appearing or working:

**Problem: External Scripts Don't Appear**

**Solution 1: Verify Folder Path**
- Check that the folder path is correct and accessible
- Ensure the folder hasn't been moved or renamed
- Verify you have read permissions for the folder
- Try removing and re-adding the folder path

**Solution 2: Check File Extensions**
- External scripts must have the `.jsx` extension
- Verify files aren't named `.jsx.txt` or similar
- Show file extensions in your operating system:
  - **Windows:** File Explorer > View > File name extensions
  - **macOS:** Finder > Preferences > Advanced > Show all filename extensions
- Rename files to have proper `.jsx` extension

**Solution 3: Refresh the Script List**
- Click the refresh button in the External Scripts tab
- Wait a few seconds for scripts to reload
- Check if scripts appear after refresh
- Restart Illustrator if refresh doesn't work

**Solution 4: Check Folder Structure**
- Ensure scripts are directly in the added folder, not in subfolders
- ScriptBox may not recursively search nested folders
- Flatten your folder structure if needed
- Keep scripts organized but not deeply nested

**Problem: External Scripts Won't Run**

**Solution 1: Validate Script Syntax**
- Open the script in a text editor
- Check for syntax errors or corruption
- Verify the script is valid JSX code
- Test the script outside ScriptBox (File > Scripts > Other Script)

**Solution 2: Check Script Compatibility**
- Ensure the script is compatible with your Illustrator version
- Some scripts require specific Illustrator features
- Check script documentation for version requirements
- Contact the script author for compatibility information

**Solution 3: Review Script Permissions**
- Ensure script files have read and execute permissions
- On macOS, run: `chmod +x /path/to/script.jsx`
- On Windows, check file properties > Security
- Move scripts to a location with proper permissions

**Problem: External Scripts Slow Down ScriptBox**

**Solution 1: Reduce Script Count**
- Remove unused scripts from external folders
- Keep only actively used scripts
- Archive old scripts outside of ScriptBox
- Aim for under 50 external scripts total

**Solution 2: Optimize Folder Organization**
- Remove duplicate scripts
- Delete test or experimental scripts
- Organize scripts into focused collections
- Use multiple smaller folders instead of one large folder

**Solution 3: Remove Problematic Scripts**
- Identify scripts that cause slowdowns
- Remove them temporarily to test performance
- Check if scripts have infinite loops or heavy operations
- Contact script authors about performance issues

### Performance Optimization Tips

Keep ScriptBox running smoothly with these performance best practices:

**Optimize Your Setup:**

1. **Manage Favorites Wisely**
   - Keep your favorites list under 30 items
   - Remove scripts you rarely use
   - Organize favorites by frequency of use
   - Regularly review and clean up favorites

2. **Limit External Scripts**
   - Add only essential external script folders
   - Remove folders you're not actively using
   - Keep external script count reasonable (under 50)
   - Archive old project scripts

3. **Use Appropriate View Modes**
   - List view is fastest for large script collections
   - Grid view requires more rendering resources
   - Switch to compact view if experiencing slowdowns
   - Avoid frequent view mode switching

4. **Keep ScriptBox Updated**
   - Check for updates regularly
   - Install new versions when available
   - Read release notes for performance improvements
   - Report performance issues to the developer

5. **Optimize Illustrator Performance**
   - Close unnecessary documents
   - Reduce document complexity when possible
   - Increase Illustrator's memory allocation (Preferences > Performance)
   - Keep Illustrator updated to the latest version

**System-Level Optimization:**

1. **Free Up System Resources**
   - Close unnecessary applications
   - Quit background processes you don't need
   - Restart your computer regularly
   - Ensure adequate free disk space (at least 10GB)

2. **Hardware Considerations**
   - ScriptBox runs best with 8GB+ RAM
   - SSD drives improve loading times
   - Multiple monitors allow keeping ScriptBox always visible
   - Adequate CPU power helps with script execution

3. **Operating System Maintenance**
   - Keep your OS updated
   - Run disk cleanup utilities
   - Check for malware or viruses
   - Optimize startup programs

### Getting Additional Help

If you've tried the troubleshooting steps above and still experience issues, here are additional resources:

**Contact Support:**

- **Website:** Visit [Samolevsky.com](https://samolevsky.com) for documentation and support
- **Email:** Contact the developer through the website contact form
- **Community:** Check for user forums or community groups
- **Social Media:** Follow ScriptBox on social media for updates and tips

**Before Contacting Support:**

When reaching out for help, please provide:

1. **System Information:**
   - Operating system (Windows/macOS) and version
   - Adobe Illustrator version
   - ScriptBox version

2. **Problem Description:**
   - What you were trying to do
   - What happened instead
   - Any error messages (take screenshots)
   - Steps to reproduce the issue

3. **Troubleshooting Attempted:**
   - List the solutions you've already tried
   - Note any changes in behavior
   - Mention if the problem is consistent or intermittent

4. **Additional Context:**
   - When did the problem start?
   - Does it happen with all scripts or specific ones?
   - Have you made any recent system changes?

**Useful Information to Include:**

- Screenshots of error messages
- Screenshots of the ScriptBox interface showing the issue
- Sample files that demonstrate the problem (if applicable)
- Console logs or error logs (if available)

> **Tip:** The more detailed information you provide, the faster support can help resolve your issue. Screenshots are especially helpful for visual problems.

---

## Conclusion

Congratulations! You've completed the ScriptBox User Guide. You now have a comprehensive understanding of all ScriptBox features, from basic script execution to advanced workflow optimization.

**Key Takeaways:**

- **Toolbox Tab:** Your gateway to 200+ automation scripts organized into 11 categories
- **External Scripts:** Extend ScriptBox with your own custom scripts
- **Code Editor:** Write, test, and run JSX scripts without leaving Illustrator
- **Panels Manager:** One-click access to all Illustrator panels
- **Favorites System:** Create a personalized toolkit of your most-used scripts and panels
- **Additional Features:** Tasks, Videos, and Reference tabs keep you organized and inspired
- **Tips & Best Practices:** Optimize your workflow with proven strategies
- **Troubleshooting:** Solutions for common issues and performance optimization

**Next Steps:**

1. **Explore:** Spend time browsing different script categories to discover new tools
2. **Experiment:** Try scripts on test documents to learn what they do
3. **Organize:** Build your Favorites collection with scripts you use most
4. **Customize:** Add external scripts and personalize your setup
5. **Master:** Practice using ScriptBox daily until it becomes second nature
6. **Share:** Help others learn ScriptBox and share your favorite workflows

**Stay Updated:**

- Check the Info tab regularly for updates
- Visit [Samolevsky.com](https://samolevsky.com) for news and resources
- Follow ScriptBox on social media for tips and tutorials
- Join the community to share experiences and learn from others

**Thank You:**

Thank you for choosing ScriptBox! We hope this extension transforms your Adobe Illustrator workflow and helps you create amazing designs more efficiently. If you find ScriptBox valuable, please consider supporting the developer and sharing it with fellow designers.

Happy designing!

---

**Document Version:** 1.0  
**Last Updated:** October 2025  
**Author:** Samolevsky.com  
**ScriptBox Version:** 0.2.3.9

