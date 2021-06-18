# Course File Repository for Introduction to Web Development

The files in this repository are provided for use in the online course, Introduction to Web Development, offered through The Software Guild, a Wiley brand.

For more information about this course or other courses we offer, please visit our website at [TheSoftwareGuild.com](https://TheSoftwareGuild.com).

![The Software Guild](https://the-software-guild.s3.amazonaws.com/tsg-logos/swg_logo-black.png)


## notes  
git pull origin master

This command tells git to pull down any changes made to the repository since the last commit (by anyone from any computer) and ensures that your copy of the repository is up to date.

In this command, the word origin refers to your online repository, as referenced by the URL you used when you cloned the repository.

The word master refers to the main branch of the repository. For this course, you don't really need to use or understand branches, but as a quick explanation, you can think of a branch as a copied version of the original set of files. For example, one developer on a team may make their own branch of the repository so they can make changes without affecting the code in the file used by other team members. Once that developer has finished making and testing the changes, they can merge the changes back to the master branch.

### Keeping Content Synchronized  
As you work through this course and add, edit, or delete files in your repository folder, remember to synchronize significant changes with your GitHub repository, using the four steps we just walked through:

git add --all
git commit -m "commit message"
git pull origin master
git push origin master
You should complete these steps at the end of every coding activity in the course, but you can do them more often, if you wish, especially if you plan to use multiple computers as you work through this course.

### Set up Another Computer (Optional)  
If you plan to use more than one computer for this course, you should use the following steps from this page on each computer:

Create a local repository folder.
Initialize Git in that folder.
Clone your remote GitHub repository to the new folder.
You will then use the synchronization steps that follow to keep files synchronized between your computer(s) and your GitHub repository.
