# Practical Record

This README has two parts:

- **Part 1:** Jira Cloud practicals (Questions 1-34)
- **Part 2:** Python AI / Machine Learning practicals (Questions 1-29)

---

# Part 1: Jira Cloud Practicals

---

**Question 1. Create a Jira Cloud Project (Kanban), Configure Project Details, and Explore the Dashboard**

**A. Create a Jira Cloud Account and Explore Dashboard**

1. Open Jira Cloud in your browser.
2. Sign in with your Atlassian account or create a new account.
3. Open Jira and explore the main dashboard, navigation menu and available projects.

**B. Create a Kanban Project**

1. Click **Projects → Create project**.
2. Select **Kanban** from the project templates.
3. Select **Company-managed** if the practical requires it.
4. Click **Use template** or **Create project**.
5. Enter the project name and project key.
6. Click **Create** to create the project.

**C. Configure Project Details and Explore the Board**

1. Open the newly created project.
2. Open the project board and inspect the columns, such as To Do, In Progress and Done.
3. Go to **Project settings**.
4. Open **Details** or **Summary** and review the project name, key and description.
5. Update the project details if required and save the changes.
6. Return to the board and explore the available project features.

---

**Question 2. Create a Jira Project, Add Team Members, and Assign Project Roles**

**A. Add Team Members**

1. Open the required Jira project.
2. Go to **Project settings → People** or **Access**.
3. Click **Add people**.
4. Enter the team member's email address or select the required user.
5. Select the appropriate project role.
6. Click **Add** to add the team member.
7. Repeat the steps for other team members.

**B. Assign Project Roles**

1. Go to **Project settings → People**.
2. Find the team member whose role you want to change.
3. Open the role selection option beside the user's name.
4. Select the required role, such as Administrator, Member or Viewer, depending on the roles available.
5. Save the changes if required.
6. Verify that each team member has the correct role.

---

**Question 3. Configure Issue Types, Components, and Versions**

**A. Configure Issue Types**

1. Open your Jira project.
2. Go to **Project settings → Issue types**.
3. Check whether Epic, Story, Task and Bug are available.
4. If any issue type is missing, use the available option to add or associate it with the project.
5. Save the changes if required.

**B. Create Project Components**

1. Go to **Project settings → Components**.
2. Click **Create component** or **Add component**.
3. Enter the component name, such as Frontend, Backend or Database.
4. Enter the description and component lead if required.
5. Click **Create**.
6. Repeat the steps to create additional components.

**C. Create Project Versions**

1. Go to **Project settings → Versions** or **Releases**.
2. Click **Create version** or **Add version**.
3. Enter a version name, such as Version 1.0.
4. Enter the start date, release date and description if required.
5. Click **Add** or **Save**.
6. Verify that the version appears in the Versions/Releases list.

---

**Question 4. Create an Epic, Add Related Issues, Assign Users, and Set Priority and Due Dates**

**A. Create an Epic**

1. Open your Jira project.
2. Click **Create** from the top navigation bar.
3. Select the issue type **Epic**.
4. Enter the Epic name or summary, such as Student Management System.
5. Enter a description if required.
6. Click **Create**.

**B. Create Related Issues**

1. Click **Create** again.
2. Select **Story** as the issue type.
3. Enter the Story summary, such as Design Login Page.
4. Select the parent Epic using the **Parent** field, if available.
5. Click **Create**.
6. Repeat the steps to create other Stories and Tasks linked to the same Epic.

**C. Assign Issues and Set Priority and Due Dates**

1. Open the created issue.
2. Click the **Assignee** field and select the required user.
3. Set the **Priority** field to High, Medium or another required level.
4. Click **Edit** if necessary and enter the required **Due date**.
5. Click **Update** or save the changes.
6. Repeat the steps for each issue.
7. Verify the assignee, priority, due date and parent Epic.

---

**Question 5. Create a Jira Automation Rule with a Trigger, Condition, and Action**

**A. Create an Automation Rule**

1. Open the Jira project.
2. Go to **Project settings → Automation** or open Automation from the project menu.
3. Click **Create rule**.
4. Select the trigger **Issue transitioned**.
5. Configure the trigger to run when an issue transitions to **Done**, if the option is available.

**B. Add a Condition**

1. Click **Add component** or **Add condition**.
2. Select **Issue fields condition**.
3. Select the field **Status**.
4. Select the condition **equals**.
5. Choose **Done** as the value.
6. Save the condition.

**C. Add an Action and Test the Rule**

1. Click **Add component → Add an action**.
2. Select **Assign issue** to assign the issue to a specified user, or choose **Send email** to send a notification.
3. Configure the selected action.
4. Enter a rule name, such as Notify When Issue Is Done.
5. Click **Turn on rule**, **Publish** or **Enable**, depending on the interface.
6. Open a test issue and move it to Done.
7. Open the automation **Audit log** and verify whether the rule executed successfully.

---

**Question 6. Configure the Jira Mobile App and Update an Issue**

**A. Install and Sign In**

1. Open the Google Play Store or Apple App Store.
2. Search for the official Jira Cloud mobile app.
3. Install and open the app.
4. Sign in using your Atlassian account.
5. Select your Jira site and project.

**B. View and Update an Issue**

1. Open your project and select the required issue.
2. View the issue summary, description, status and assignee.
3. Tap the issue status or available workflow action.
4. Select the required status, such as In Progress or Done.
5. Open the **Comments** section.
6. Enter your comment and tap **Add** or **Send**.

**C. Assign the Issue and Verify**

1. Open the issue details.
2. Tap **Assignee** or the edit option.
3. Select the required user.
4. Save the changes.
5. Reopen the issue and verify the status, comment and assignee.
6. Check the activity section and notifications if available.

---

**Question 7. Create a Scrum Project and Board, Start a Sprint, and Review Progress**

**A. Create a Scrum Project and Board**

1. Open Jira and click **Projects → Create project**.
2. Select the **Scrum** template.
3. Choose the required project type, such as **Company-managed**, if specified.
4. Enter the project name and key.
5. Click **Create project**.
6. Open the Scrum board and select **Backlog**.

**B. Create and Start a Sprint**

1. Open the **Backlog** section.
2. Click **Create sprint**.
3. Create issues using **Create issue** or drag existing issues into the sprint.
4. Add the required Stories and Tasks to the sprint.
5. Click **Start sprint**.
6. Enter the sprint name, duration and start/end dates if requested.
7. Click **Start** to begin the sprint.

**C. Review Sprint Progress**

1. Open the active Scrum board.
2. Move issues across the workflow columns as work progresses.
3. Open **Reports** from the project sidebar.
4. Select **Sprint Report** or **Burndown Chart**.
5. Select the required sprint.
6. Review completed issues, incomplete issues and sprint progress.

---

**Question 8. Create and Configure Issue Types, Components, and Versions**

**A. Configure Issue Types**

1. Open the Jira project.
2. Go to **Project settings → Issue types**.
3. Verify that Epic, Story, Task and Bug are available.
4. Add or associate any missing issue types with the project.
5. Save the changes if required.

**B. Create Components**

1. Go to **Project settings → Components**.
2. Click **Create component**.
3. Enter a component name, such as Frontend.
4. Enter the description and other details if required.
5. Click **Create**.
6. Repeat for the remaining components.

