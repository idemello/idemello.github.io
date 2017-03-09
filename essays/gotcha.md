---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---
As we move on in the semester our class has started to learn about a new JavaScript framework known as Meteor. The Meteor framework is powerful, as it can be used to create web applications, integrate complicated features, and much more. However, with that much power there comes a very steep learning curve. To practice Meteor we have done several tutorials, and are currently working on a small project called digits. This project consists of creating a small address book where we can edit and add contacts.

## The sky is falling
A problem that I am currently having with learning Meteor, specifically within digits is that there is a massive amount of files to keep track of. If there is an update in one .js or .html file, then there are very specific files that need to be updated in order to make your changes actually happen on the Meteor server. While through practice I have found that 50% of the time this is caused by missing an import. There are many cases where if something doesn’t match a file in the related files, there is a lot of searching that needs to be done.
Another problem that I am having with Meteor is that the way that templates are formatted remain a small mystery to me at times. With the simpler templates, there are not terrible. However, seeing statements such as  “{{pathFor 'Edit_Stuff_Page' _id=stuff._id}}”, has a lot of new syntax that I am not quite comfortable with.

## Overkill
A problem that I was having when we first started Meteor was the installation of Meteor every time I wanted to start a project. Running the meteor npm install command would return a huge list of errors that I had no idea how to deal with. So I spent a long time changing the way I installed the files, how I worked with the Windows 10 command line, I even tried removing and reinstalling the files multiple times. Even after all of this I could not get the program to work. 
So what was my solution to the trouble I was receiving from the Meteor/Windows 10 interaction? It was simple. I installed Linux natively to my computer. While this did have the overhead of having to re-configure intelliJ, reinstall my programs, and find all my bookmarks. As soon as I opened my command prompt I simply typed curl https://install.meteor.com/ | sh into my termial and within minutes it was done. No errors, no long warnings or anything. So after struggling with Windows 10 for hours to get this to work, I was able to get meteor up and running within minutes on Ubuntu.
