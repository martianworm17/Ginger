# When Ginger is connected with Source Control like Git or SVN an icon will indicate the status of the item

# New, Changed, No Change
- `New` <img src="https://github.com/Ginger-Automation/Ginger/blob/master/Ginger/DeveloperZone/Documents/Images/SourceControl/%40SourceControlItemAdded_10x10.png">
The item was added locally and was not checked-in yet
- `Changed` <img src="https://github.com/Ginger-Automation/Ginger/blob/master/Ginger/DeveloperZone/Documents/Images/SourceControl/%40SourceControlItemChange_10x10.png">
The item exist in Source Control but was modified locally
- `No Change` <img src="https://github.com/Ginger-Automation/Ginger/blob/master/Ginger/DeveloperZone/Documents/Images/SourceControl/%40SourceControlItemUnchanged_10x10.png">
The item exist in source control and was not modifed

<img src="https://github.com/Ginger-Automation/Ginger/blob/master/Ginger/DeveloperZone/Documents/images/Agents.png" width="300">

- When TreeViewItem heaser is created the icon is binded to the RepositoryItem.SourceControlImage each change will automatically shown to the user

# Change can be one of the following:

- Item Was checked-in to source control - will change to NoChange
- Undo was requested 
- Relaod happen due to file changed on file system - can be by user manipulating the file outsized Ginger, or doing GetLatest, the icon status will be re-calculated