**C. Create Versions**

1. Go to **Project settings → Versions/Releases**.
2. Click **Create version**.
3. Enter the version name, such as Version 1.0.
4. Add the release date and description if required.
5. Click **Add** or **Save**.
6. Open an issue and select the appropriate **Component** and **Fix version** fields, if available.
7. Save the issue and verify the associations.

---

**Question 9. Create an Epic with Stories and Tasks, Assign Issues, and Set Priority and Due Dates**

**A. Create an Epic**

1. Open your Jira project.
2. Click **Create**.
3. Select **Epic** as the issue type.
4. Enter the Epic summary and description.
5. Click **Create**.

**B. Create Stories and Tasks**

1. Click **Create** and select **Story**.
2. Enter the Story summary.
3. Set the **Parent** field to the previously created Epic.
4. Click **Create**.
5. Repeat the steps to create the required Stories and Tasks.
6. Ensure that each Story and Task is associated with the correct Epic.

**C. Assign Issues and Set Details**

1. Open each Story or Task.
2. Select the required **Assignee**.
3. Set the **Priority** field.
4. Open **Edit** and enter the required **Due date**.
5. Click **Update**.
6. Repeat for all issues and verify the Epic hierarchy.

---

**Question 10. Customize a Jira Workflow and Associate It with a Project**

**A. Open Workflow Settings**

1. Open Jira.
2. Click the **Settings** gear icon.
3. Select **Issues** or **Work items**, depending on your Jira interface.
4. Open **Workflows**.
5. Click **Add workflow** or edit an existing workflow. Administrator permissions may be required.

**B. Add Statuses and Transitions**

1. Open the workflow editor.
2. Add the required statuses, such as To Do, In Progress, In Review and Done.
3. Add transitions between the statuses.
4. Connect the statuses in the required order.
5. Add conditions or validators to transitions if required.
6. Save or publish the workflow draft.

**C. Associate the Workflow with a Project**

1. Open **Settings → Issues/Work items → Workflow schemes**.
2. Create or edit the workflow scheme.
3. Associate the custom workflow with the required issue types.
4. Associate the workflow scheme with your project using the available project association option.
5. Complete any migration prompts if Jira displays them.
6. Open an issue and test the transitions to verify that the workflow works correctly.

---

**Question 11. Generate a Pie Chart or Issue Statistics Report and Add It to a Dashboard**

**A. Create a Dashboard**

1. Click **Dashboards → View all dashboards**.
2. Click **Create dashboard**.
3. Enter the dashboard name, such as Project Statistics Dashboard.
4. Configure sharing permissions if required.
5. Click **Create**.

**B. Add a Gadget**

1. Open your dashboard.
2. Click **Add gadget**.
3. Search for **Pie Chart** or **Issue Statistics**.
4. Click **Add** for the required gadget.
5. Close the gadget directory and return to the dashboard.

**C. Configure the Report**

1. Click **Edit** or **Configure** on the gadget.
2. Select the required project or saved filter.
3. Select the statistic type, such as Status, Assignee or Priority.
4. Enter any other required details.
5. Click **Save**.
6. Verify that the chart or issue statistics appear on the dashboard.

---

**Question 12. Create, Test, and Enable a Jira Automation Rule**

**A. Create the Rule**

1. Open the Jira project.
2. Go to **Project settings → Automation**.
3. Click **Create rule**.
4. Select the required trigger, such as **Issue created** or **Issue transitioned**.
5. Configure the trigger according to the question.

**B. Add Condition and Action**

1. Click **Add condition**.
2. Select **Issue fields condition**.
3. Choose the required field and condition, such as Status equals In Progress.
4. Click **Add action**.
5. Select the required action, such as **Assign issue** or **Send email**.
6. Configure the action and enter the required details.

**C. Test and Enable**

1. Enter a suitable rule name.
2. Save the rule as a draft if the interface provides that option.
3. Test the rule using a sample issue and the required trigger event.
4. Open the rule's **Audit log** and inspect the execution result.
5. Correct any errors if necessary.
6. Enable the rule and verify that it is active.

---

**Question 13. Configure Project Roles and Review Permissions**

**A. Review Project Roles**

1. Open the Jira project.
2. Go to **Project settings → People** or **Access**.
3. Review the users assigned to the project.
4. Check the roles assigned to each user.
5. Add users or change their roles if required.

**B. Review the Permission Scheme**

1. Open **Jira settings → Issues/Work items**.
2. Select **Permission schemes**.
3. Locate the permission scheme associated with your project.
4. Click **Permissions** or **View permissions**.
5. Review permissions such as Browse Projects, Create Issues, Edit Issues, Assign Issues and Transition Issues.
6. Check which project roles or groups have each permission.
7. Record the findings and modify permissions only if required and authorized.

---

**Question 14. Create a Scrum Project, Add Members, Create an Epic, Start a Sprint, and Generate a Sprint Report**

**A. Create a Scrum Project and Add Members**

1. Go to **Projects → Create project**.
2. Select the **Scrum** template.
3. Choose **Company-managed** if required.
4. Enter the project name and key.
5. Click **Create project**.
6. Open **Project settings → People**.
7. Click **Add people**, select the required users and assign their roles.
8. Click **Add**.

**B. Configure Issue Types and Create an Epic**

1. Open **Project settings → Issue types**.
2. Verify that Epic, Story and Task are available.
3. Click **Create** and select **Epic**.
4. Enter the Epic summary and create it.
5. Create the required Stories and Tasks.
6. Set the **Parent** field of each related issue to the Epic.
7. Assign users and configure priorities and due dates if required.

**C. Create and Start a Sprint**

1. Open **Backlog**.
2. Click **Create sprint**.
3. Add the required issues to the sprint.
4. Click **Start sprint**.
5. Enter the sprint name and duration.
6. Click **Start**.

**D. Generate a Sprint Report**

1. Open **Reports** from the project sidebar.
2. Select **Sprint Report**.
3. Select the sprint you want to review.
4. Review the completed and incomplete issues.
5. Verify that the report displays the sprint's progress.

---

**Question 15. Create a Jira Project, Configure a Workflow, Create JQL Filters, Build a Dashboard, and Test Automation**

**A. Create a Project and Configure Workflow**

1. Go to **Projects → Create project**.
2. Select **Scrum** or **Kanban** as required.
3. Enter the project name and key.
4. Click **Create project**.
5. Open **Jira settings → Issues/Work items → Workflows**.
6. Create or edit a workflow.
7. Add the required statuses and transitions.
8. Publish the workflow and associate it with the project through its workflow scheme, if required.

**B. Create and Save a JQL Filter**

1. Open **Filters → Search work items** or **Issues → Search for issues**, depending on the interface.
2. Switch to **Advanced search**.
3. Enter a JQL query such as:

   ```sql
   project = DEMO ORDER BY created DESC
   ```

4. Replace `DEMO` with your actual project key.
5. Click **Search** or **Run**.
6. Verify the returned issues.
7. Click **Save as** and enter a filter name.
8. Save the filter.

**C. Create a Dashboard with Gadgets**

