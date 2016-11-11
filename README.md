README

This is a "Complaints" plugin to collect and manage complaints.

This is a quick POC on Jira Plugin development tutorial: https://developer.atlassian.com/jiradev/jira-platform/guides/issues/tutorial-jira-issue-crud-servlet-and-issue-search

To USE:

In theory this can be atlas-packed up into a jar and loaded into a real Jira instance, however it is only confirmed to run via the Atlassian Plugin SDK atlas-run test Jira instance.

Make sure you are logged in as admin user.

Create a project with key COMPLAIN

Make sure the issuetype ID # exists: issueInputParameters.setIssueTypeId("10000");

Servlet url if using SDK: http://localhost:2990/jira/plugins/servlet/complainer
