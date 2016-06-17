# fastlane_actions
Set of cusom acitons for Fastlane toolset, used in my projects

## Actions
* __prepare_snapfiles__ - creates individual Snapfile for each given device/locale combination, to let run snapshot on each of them individually, and have individual report 
* __update_changelog__ - gets contents of CHANGELOG_CURRENT.md and appends them to CHANGELOG.md, adding app version and current date

## Docs
You can see detail docs for each action via `fastlane actions <action_name>`

## Setup
1. Add [import_from_git](https://github.com/SemenovAlexander/fastlane_actions/) to your Fastfile
2. Copy `fastlane/assets` folder from repository to your fastlane folder

Look though [Fastlane documentation](https://github.com/fastlane/fastlane/blob/master/fastlane/docs/README.md) for details on using Fastlane