1. Open **Dashboards → Create dashboard**.
2. Enter the dashboard name.
3. Click **Create**.
4. Click **Add gadget**.
5. Add gadgets such as Filter Results, Pie Chart and Issue Statistics.
6. Configure each gadget using the saved filter.
7. Select the required statistics and save the gadget settings.

**D. Create and Test Automation**

1. Open **Project settings → Automation**.
2. Click **Create rule**.
3. Select the trigger, condition and action.
4. Configure the rule and enter a name.
5. Save and enable the rule.
6. Trigger the rule using a sample issue.
7. Open the **Audit log** and verify the result.

---

**Question 16. Create a Jira Cloud Account, Explore the Dashboard, and Create a Company-Managed Project**

**A. Create an Account and Explore the Dashboard**

1. Open Jira Cloud.
2. Sign in or create an Atlassian account.
3. Open Jira.
4. Explore the dashboard, navigation menu and Projects section.

**B. Create a Company-Managed Project**

1. Click **Projects → Create project**.
2. Select **Scrum** or **Kanban**.
3. Choose **Company-managed** if the option is displayed.
4. Click **Use template**.
5. Enter the project name and key.
6. Click **Create project**.

**C. Configure Project Details**

1. Open the project.
2. Go to **Project settings → Details** or **Summary**.
3. Enter or update the project name, key and description if required.
4. Save the changes.
5. Open the project board.
6. Review the board columns and available settings.

---

**Question 17. Add Team Members and Assign Project Roles**

**A. Add Team Members**

1. Open your Jira project.
2. Go to **Project settings → People** or **Access**.
3. Click **Add people**.
4. Enter the team member's email address or select their account.
5. Select the appropriate project role.
6. Click **Add**.
7. Repeat for all required team members.

**B. Assign and Verify Roles**

1. Open **Project settings → People**.
2. Locate the required team member.
3. Open the role selection option.
4. Select the appropriate role.
5. Save the changes if necessary.
6. Verify that the correct role is displayed beside each team member.

---

**Question 18. Configure Epic, Story, Task, and Bug; Create Components and Versions**

**A. Configure Issue Types**

1. Open the Jira project.
2. Go to **Project settings → Issue types**.
3. Verify that Epic, Story, Task and Bug are available.
4. Add or associate any missing issue types.
5. Save the changes if required.

**B. Create Components and Versions**

1. Open **Project settings → Components**.
2. Click **Create component**.
3. Enter the component name and description.
4. Click **Create**.
5. Repeat to create additional components.
6. Open **Project settings → Versions/Releases**.
7. Click **Create version**.
8. Enter the version name and release details.
9. Click **Add** or **Save**.

**C. Associate Components and Versions with an Issue**

1. Open an existing issue or create a new issue.
2. Click **Edit**.
3. Select the appropriate **Component/s** value.
4. Select the appropriate **Fix Version/s** value.
5. Click **Update**.
6. Reopen the issue and verify that the component and version are displayed correctly.

---

**Question 19. Install Jira Mobile, Update an Issue, Add a Comment, and Change Assignee**

**A. Install and Sign In**

1. Open the Google Play Store or Apple App Store.
2. Search for the official Jira Cloud app.
3. Install and open the app.
4. Sign in using your Atlassian account.
5. Open the required project.

**B. View and Update an Issue**

1. Search for and open the required issue.
2. View the issue details.
3. Tap the status or workflow action.
4. Select the required status.
5. Open **Comments** and enter your comment.
6. Tap **Add** or **Send**.

**C. Change Assignee and Verify**

1. Open the issue details.
2. Tap the **Assignee** field or **Edit** option.
3. Select the required user.
4. Save the change.
5. Verify the status, comment and assignee in the issue details.
6. Check the activity history and notifications if available.

---

**Question 20. Create a Company-Managed Scrum Project with an Epic, Two Stories, and One Task**

**A. Create a Scrum Project**

1. Open Jira and click **Projects → Create project**.
2. Select the **Scrum** template.
3. Choose **Company-managed**.
4. Click **Use template**.
5. Enter the project name and key.
6. Click **Create project**.

**B. Create an Epic**

1. Open the project and click **Create**.
2. Select **Epic** as the issue type.
3. Enter the Epic summary, such as Student Portal Development.
4. Enter the description if required.
5. Click **Create**.

**C. Create Two Stories and One Task**

1. Click **Create**.
2. Select **Story** and enter the first Story summary.
3. Set its **Parent** field to the created Epic.
4. Click **Create**.
5. Repeat to create a second Story and select the same Epic as its parent.
6. Create a **Task** and select the same Epic as its parent.
7. Save all issues.

**D. Verify the Epic Hierarchy**

1. Open the Epic.
2. View the child issues or associated work items.
3. Verify that both Stories and the Task are linked to the Epic.
4. Open each issue and check its **Parent** field.

---

**Question 21. Create and Save a JQL Filter for Selected Priority and Status**

**A. Open Advanced Issue Search**

1. Open Jira.
2. Click **Filters → Search work items** or **Issues → Search for issues**.
3. Switch to **Advanced search**.
4. Enter the following JQL query, replacing `DEMO` with your project key.

```sql
project = DEMO AND priority = High AND status = "In Progress" ORDER BY created DESC
```

**B. Run and Save the Filter**

1. Click **Search** or **Run**.
2. Verify that the results contain issues from the selected project with High priority and In Progress status.
3. Click **Save as**.
4. Enter a filter name, such as High Priority In Progress Issues.
5. Click **Save**.
6. Open **Filters → My filters** and verify that your filter is saved.

---

**Question 22. Create a Custom Dashboard and Add Issue Statistics Gadgets**

**A. Create a Dashboard**

1. Click **Dashboards → View all dashboards**.
2. Click **Create dashboard**.
3. Enter a dashboard name, such as Issue Statistics Dashboard.
4. Configure the sharing settings if required.
5. Click **Create**.

**B. Add Gadgets**

1. Open the dashboard.
2. Click **Add gadget**.
3. Search for **Pie Chart**, **Issue Statistics** or **Filter Results**.
4. Click **Add** beside the required gadgets.
5. Close the gadget directory.

**C. Configure the Gadgets**

1. Click **Edit** or **Configure** on a gadget.
2. Select the relevant project or saved filter.
3. Select the statistic, such as Status, Assignee or Priority.
4. Click **Save**.
5. Verify that the gadgets display the correct issue information.

---

**Question 23. Configure Project Roles and Review Permissions**

**A. Review Project Roles**

1. Open the required Jira project.
2. Go to **Project settings → People** or **Access**.
3. Review the team members and their assigned roles.
4. Add users or update roles if required.
5. Verify the role assignments.

**B. Review Permissions**

1. Open **Jira settings → Issues/Work items → Permission schemes**.
2. Find the permission scheme associated with the project.
3. Open the scheme and review its permissions.
4. Check Browse Projects, Create Issues, Edit Issues, Assign Issues and Transition Issues.
5. Identify the roles or groups granted each permission.
6. Record which roles can perform the required activities.
7. Modify permissions only if required and you have administrator access.

---

**Question 24. Create an Automation Rule to Assign Issues Automatically**

**A. Create an Automation Rule**

1. Open the Jira project.
2. Go to **Project settings → Automation**.
3. Click **Create rule**.
4. Select **Issue created** or **Issue transitioned** as the trigger.
5. Configure the trigger according to the question.

