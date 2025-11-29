01_jira_connect.json

**Jira Issue Creation Agent**
This agent facilitates the automatic creation of issues within Jira Software.

**Functionality**
The primary function of this agent is to create new issues in Jira. It takes a Summary and a Description as input for the issue.

**How to Use**
This agent can be invoked to create a Jira issue by providing the necessary details:

**Parameters**
Summary (string, required): A concise title for the Jira issue.
Description (string, required): A detailed explanation of the issue.
Example Usage (conceptual)
While the exact method of invoking this agent will depend on the platform it's integrated with, conceptually, you would call a function like this:

create_jira_issue(
    Summary="Bug: Application crashes on login",
    Description="The application crashes consistently when a user attempts to log in with valid credentials. This affects all users and prevents access to the system."
)
**Available Actions**
Create an issue in Jira Software: This action allows the agent to create a new Jira issue with a specified summary and description.
