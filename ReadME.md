git push --set-upstream origin deploy

gh auth login

gh pr create --base master --head deploy --title "deployment $(Build.BuildNumber)" --body "adding read me"