**B. Add a Condition and Assignment Action**

1. Click **Add condition**.
2. Select **Issue fields condition**.
3. Select **Status** as the field.
4. Select **equals** and choose the required status, such as In Progress.
5. Click **Add action**.
6. Select **Assign issue**.
7. Choose the required user or assignment method.
8. Save the action.

**C. Test the Rule**

1. Enter a rule name, such as Auto Assign Issues.
2. Save and enable the rule.
3. Create a sample issue or transition an issue to the specified status.
4. Open the issue and verify its assignee.
5. Open the automation **Audit log** and check the execution result.

---

**Question 25. Create a Scrum Board, Start a Sprint, and View Its Report**

**A. Open or Create a Scrum Board**

1. Open your Scrum project.
2. Open the Scrum board and select **Backlog**.
3. If a board does not exist, use the available **Boards → Create board** option.
4. Select **Scrum board**.
5. Choose the option to create a board from an existing project or saved filter.
6. Enter the board name and complete the creation process.

**B. Create and Start a Sprint**

1. Open **Backlog**.
2. Click **Create sprint**.
3. Add the required issues to the sprint.
4. Click **Start sprint**.
5. Enter the sprint name and duration.
6. Click **Start**.

**C. View the Sprint Report**

1. Open the project's **Reports** section.
2. Select **Sprint Report**.
3. Select the required sprint.
4. Review completed issues, incomplete issues and sprint progress.
5. Verify that the report corresponds to the selected sprint.

---

**Question 26. Create Project Components and Versions and Associate Them with Issues**

**A. Create Components**

1. Open the Jira project.
2. Go to **Project settings → Components**.
3. Click **Create component**.
4. Enter the component name and description.
5. Click **Create**.
6. Repeat for any additional components.

**B. Create Versions**

1. Go to **Project settings → Versions/Releases**.
2. Click **Create version**.
3. Enter the version name, such as Version 1.0.
4. Enter the release date and description if required.
5. Click **Add** or **Save**.

**C. Associate Components and Versions**

1. Open the issue you want to update.
2. Click **Edit**.
3. Select the appropriate component in **Component/s**.
4. Select the required version in **Fix Version/s**.
5. Click **Update**.
6. Reopen the issue and verify the saved values.

---

**Question 27. Use Jira Filters and Issue Statistics to Summarize Issues**

**A. Filter Issues**

1. Open **Filters → Search work items**.
2. Switch to **Advanced search** if you want to use JQL.
3. Enter a query such as:

   ```sql
   project = DEMO ORDER BY created DESC
   ```

4. Replace `DEMO` with your actual project key.
5. Click **Search**.
6. Use additional conditions for status, assignee or priority if required.

**B. Save the Filter**

1. Click **Save as**.
2. Enter a filter name, such as Project Issue Summary.
3. Click **Save**.

**C. Display Issue Statistics**

1. Open **Dashboards** and create or select a dashboard.
2. Click **Add gadget**.
3. Add **Issue Statistics** or **Pie Chart**.
4. Configure the gadget using your project or saved filter.
5. Select Status, Assignee or Priority as the statistic type.
6. Click **Save** and review the displayed statistics.

---

**Question 28. Use the Jira Mobile App to Update an Issue and Check Notifications**

**A. Install and Sign In**

1. Open the Google Play Store or Apple App Store.
2. Search for the official Jira Cloud app.
3. Install and open the app.
4. Sign in using your Atlassian account.
5. Open the required project.

**B. Update the Issue**

1. Search for and open the required issue.
2. Tap the issue status or workflow action.
3. Select the required status.
4. Open the **Comments** section.
5. Enter a comment and tap **Add** or **Send**.

**C. Assign the Issue and Check Activity**

1. Open the issue details.
2. Tap **Assignee** or the **Edit** option.
3. Select the required user and save.
4. Verify the status, comment and assignee.
5. Open the activity section and check the latest updates.
6. Check the app's notifications if available.

---

**Question 29. Create a Jira Cloud Account, Create a Company-Managed Project, and Configure Details**

**A. Create an Account and Explore the Dashboard**

1. Open Jira Cloud.
2. Sign in or create an Atlassian account.
3. Open Jira and explore the dashboard.
4. Review the navigation menu and Projects section.

**B. Create a Company-Managed Project**

1. Click **Projects → Create project**.
2. Select **Scrum** or **Kanban**.
3. Choose **Company-managed** if available.
4. Click **Use template**.
5. Enter the project name and key.
6. Click **Create project**.

**C. Configure Project Details**

1. Open the created project.
2. Go to **Project settings → Details** or **Summary**.
3. Update the project name, key or description if required.
4. Save the changes.
5. Open the project board and inspect its columns and settings.

---

**Question 30. Add Team Members and Assign Roles**

**A. Add Team Members**

1. Open the Jira project.
2. Go to **Project settings → People** or **Access**.
3. Click **Add people**.
4. Enter the team member's email address or select the user.
5. Select the required project role.
6. Click **Add**.
7. Repeat for all required members.

**B. Assign Roles**

1. Open **Project settings → People**.
2. Locate the required team member.
3. Open the role selection option.
4. Select the appropriate role.
5. Save the changes if required.
6. Verify that the correct roles are displayed.

---

**Question 31. Design a Custom Workflow, Add Transitions and Conditions, and Publish It**

**A. Create a Custom Workflow**

1. Open Jira.
2. Click the **Settings** gear icon.
3. Select **Issues/Work items → Workflows**.
4. Click **Add workflow** or select an existing workflow to edit.
5. Enter the workflow name.

**B. Add Statuses, Transitions and Conditions**

1. Open the workflow editor.
2. Add the required statuses, such as To Do, In Progress, Review and Done.
3. Add transitions between the statuses.
4. Connect the statuses in the required order.
5. Configure transition conditions or validators if required.
6. Save the workflow draft.

**C. Publish and Associate the Workflow**

1. Publish the workflow.
2. Open **Workflow schemes** in Jira settings.
3. Create or edit a workflow scheme.
4. Associate the workflow with the appropriate issue types.
5. Associate the scheme with the required project.
6. Complete any migration prompts.
7. Open an issue and test the workflow transitions.

---

**Question 32. Configure a Scrum Board, Start a Sprint, Complete It, and Generate a Sprint Report**

**A. Create or Configure a Scrum Board**

1. Open your Scrum project.
2. Open **Boards → Create board**, if a board is not already available.
3. Select **Scrum board**.
4. Choose the existing project or a saved filter as the board's source.
5. Enter the board name and create it.
6. Open the board and select **Backlog**.

**B. Create and Start a Sprint**

1. Click **Create sprint**.
2. Add the required issues to the sprint.
3. Click **Start sprint**.
4. Enter the sprint name, duration and dates if requested.
5. Click **Start**.
6. Move issues across the board as work progresses.

**C. Complete the Sprint and Generate a Report**

1. Open the active sprint's Scrum board.
2. Ensure that completed issues are in the Done column.
3. Click **Complete sprint** when the sprint is ready to close.
4. Review any incomplete issues and choose where they should go.
5. Confirm completion.
6. Open **Reports → Sprint Report**.
7. Select the completed sprint and review the report.

