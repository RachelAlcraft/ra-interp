
### Publish from github actions

https://www.seanh.cc/2022/05/21/publishing-python-packages-from-github-actions/#:~:text=The%20publish.,create%20an%20unscoped%20API%20token.

1) Set up as per above, with a publish.yml in workflows folder set to publish with an api secret.
2) Then when you make a release it will publish automatically.
3) Check success https://pypi.org/manage/projects/