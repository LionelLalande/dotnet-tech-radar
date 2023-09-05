---
title: "Feature Folders"
ring: adopt
quadrant: methods-and-patterns
tags: []
--- 
Recently, a new approach in the organization of folder structure for large projects, called Feature Folders, has become very popular. This is especially true for the teams that use the Vertical slice approach.

When organizing a project by features, you usually create a root folder (for example, Features), to which you will have subfolders for each of the features. This is very similar to how Areas are organized. However, each folder with feature will include all the necessary controllers, View, ViewModel, etc. In most cases, as a result, we will get a folder with, perhaps, 5 to 15 files that are all closely related to each other. You can easily keep in focus all contents of the feature folder in the Solution Explorer.

Advantages of using Feature Folders:

- In contrast to Areas, we do not need additional routes
- Reduces navigation and file search time
- Can be easily scaled and modified independently of other features
- Allows you to keep fewer open folders in the Solution Explorer
- Gives an understanding of what exactly the application does and what files are needed for this
- Gives us the option to reuse the feature in other projects by simply copying a folder
- In the version control system, it is possible to see all the changes that relate to a particular feature
- Improves file coupling