---

**Question 33. Generate Burndown and Velocity Charts, Create Issue Statistics, and Build a Dashboard**

**A. Generate Burndown and Velocity Charts**

1. Open your Scrum project.
2. Select **Reports** from the project sidebar.
3. Open **Burndown Chart**.
4. Select the required sprint if prompted.
5. Review the remaining work over the sprint duration.
6. Return to Reports and select **Velocity Chart**.
7. Review completed work across the available sprints. Historical data may be needed for meaningful results.

**B. Create a Pie Chart or Issue Statistics Report**

1. Open **Dashboards → View all dashboards**.
2. Create a dashboard or open an existing one.
3. Click **Add gadget**.
4. Add **Pie Chart** or **Issue Statistics**.
5. Configure the gadget with the required project or saved filter.
6. Select Status, Assignee or Priority as the statistic type.
7. Save the configuration.

**C. Create a Custom Dashboard**

1. Open **Dashboards → Create dashboard**.
2. Enter the dashboard name.
3. Click **Create**.
4. Click **Add gadget**.
5. Add the required gadgets, such as Pie Chart, Issue Statistics and Filter Results.
6. Configure each gadget with the appropriate project or saved filter.
7. Save the gadget settings and verify that the dashboard displays the results.

---

**Question 34. View or Modify the Project Permission Scheme and Configure Project Roles**

**A. View and Modify the Permission Scheme**

1. Open Jira.
2. Click the **Settings** gear icon.
3. Select **Issues/Work items → Permission schemes**.
4. Locate the permission scheme associated with your project.
5. Open the scheme and review the permissions.
6. Check permissions such as Browse Projects, Create Issues, Edit Issues, Assign Issues and Transition Issues.
7. Modify a permission only if the practical requires it and you have administrator access.
8. Save the changes if required.

**B. Configure Project Roles and Assign Permissions**

1. Open the required project.
2. Go to **Project settings → People** or **Access**.
3. Click **Add people**.
4. Select the required team members.
5. Assign appropriate project roles, such as Administrator, Member or Viewer, depending on the available options.
6. Click **Add**.
7. Return to the permission scheme and verify which roles have the required permissions.
8. Test the configuration, if permitted, and verify that users have the intended access.

---

# Part 2: Python AI / Machine Learning Practicals

---

**Question 1: Define PEAS for a vacuum-cleaner agent. Classify its environment as fully/partially observable, deterministic/stochastic, and episodic/sequential. Implement a simple table-driven agent in Python.**

**PEAS Description**

| Component | Description |
|-----------|-------------|
| **Performance** | Cleanliness of rooms, minimum time and energy used |
| **Environment** | Two rooms (A and B) that may be clean or dirty |
| **Actuators** | Wheels (move left/right), suction mechanism |
| **Sensors** | Location sensor, dirt sensor |

**Environment Classification**

| Property | Classification | Reason |
|----------|----------------|--------|
| Observability | Partially observable | The agent senses only its current room |
| Determinism | Deterministic | Actions have predictable results (in the basic model) |
| Episodes | Sequential | Current actions affect future cleanliness |

**Python program:**

```python
table = {
    ('A', 'Dirty'): 'Suck',
    ('A', 'Clean'): 'Right',
    ('B', 'Dirty'): 'Suck',
    ('B', 'Clean'): 'Left'
}

location = input("Enter location (A/B): ").strip().upper()
status = input("Enter status (Dirty/Clean): ").strip().title()

action = table.get((location, status), "No rule defined")
print("Action:", action)
```

**Sample output / result:** For input `A` and `Dirty`, the output is `Action: Suck`.

---

**Question 2: Define PEAS for an autonomous taxi and classify its task environment using suitable examples.**

**Answer:**

| Component | Description |
|-----------|-------------|
| **Performance** | Safety, reaching destination, passenger comfort, low time and cost |
| **Environment** | Roads, traffic, pedestrians, passengers and signals |
| **Actuators** | Steering, brakes, accelerator, horn and indicators |
| **Sensors** | Cameras, GPS, radar, LiDAR and speedometer |

**Environment Classification:**

| Property | Classification | Example |
|----------|----------------|---------|
| Observability | Partially observable | A pedestrian is hidden behind a bus. |
| Determinism | Stochastic | Another vehicle changes lanes unexpectedly. |
| Episodes | Sequential | Braking affects future movement. |
| Dynamics | Dynamic | Traffic changes while driving. |
| State | Continuous | Speed and position vary continuously. |
| Agents | Multi-agent | Other drivers and pedestrians interact. |

**Conclusion:** An autonomous taxi operates in a complex, partially observable, stochastic and dynamic environment.

---

**Question 3: Implement Breadth-First Search (BFS) in Python to find the shortest path in an 8-puzzle. Use the given initial and goal configurations.**

**Answer:** BFS explores states level by level and finds the shortest path when each move has equal cost. The example below uses `0` for the blank; replace `start` and `goal` with the configurations supplied by your instructor.

**Python program:**

```python
from collections import deque

start = (1, 2, 3, 4, 5, 6, 0, 7, 8)  # 0 is blank
goal = (1, 2, 3, 4, 5, 6, 7, 8, 0)

queue = deque([(start, [])])
visited = {start}

while queue:
    state, path = queue.popleft()

    if state == goal:
        print("Moves:", path)
        print("Total moves:", len(path))
        break

    z = state.index(0)
    row, col = divmod(z, 3)

    options = [
        ("Up", z - 3, row > 0),
        ("Down", z + 3, row < 2),
        ("Left", z - 1, col > 0),
        ("Right", z + 1, col < 2)
    ]

    for name, pos, valid in options:
        if valid:
            new = list(state)
            new[z], new[pos] = new[pos], new[z]
            new = tuple(new)

            if new not in visited:
                visited.add(new)
                queue.append((new, path + [name]))
else:
    print("No solution found")
```

**Sample output / result:** For the example start state, moves are `['Right', 'Right']`; total moves: `2`.

---

**Question 4: Solve the 4-litre and 3-litre water-jug problem using Depth-First Search (DFS) to obtain exactly 2 litres. Display the sequence of states.**

**Answer:** Represent a state as `(amount in 4-litre jug, amount in 3-litre jug)`. DFS explores fill, empty and pour actions until one jug contains exactly 2 litres.

**Python program:**

```python
def dfs(a, b, path, visited):
    state = (a, b)

    if state in visited:
        return None

    visited.add(state)
    path = path + [state]

    if a == 2 or b == 2:
        return path

    x = min(a, 3 - b)  # pour 4L jug into 3L jug
    y = min(b, 4 - a)  # pour 3L jug into 4L jug

    next_states = [
        (4, b), (a, 3), (0, b), (a, 0),
        (a - x, b + x), (a + y, b - y)
    ]

    for na, nb in next_states:
        if (na, nb) != state:
            result = dfs(na, nb, path, visited)
            if result:
                return result

    return None


solution = dfs(0, 0, [], set())

print("Sequence of states:")
for state in solution:
    print(state)
```

**Sample output / result:** The sequence ends at a state where either jug contains 2 litres, for example `(0, 2)`.

---

**Question 5: Implement Linear Regression using scikit-learn on a suitable dataset. Display model predictions and an evaluation metric.**

