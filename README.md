# Jira Guide

This guide provides an overview of Jira, focusing on its Scrum and Kanban methodologies, issue management, backlog grooming, and board configuration. Follow this guide to effectively organize and manage your projects in Jira.

---

## Table of Contents
- [Scrum vs. Kanban](#scrum-vs-kanban)
- [Project Structure](#project-structure)
- [Backlog Interface](#backlog-interface)
- [Managing Issues](#managing-issues)
- [Filtering and Categorization](#filtering-and-categorization)
- [Components and Releases](#components-and-releases)
- [Backlog Grooming](#backlog-grooming)
- [Creating and Configuring Boards](#creating-and-configuring-boards)
- [Sprint Reports](#sprint-reports)

---

## Scrum vs. Kanban
- **Scrum**: Work is managed in **sprints**, which are time-boxed periods where a set of tasks moves through phases until completed.
- **Kanban**: Work is managed through a **pull system**, where tasks are pulled from left to right (e.g., from "To Do" to "Done") based on resource availability.

---

## Project Structure
- **Project Name**: The overarching container for all work.
- **Epic**: High-level features (e.g., "Shopping Module") that represent larger goals and take weeks to complete.
  - **Story (User Story)**: Represents new functionality or a feature within the product.
  - **Bug**: Issues or errors identified during or after development.
  - **Task**: Work required to complete an item (e.g., configuration or testing).
  - **Subtasks**: The smallest work units under a story, usually taking a day or less to complete.

---

## Backlog Interface
- **Purpose**: Create and organize all issues (Epics, Stories, Bugs, Tasks).
- **Key Points**:
  - **Summary**: Ensure concise summaries for all issues.
  - **Parent Relationships**: 
    - Epics have no parents.
    - Stories, Tasks, and Bugs must be linked to a parent (typically an Epic).
  - Use the "Create Issue" shortcut to streamline issue creation.
  - Subtasks can be added to Stories for detailed tracking.
  - Assign Stories to Epics by dragging and dropping them onto the Epic tile.

---

## Managing Issues
- **Epics**:
  - Assign distinct colors for easier identification.
- **Labels**:
  - Use labels to categorize similar Stories, Tasks, or Bugs.
  - Labels must be single words (e.g., `user_story_category`).
  - Assign labels quickly by selecting an issue and pressing `L`.
- **Components**:
  - Subsections within a project (e.g., "iOS", "macOS").
  - Link components to Stories through the details tab.

---

## Filtering and Categorization
- **Filter by Label**: Identify and group related issues.
- **Filter by Epic**: Focus on issues within a specific Epic.
- **Filter by Version**: Prioritize issues tied to a particular release.

---

## Components and Releases
- **Components**: Use these to group issues within a project (e.g., "iOS" or "Backend").
- **Releases**:
  - Track project versions.
  - Use the "V" shortcut in the backlog to access version control.
  - Drag and drop Stories into the desired version.
  - A green progress bar in the version indicates how much work has been completed.

---

## Backlog Grooming
- **Key Actions**:
  1. Ensure every issue is connected to an Epic.
  2. Verify all issues are assigned to a version.
  - Rank issues by priority within a version for better focus.
  - Bugs related to a Story should be ranked immediately below that Story.
- **Prioritization**:
  - Use team discussions to assign priority numbers.
  - Include visuals to indicate story points and their meanings.
![This image shows the values to be assigned for knowing the priority](https://github.com/user-attachments/assets/7a80bc66-1494-4fed-95da-3a839ea636d1)

---

## Creating and Configuring Boards
- **Basic Workflow**:
  - Columns: "To Do", "In Progress", "Done".
  - Customize columns in the board configuration for real-life workflows.
- **Done Column**:
  - When dragging a task to "Done", you may be prompted to update the parent issue.

---

## Sprint Reports
- **Purpose**: Provide insights into sprint progress and outcomes.
  - Identify which issues were completed and which were not.
  - Use this information to make strategic plans for future sprints.
- **Visual Indicators**:
  - A green progress line in the sprint report shows the amount of work completed.

---

## Tips for Success
1. Use shortcuts (e.g., `L` for labels, `V` for versions) to save time.
2. Continuously groom the backlog to maintain focus and clarity.
3. Customize boards and filters to match your team’s workflow.

---

### **Jira Shortcuts and Tips**


- **Create Issue (`C`)**: Quickly open the issue creation window.  
- **Quick Search (`Ctrl + K` / `Cmd + K`)**: Find projects, issues, or boards instantly.  
- **Keyboard Shortcuts (`?`)**: View all available Jira shortcuts.  
- **Labels (`L`)**: Assign or edit labels for an issue directly.  
- **Version Panel (`V`)**: Open the version control panel in the backlog.  
- **Bulk Select (`Shift + Click`)**: Select multiple issues for batch actions.  
- **Drag and Drop**: Assign Stories to Epics or Versions by dragging them.  
- **Filter by Labels**: Use a single word or `_` for multi-word labels.  
- **Epic Panel**: Collapse or expand Epics in the backlog for better focus.  
- **Board Configuration**: Add custom columns to your workflow.  
- **Done Prompt**: Updating tasks to "Done" may prompt you to update the parent issue.  

Use these tips to streamline your Jira workflow and manage tasks with ease!

By following these steps, you can effectively manage your projects in Jira, ensuring clarity, prioritization, and efficient workflows.
![how a jira account would look like](https://github.com/user-attachments/assets/2c11945c-488d-4e55-95a0-020674521c85)




