# Overview GitHub tools for agile product planning

## Create a Repository for the Project.
- The following applies to the menu in this repository.

## Add Template for User Stories

- Click on "Settings" on the main bar.
- Scroll down to “Features” heading, and inside “Issues” click on “Set up templates.”
- Click on “Add a template” and choose “Custom Template.”
- Click on “Preview and Edit”.
- Add content, e.g. 
  - USER STORY: 'topic'
  - Template for user stories
  - As a **role** I can **capability** so that **received benefit**
- Click on the small 'x' to go back to preview mode.
- Templates are stored as files, and they become part of the repository.
- Click on “Propose” changes on the top corner of the screen.
- Commit changes.
- Go to hidden folder in the repository named, ".github".
- This folder contains a markdown file which contains the User Story.

## Add Product Backlog

- “Create a new milestone.”
- In section Issues, click on the user stories to be part of the Product Backlog
- Check the boxes for the user stories to be included.
- Select the correct "milestone" (Product Backlog) from the dropdown menu.
- The name of the milestone now appears under the name of the issue in section issues.  
- You can also create user stories  from inside the milestone. Click “New Issue”.
  - No need to assign this to the backlog, it's already part of it.

## Maintain Backlog

- Browse to the backlog.
- To reprioritise a PBI:
  - Hover the cursor over the task you want to prioritize.
  - Use the dotted icon appearing just before the checkbox this icon to drag and drop the selected task up or down to change the PBIs order.
- To archive a PBI:
  - click on the PBI item.
  - Scroll down the page to the issue details.
  - Add to the text area and select "comment and close" the PBI.
  - the Issue History is updates  to indicate that the item is closed.
  - reopen the item again at any time by  adding a comment and clicking on “Reopen Issue”.
- To review the list of closed items:
  - Browse to the product backlog main page.
  - Click on “Closed” tab on top of the PBI list.

## Reference a PBI Using the Link Feature
- Reference items in the description field or in the comment field.
- Click on the PBI item.
- Click on the “...” on the  top of the issue details page.
- Click on "Edit".
- In the edit view:
  - Type hash '#' in the text box ("write" field).
  - A contextual menu will appear to suggest the list of issues to link to.


## Delete PBI
- Browse to the PBI (the "issue") and open.
- Scroll down "Delete issue" with the trash bin icon next to it.

## Create Iteration
- Create a  timebox for an iteration and assign PBIs to it.
- Navigate to "Issues".
- Click on “Milestones“.
- Click on “New Milestone“ and name it.
- Add a due date (if applicable).
- Add “description” (if applicable).
- Click “Create Milestone”.
- Move stories from another milestone to be iterated to this new milestone:
  - Click on the said milestone
  - Select the user stories or PBIs to be completed in this iteration. 
  - Once selected, click on “Milestone” of the iteration, the stories should be moved to.
  - Select the target iteration from the drop-down menu.
- To confirm that they are actually moved to the target milestone to be iterated.
  - Click on “Milestones”  
  - Select the milestone to be iterated.
  - The PBIs should now show within this iteration (milestone).

## Create and Assign Labels
- Navigate to section “Labels” in the top menu.
- Click on “New Label.”
- Edit or add to the label name on the form (if applicable).
- Add a description (if applicable).
- Customize the label color using default colors or hexadecimal color code.
- Click on ”Create Label”.
- In the section “Milestones”, choose the desired Product Backlog.
- Check the boxes next to the PBIs to be labelled.
- Select the desired label from the dropdown menu “Label” at the top of the PBIs (“issues”).

## Create Iteration Board 
- Click on “Create a project”.
- Name the project.
- Add description.
- Click on “Create Project” to save. 
- Delete the  pre-populated cards in the “To-do” column:
  - Click on the three dots on the top right  side of each card, 
  - Select “Delete note”
- Add User Stories to the board.
  - Click on “ + Add Card” next to the “Filter Card” field.  
  - With the side menu open, enter the name of the iteration (“Milestone”) in the search field 
  - Other filters:
    - Click on the “Issue search” link to see them.
  - Drag and drop User story cards to the “To Do” column of the board. 
  - Place them in order of effort, i.e. must-haves on the top in descending story-point order.  
- Update an existing column on the Board:
  - Update an existing column:
  - Click on the three dots “…”
  - Select “Edit column”
- Add new columns:
  - Click on “ + Add columns”.
- Update a project status of completed project on the bord:
  - Click on “Menu” on the top right menu.
  - Click on “Close project”.
  - The status of the project board is now “closed”.
Delete a board:
  - Click on “Menu” on the top right menu.
  - Click on the three dots “…”
  - Select “Edit”.
  - Click on “Delete project”.





*References: Code Institute's Learning Material on Agile.*