**Answer:** The California Housing dataset is used to predict a continuous target. The first download may require internet access.

**Python program:**

```python
from sklearn.datasets import fetch_california_housing
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error

data = fetch_california_housing()
X, y = data.data, data.target

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, random_state=42
)

model = LinearRegression()
model.fit(X_train, y_train)

predictions = model.predict(X_test)

print("Actual values:", y_test[:5])
print("Predictions:", predictions[:5])
print("Mean Squared Error:", mean_squared_error(y_test, predictions))
```

**Sample output / result:** The program prints five actual values, five predictions and Mean Squared Error (MSE).

**Note:** A lower MSE generally indicates smaller prediction errors on the same dataset.

---

**Question 6: Implement a Decision Tree classifier using the Iris dataset. Display predictions and classification accuracy.**

**Answer:** Train a Decision Tree classifier on Iris flower measurements and labels.

**Python program:**

```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import accuracy_score

iris = load_iris()

X_train, X_test, y_train, y_test = train_test_split(
    iris.data, iris.target, test_size=0.3, random_state=42
)

model = DecisionTreeClassifier(random_state=42)
model.fit(X_train, y_train)

predictions = model.predict(X_test)

print("Predictions:", predictions[:10])
print("Accuracy:", accuracy_score(y_test, predictions))
```

**Sample output / result:** The program displays predicted class labels and accuracy (between 0 and 1).

---

**Question 7: Implement Decision Tree Regression on a suitable regression dataset and display predictions with an evaluation metric.**

**Answer:** Use `DecisionTreeRegressor` on the California Housing dataset.

**Python program:**

```python
from sklearn.datasets import fetch_california_housing
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeRegressor
from sklearn.metrics import mean_squared_error

data = fetch_california_housing()

X_train, X_test, y_train, y_test = train_test_split(
    data.data, data.target, test_size=0.2, random_state=42
)

model = DecisionTreeRegressor(max_depth=5, random_state=42)
model.fit(X_train, y_train)

predictions = model.predict(X_test)

print("Predictions:", predictions[:5])
print("MSE:", mean_squared_error(y_test, predictions))
print("R2 Score:", model.score(X_test, y_test))
```

**Sample output / result:** The program displays predictions, Mean Squared Error and R² score.

---

**Question 8: Implement a k-Nearest Neighbors (kNN) classifier using scikit-learn. Split the dataset and display test accuracy.**

**Answer:** Use the Iris dataset and k = 3 nearest neighbours.

**Python program:**

```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.neighbors import KNeighborsClassifier

iris = load_iris()

X_train, X_test, y_train, y_test = train_test_split(
    iris.data, iris.target, test_size=0.3, random_state=42
)

model = KNeighborsClassifier(n_neighbors=3)
model.fit(X_train, y_train)

print("Predictions:", model.predict(X_test[:10]))
print("Test Accuracy:", model.score(X_test, y_test))
```

**Sample output / result:** The program displays predicted class labels and test accuracy.

---

**Question 9: Perform multiclass classification using Logistic Regression or a Decision Tree on a suitable dataset. Display the accuracy.**

**Answer:** Use Logistic Regression to classify Iris flowers into three species.

**Python program:**

```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression

iris = load_iris()

X_train, X_test, y_train, y_test = train_test_split(
    iris.data, iris.target, test_size=0.3, random_state=42
)

model = LogisticRegression(max_iter=5000)
model.fit(X_train, y_train)

print("Predictions:", model.predict(X_test[:5]))
print("Accuracy:", model.score(X_test, y_test))
```

**Sample output / result:** The program displays predictions and accuracy.

---

**Question 10: Analyze a public dataset for class imbalance and possible bias. Display class counts and briefly discuss limitations in the data.**

**Answer:** Use the public Iris dataset and count samples in each class.

**Python program:**

```python
from sklearn.datasets import load_iris
import pandas as pd

iris = load_iris()

df = pd.DataFrame(iris.data, columns=iris.feature_names)
df["Species"] = iris.target

print(df["Species"].value_counts().sort_index())
```

**Sample output / result:**

| Class | Samples |
|-------|---------|
| 0 | 50 |
| 1 | 50 |
| 2 | 50 |

**Discussion:** Iris is balanced by class count, but it is small and contains only three species. Balanced counts do not rule out other forms of bias.

---

**Question 11: Implement Naïve Bayes classification using a small dataset, and show how the dataset is divided into training and testing sets.**

**Answer:** Encode a small weather dataset, split it into training and testing sets, and train Categorical Naïve Bayes.

**Python program:**

```python
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import OrdinalEncoder, LabelEncoder
from sklearn.naive_bayes import CategoricalNB

weather = [
    ["Sunny"], ["Sunny"], ["Rainy"], ["Rainy"], ["Overcast"],
    ["Overcast"], ["Sunny"], ["Rainy"], ["Overcast"], ["Sunny"]
]
play = ["No", "No", "Yes", "Yes", "Yes", "Yes", "No", "Yes", "Yes", "No"]

enc = OrdinalEncoder()
X = enc.fit_transform(weather)

le = LabelEncoder()
y = le.fit_transform(play)

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.3, random_state=42, stratify=y
)

# min_categories=3 avoids errors if a category is missing from the training split
model = CategoricalNB(min_categories=3)
model.fit(X_train, y_train)

print("Training samples:", len(X_train))
print("Testing samples:", len(X_test))

test = enc.transform([["Overcast"]])
print("Prediction:", le.inverse_transform(model.predict(test))[0])
```

**Sample output / result:** Training samples: 7; Testing samples: 3; a prediction is printed.

---

**Question 12: Implement a machine-learning workflow using a suitable dataset: load with Pandas, handle missing values or scale features, split into training and testing sets, train a classifier, and display training and testing accuracy.**

**Answer:** This workflow loads Iris with Pandas, fills missing values if present, scales features, splits the data and trains a Decision Tree.

**Python program:**

```python
import pandas as pd
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.tree import DecisionTreeClassifier

iris = load_iris()

df = pd.DataFrame(iris.data, columns=iris.feature_names)
df["Species"] = iris.target

df = df.fillna(df.mean())  # Iris has no missing values

X = df.drop("Species", axis=1)
y = df["Species"]

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.3, random_state=42
)

scaler = StandardScaler()
X_train = scaler.fit_transform(X_train)
X_test = scaler.transform(X_test)

model = DecisionTreeClassifier(random_state=42)
model.fit(X_train, y_train)

print("Training Accuracy:", model.score(X_train, y_train))
print("Testing Accuracy:", model.score(X_test, y_test))
```

**Sample output / result:** Training Accuracy and Testing Accuracy are printed. Iris has no missing values, so `fillna` does not change it.

---

**Question 13: Write a Python program to solve the 8-puzzle using Breadth-First Search (BFS) and display the sequence of moves.**

**Answer:** This is the same BFS approach as Question 3. The program prints the move sequence and its length.

**Python program:**

