Eclipse Zenoh project repositories CI Status

This project is based on the idea to provide information about repositories PR and to be the one stop shop to have a bird eyed view of all the currently opened pull-request in a centralized fashion.

Due to the retrieved information requires a GITHUB_TOKEN and github API has a limitation it is better to not collect the information on every request from this webpage is made. So this webpage does not really requires an application service and all the required data is stored in github pages. This information is normally retrieved, treated and stored using chain-status/action tool which is exposed as a Github Action tool, so we can customize the job execution frequency as we need.
