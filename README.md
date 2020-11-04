# alfred-jira-worklogs
Alfred Workflow for creating worklogs in Jira

## Instructions
1. Install in Alfred
2. Set the environment variables
    - `jiraHost`: the hostname of your Jira instance (without https://)
    - `jiraUser`: your Jira username
    - `jiraPassword`: your Jira password
3. Log time with `jlog ticketId,comment,timeInHours`, e.g. `jlog ABC-123,This is a worklog comment,1.5`
