# Jira-Smart-Commits

Testing Smart Commits

Test 1
Send comment to jira issue (issuetype = story) from GitHub with GA email address as primary

WT-3 #comment test comments with GA email as primary

Test 2
Send comment to jira issue (issuetype = task) from GitHub to jira with GA email address as primary

WT-5 #comment Test comments to task (GA email as primary)

Test 1 and 2 unsuccessful

Test 3
Make primary email address public and reomve secondary email 

WT-3 #comment Test 3 change email addresses

Test 4
Include some angle brackets

<WT-3> #comment Test with angle brackets around issue key

Test 5
Test with angle brackets around issue key and comment text

<WT-3> #comment <Test with angle brackets around issue key and comment text>

Test 6
Put Smart Commit comment into commit title without angle brackets
TEST 6 WAS SUCCESSFUL in sending text "Test without brackets inside github commit title" to Comments section in Jira AND a commit update to Developer section in Jira

Test 7
Put Smart Commit comment into commit description without angle brackets

Test 8
Send Smart Commit comment to PYR-12 from this github account
FAILED - Email from Jira saying that PYR-12 does not exist

Test 9
Add gmail account back inand test as test 7

Test 10
Make GA email account private again