```python
from collections import deque

start = (1, 2, 3, 4, 5, 6, 0, 7, 8)  # 0 is blank
goal = (1, 2, 3, 4, 5, 6, 7, 8, 0)

queue = deque([(start, [])])
visited = {start}

while queue:
    state, path = queue.popleft()

    if state == goal:
        print("Moves:", path)
        print("Total moves:", len(path))
        break

    z = state.index(0)
    row, col = divmod(z, 3)

    options = [
        ("Up", z - 3, row > 0),
        ("Down", z + 3, row < 2),
        ("Left", z - 1, col > 0),
        ("Right", z + 1, col < 2)
    ]

    for name, pos, valid in options:
        if valid:
            new = list(state)
            new[z], new[pos] = new[pos], new[z]
            new = tuple(new)

            if new not in visited:
                visited.add(new)
                queue.append((new, path + [name]))
else:
    print("No solution found")
```

**Sample output / result:** For the sample state: `['Right', 'Right']`; total moves: `2`.

---

**Question 14: Use Depth-First Search (DFS) in Python to solve the 4-litre and 3-litre water-jug problem and obtain exactly 2 litres.**

**Answer:** This uses the same state representation and DFS method as Question 4.

**Python program:**

```python
def dfs(a, b, path, visited):
    state = (a, b)

    if state in visited:
        return None

    visited.add(state)
    path = path + [state]

    if a == 2 or b == 2:
        return path

    x = min(a, 3 - b)  # pour 4L jug into 3L jug
    y = min(b, 4 - a)  # pour 3L jug into 4L jug

    next_states = [
        (4, b), (a, 3), (0, b), (a, 0),
        (a - x, b + x), (a + y, b - y)
    ]

    for na, nb in next_states:
        if (na, nb) != state:
            result = dfs(na, nb, path, visited)
            if result:
                return result

    return None


solution = dfs(0, 0, [], set())

print("Sequence of states:")
for state in solution:
    print(state)
```

**Sample output / result:** The state sequence reaches a state where either jug contains exactly 2 litres.

---

**Question 15: Write a Python program applying Bayes' Rule to calculate the probability of disease after a positive test result using the given scenario.**

**Answer:** Example scenario: disease prevalence 1%, sensitivity 99%, and false-positive rate 5%. Bayes' Rule combines these values to find the probability of disease given a positive result.

**Python program:**

```python
prevalence = 0.01
sensitivity = 0.99
false_positive_rate = 0.05

p_positive = (
    sensitivity * prevalence
    + false_positive_rate * (1 - prevalence)
)

p_disease_given_positive = sensitivity * prevalence / p_positive

print("Probability of disease after positive test:",
      round(p_disease_given_positive * 100, 2), "%")
```

**Sample output / result:** `Probability of disease after positive test: 16.67 %`

---

**Question 16: Implement a Naïve Bayes classifier using scikit-learn on a small weather or spam dataset and display its prediction.**

**Answer:** Use the small weather dataset and `CategoricalNB` to predict whether to play when the weather is Overcast.

**Python program:**

```python
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import OrdinalEncoder, LabelEncoder
from sklearn.naive_bayes import CategoricalNB

weather = [
    ["Sunny"], ["Sunny"], ["Rainy"], ["Rainy"], ["Overcast"],
    ["Overcast"], ["Sunny"], ["Rainy"], ["Overcast"], ["Sunny"]
]
play = ["No", "No", "Yes", "Yes", "Yes", "Yes", "No", "Yes", "Yes", "No"]

enc = OrdinalEncoder()
X = enc.fit_transform(weather)

le = LabelEncoder()
y = le.fit_transform(play)

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.3, random_state=42, stratify=y
)

model = CategoricalNB(min_categories=3)
model.fit(X_train, y_train)

print("Training samples:", len(X_train))
print("Testing samples:", len(X_test))

test = enc.transform([["Overcast"]])
print("Prediction:", le.inverse_transform(model.predict(test))[0])
```

**Sample output / result:** The program prints the training/testing sizes and a prediction for Overcast.

---

**Question 17: Use the MNIST dataset to build a binary classifier for digit versus not-digit and evaluate its performance.**

**Answer:** For a lightweight practical, use scikit-learn's `load_digits` dataset (8×8 images) as an MNIST-like alternative. The binary target is digit 5 versus not 5.

**Python program:**

```python
from sklearn.datasets import load_digits
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score

digits = load_digits()  # Small 8x8 dataset, MNIST-like

X = digits.data
y = (digits.target == 5).astype(int)  # 1 = digit 5, 0 = not 5

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.25, random_state=42, stratify=y
)

model = LogisticRegression(max_iter=5000)
model.fit(X_train, y_train)

predictions = model.predict(X_test)

print("Predictions (1=5, 0=not 5):", predictions[:10])
print("Accuracy:", accuracy_score(y_test, predictions))
```

**Sample output / result:** The program displays predictions (1 means digit 5; 0 means not 5) and accuracy.

**Note:** This is not the full 28×28 MNIST dataset; use a downloaded MNIST dataset if your instructor requires MNIST specifically.

---

**Question 18: Implement a k-Nearest Neighbors (kNN) classifier using a suitable dataset and evaluate its accuracy.**

**Answer:** Use the Iris dataset with `KNeighborsClassifier` and k = 3.

**Python program:**

```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.neighbors import KNeighborsClassifier

iris = load_iris()

X_train, X_test, y_train, y_test = train_test_split(
    iris.data, iris.target, test_size=0.3, random_state=42
)

model = KNeighborsClassifier(n_neighbors=3)
model.fit(X_train, y_train)

print("Predictions:", model.predict(X_test[:10]))
print("Test Accuracy:", model.score(X_test, y_test))
```

**Sample output / result:** The program displays predictions and test accuracy.

---

**Question 19: Perform multiclass classification using Logistic Regression or a Decision Tree on a suitable dataset.**

**Answer:** Use Logistic Regression to predict the three Iris species.

**Python program:**

```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression

iris = load_iris()

X_train, X_test, y_train, y_test = train_test_split(
    iris.data, iris.target, test_size=0.3, random_state=42
)

model = LogisticRegression(max_iter=5000)
model.fit(X_train, y_train)

print("Predictions:", model.predict(X_test[:5]))
print("Accuracy:", model.score(X_test, y_test))
```

**Sample output / result:** The program prints five predictions and the model accuracy.

---

**Question 20: Select a public dataset and examine possible class imbalance by displaying the number of samples in each class.**

**Answer:** Count the class labels in the Iris dataset.

**Python program:**

```python
from sklearn.datasets import load_iris
import pandas as pd

iris = load_iris()

df = pd.DataFrame(iris.data, columns=iris.feature_names)
df["Species"] = iris.target

print(df["Species"].value_counts().sort_index())
```

**Sample output / result:** Each of the three classes contains 50 samples.

**Observation:** The dataset has equal class counts.

---

**Question 21: Write a Python program to solve a water-jug problem using DFS; use jug capacities of your choice and reach a specified target amount.**

**Answer:** Use a 5-litre jug and a 3-litre jug to obtain exactly 4 litres in the first jug.

**Python program:**

```python
def dfs(a, b, path, visited):
    state = (a, b)

    if state in visited:
        return None

    visited.add(state)
    path = path + [state]

    if a == 4:
        return path

    x = min(a, 3 - b)  # pour 5L jug into 3L jug
    y = min(b, 5 - a)  # pour 3L jug into 5L jug

    next_states = [
        (5, b), (a, 3), (0, b), (a, 0),
        (a - x, b + x), (a + y, b - y)
    ]

    for na, nb in next_states:
        if (na, nb) != state:
            result = dfs(na, nb, path, visited)
            if result:
                return result

    return None


solution = dfs(0, 0, [], set())

for state in solution:
    print(state)
```

