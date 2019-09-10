Sample configuration

Things to test & evaluate:
- Using PRs
- GH Statuses
- CircleCI Checks
- Admin/non-admin permissions
- Context groups

Invited angelisamaria (non-admin) to the team and this was reflected in CircleCI
angelisamaria can see other team members (https://circleci.com/team/gh/angcci) and the # projects followed
While logged in as angelisamaria, plan usage (https://circleci.com/gh/organizations/angcci/settings#usage) can be viewed

Attempting to create a context as angelisamaria
https://circleci.com/gh/organizations/angcci/settings#contexts > `Create Context`
Name: test > `create`
Error: Something unexpected happened
https://circleci.com/docs/2.0/contexts/#creating-and-using-a-context
`Note: Any organization member can create a context only organization administrators can restrict it with a security group.`

https://circleci.com/account/plans
Tells me the "orgs" I have permissions to, even though only one is an actual GitHub org and the other is just a user account