**Sample output / result:** The program prints a sequence reaching a state where the 5-litre jug contains 4 litres, such as `(4, 0)`.

---

**Question 22: Train a Naïve Bayes classifier on a small dataset, then discuss one possible source of bias or class imbalance in that dataset.**

**Answer:** Train Naïve Bayes on the small weather dataset. A possible limitation is that a tiny dataset may not represent real weather conditions; if the Yes/No classes are imbalanced, the model may favour the majority class.

**Python program:**

```python
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import OrdinalEncoder, LabelEncoder
from sklearn.naive_bayes import CategoricalNB

weather = [
    ["Sunny"], ["Sunny"], ["Rainy"], ["Rainy"], ["Overcast"],
    ["Overcast"], ["Sunny"], ["Rainy"], ["Overcast"], ["Sunny"]
]
play = ["No", "No", "Yes", "Yes", "Yes", "Yes", "No", "Yes", "Yes", "No"]

enc = OrdinalEncoder()
X = enc.fit_transform(weather)

le = LabelEncoder()
y = le.fit_transform(play)

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.3, random_state=42, stratify=y
)

model = CategoricalNB(min_categories=3)
model.fit(X_train, y_train)

print("Training samples:", len(X_train))
print("Testing samples:", len(X_test))

test = enc.transform([["Overcast"]])
print("Prediction:", le.inverse_transform(model.predict(test))[0])
```

**Sample output / result:** The program prints training/testing sample counts and a prediction.

---

**Question 23: Build a Decision Tree classifier and assess possible bias and class imbalance in the selected dataset.**

**Answer:** Use Iris, display class counts, and compare training and testing accuracy.

**Python program:**

```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
import pandas as pd

iris = load_iris()
X, y = iris.data, iris.target

print("Class counts:")
print(pd.Series(y).value_counts().sort_index())

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.3, random_state=42
)

model = DecisionTreeClassifier(random_state=42)
model.fit(X_train, y_train)

print("Training accuracy:", model.score(X_train, y_train))
print("Testing accuracy:", model.score(X_test, y_test))
```

**Sample output / result:** Iris has equal class counts. A deep tree can overfit; equal class counts do not eliminate all data bias.

---

**Question 24: Demonstrate a basic machine-learning workflow: load a dataset with Pandas, preprocess it, split it, train a classifier and report training/testing accuracy.**

**Answer:** Load Iris into a DataFrame, fill missing values if any, scale the features, split the dataset, train a Decision Tree and report accuracy.

**Python program:**

```python
import pandas as pd
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.tree import DecisionTreeClassifier

iris = load_iris()

df = pd.DataFrame(iris.data, columns=iris.feature_names)
df["Species"] = iris.target

df = df.fillna(df.mean())  # Iris has no missing values

X = df.drop("Species", axis=1)
y = df["Species"]

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.3, random_state=42
)

scaler = StandardScaler()
X_train = scaler.fit_transform(X_train)
X_test = scaler.transform(X_test)

model = DecisionTreeClassifier(random_state=42)
model.fit(X_train, y_train)

print("Training Accuracy:", model.score(X_train, y_train))
print("Testing Accuracy:", model.score(X_test, y_test))
```

**Sample output / result:** Training and testing accuracy are printed.

---

**Question 25: Implement Linear Regression using scikit-learn on a suitable regression dataset and evaluate the model.**

**Answer:** Use California Housing and evaluate predictions with Mean Squared Error.

**Python program:**

```python
from sklearn.datasets import fetch_california_housing
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error

data = fetch_california_housing()
X, y = data.data, data.target

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, random_state=42
)

model = LinearRegression()
model.fit(X_train, y_train)

predictions = model.predict(X_test)

print("Actual values:", y_test[:5])
print("Predictions:", predictions[:5])
print("Mean Squared Error:", mean_squared_error(y_test, predictions))
```

**Sample output / result:** The program displays actual values, predictions and MSE.

---

**Question 26: Implement a Decision Tree classifier using the Iris dataset or another suitable dataset.**

**Answer:** Use the Iris dataset and `DecisionTreeClassifier`.

**Python program:**

```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import accuracy_score

iris = load_iris()

X_train, X_test, y_train, y_test = train_test_split(
    iris.data, iris.target, test_size=0.3, random_state=42
)

model = DecisionTreeClassifier(random_state=42)
model.fit(X_train, y_train)

predictions = model.predict(X_test)

print("Predictions:", predictions[:10])
print("Accuracy:", accuracy_score(y_test, predictions))
```

**Sample output / result:** The program displays predictions and classification accuracy.

---

**Question 27: Implement Decision Tree regression on a suitable regression dataset and evaluate its predictions.**

**Answer:** Use California Housing and `DecisionTreeRegressor`.

**Python program:**

```python
from sklearn.datasets import fetch_california_housing
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeRegressor
from sklearn.metrics import mean_squared_error

data = fetch_california_housing()

X_train, X_test, y_train, y_test = train_test_split(
    data.data, data.target, test_size=0.2, random_state=42
)

model = DecisionTreeRegressor(max_depth=5, random_state=42)
model.fit(X_train, y_train)

predictions = model.predict(X_test)

print("Predictions:", predictions[:5])
print("MSE:", mean_squared_error(y_test, predictions))
print("R2 Score:", model.score(X_test, y_test))
```

**Sample output / result:** The program displays predicted values, MSE and R² score.

---

**Question 28: Select a public dataset and analyze possible bias and class imbalance. Report the class distribution and observations.**

**Answer:** Use the Iris dataset to count samples in each species.

**Python program:**

```python
from sklearn.datasets import load_iris
import pandas as pd

iris = load_iris()

df = pd.DataFrame(iris.data, columns=iris.feature_names)
df["Species"] = iris.target

print(df["Species"].value_counts().sort_index())
```

**Sample output / result:**

| Class | Samples |
|-------|---------|
| 0 | 50 |
| 1 | 50 |
| 2 | 50 |

**Observation:** The dataset is balanced by class count, but its small size and limited species coverage are limitations.

---

**Question 29: Create a simple table-driven agent in Python. Define its percepts, actions and table, then test it with sample inputs.**

**Answer:** Percepts: location and room status. Actions: Suck, Move Right and Move Left. The table maps each percept to an action.

**Python program:**

```python
table = {
    ("A", "Dirty"): "Suck",
    ("A", "Clean"): "Move Right",
    ("B", "Dirty"): "Suck",
    ("B", "Clean"): "Move Left"
}

percepts = [
    ("A", "Dirty"), ("A", "Clean"),
    ("B", "Dirty"), ("B", "Clean")
]

for percept in percepts:
    print("Percept:", percept, "Action:", table[percept])
```

**Sample output / result:**

| Percept | Action |
|---------|--------|
| `('A', 'Dirty')` | Suck |
| `('A', 'Clean')` | Move Right |
| `('B', 'Dirty')` | Suck |
| `('B', 'Clean')` | Move Left |
