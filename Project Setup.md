# Setting up a collaborative space

## Learning objectives
* Understand the purpose and use of the wiki
	* Create initial project description (wiki)
* Understand use and importance of subfolder/subcomponent organization
	* Add components to a project
* Understand how to set up a centralizer location for project storage/management
	* Add collaborators to project
	* Connect an add-on to the OSF (github)

## Section Outline
* Set up study example & break room into ‘collaborative groups’ for project creation
	* 3 person groups, each working on creating one OSF project for the three of them

For most of the workshop, you’ll all be working in groups of three, pretending to be little research groups with a PI, graduate student, and research assistant. Collectively, you’ll work on building an open, transparent small scale research project from start to finish. To help with this, and because people are from a variety of different scientific disciplines here, we’re going to be using a set of example materials so everyone will be working with the same materials. These materials are from the 2012 Annual National Election Survey in the US.

I emailed all the materials to you this morning. If you open up the filed called, ‘Questionnaire’, you’ll notice that there are about 12 different questions that were asked of respondents (this is a very small subsample of the questions from the actual survey). So, over the course of the workshop, what is going to happen is that each group will decide amongst themselves, from the available materials, what there research question will be, the variables they want to use, the analyses they want to do, how they want to build and structure there project, and how open they would like the project to be at the end. 

To start off, lets count off in 3s. If you don’t have a computer with you, say ’skip’ and look on with one of the groups on either side of you. These will be your groups. All the 1s will be the PIs, all the 2s with be graduate student collaborators, and all the 3s will be research assistants. Don’t worry too much about your role, it’s not going to have a huge impact, but if you feel uncomfortable in your role and you want to switch with someone else in your group that is fine.
  

##Creating a project
	
* Describe what a ‘project’ on the OSF can be and create one for example
	* Project can be a: Lab group, organization, grant, line of research, individual study;
		* it’s basically the top level of nesting, you can nest as many things under it as you like

So, first things first, we need to go to the OSF and create our first project. A ‘project’ on the site can be anything: a lab group, an organization, a grant, a line of research, and individual experiment, etc. When you initially create a ‘project’, basically you can think about this as just the top level of a nested structure. You’ll be able to nest as many things under it later as you like. 

* Person A create a project for the group

Since we don’t have any projects yet, and we’re only going to be ‘conducting’ one experiment. Lets just create a project for that one experiment. If you are the PI in your group, if you could click on the ‘create project’ button, and give the project whatever name you like. You can also give it a short description if you want, but you don’t have to. There will be a space later to add a longer description. Then, create the project:

![Creating a project](Project_figs/creating_project.png)

	
* Orient attendees to the project overview page (title, wiki, file tree, privacy setting, GUID)
	* describe and point out main features/state of project upon creation
		* File tree: place where you can upload basically any type of file, with size limit
			* we’ll go over ways to give structure to this area and to deal with size limits later on

Alright, so if you’re a PI, you should now be seeing something that looks similar to my screen. Before we start adding content, I just want to take a minute to orient everyone to how a project looks when it’s first started. If you aren’t a PI, you can follow along on my screen for a second. All projects start out with this same screen. The ‘wiki’ is a collaborative editing space which you can use to list information about the project, things like READMEs, abstracts, research questions, outlines, etc. The file tree is how you upload files to the system, and you can upload basically any time of file that you want, everything from CSVs to word documents, to power points, to image and video files. This ‘component’ section is how you add additional structure and nesting to your project, we’ll talk more about that later, and then there is the citation widget, which shows you the automatically generated citation for the project:

![Project overview page intro](Project_figs/project_overview.png)

* Project page has GUID that you can use to direct others to the project
			* have person B try the link, see that they can’t see it
		* Project default to privates so only collaborators can see it

At the top of the screen, you’ll notice a little 5 letter string at the end of the osf.io url. This entire address is a GUID, or a permanent, unique identifier. This address has been assigned to this project page and will point back to it unless the project is deleted. Grad students and RAs, if you could type in the URL for your groups project in your browser window, try to go to the project, and see what happens?

Who can tell me what happened? [get audience feebdack]. Right, if you aren’t a PI, you’re being told that you don’t have access to the project. That’s because all project on the OSF are set to ‘private’ as a default. Which means that only people who the admins of the project have added as ‘contributors’ have access to the project and can see into it. Right now, the PI is the only contributor on the project. 


## Giving contributors access
	* Person A adds people B & C to the project as contributors
		* note contributor permissions & non-bibliographic options
	* point out autogenerated citation which now has all collaborators

Since we want this to be a collaborative project, we need to give the other two members of your teams access to the project. If you go up to the ‘sharing’ tab and click on that, this is how you can give access to additional contributors. 

![Sharing tab](Project_figs/Sharing_tab.png)

Go in and search of the names of your GS and RA, and click the + icon to add them over to the project. 

![Searching for Contributors](Project_figs/contributor_search.png)

You’ll notice that each person is given a permission setting for access to the project. There are three possible settings, ‘admin’, ‘read + write’, and ‘read’. Read access means the contributor can see into the project and can download any files they want, but they will not be able to add any files or modify any content. ‘Read + Write’ access has additional capabilities to add and modify files, but they can’t change any of the settings on the project (so for example they can’t add new contributors or change the privacy settings on the project). An administrator can do anything to the project and files. So, go ahead and give your GS and RA whatever permission settings you want.

![Altering permission settings for contributors](Project_figs/contributor_permissions.png) 

If we now go back to the project overview page, you’ll notice that now all three people are listed as contributors on the project, and that they are all now also listed in the auto generated citation for the project.

![How citation info has changed](Project_figs/contributor_citation.png)

If for some reason you wanted to give someone access to the project but did not want to give them authorship credit, perhaps your RA needs access to the project but you don’t generally give your RAs authorship, just acknowledgements, you can do this by going back to the ‘sharing’ screen and unchecking the ‘bibliographic contributor’ box next to that person’s name.

## Creating a wiki

Now that you have a project and everyone has access, the first thing to do is start to write down a bit of information about the project. This will often start out pretty loose, depending on how exploratory vs. confirmatory the study is, and over time turn into something more detailed like an abstract and/or a README file of the project. On the OSF, a good place to put this type of information is in the wiki. The wiki is a real time collaborative editor, so your whole team can work on it at once. It also can be formatted using markdown. You get into the wiki by clicking on the widget, and then click on the ‘edit’ button in the upper right to open up the editor. 


	* Person B starts, person A & C add content 
		* research question & hypothesis to start out with

Lets have you all take a minute to set up a wiki for the project. So, collaborative set up a wiki that includes the research questions you’re interested based on the data you have, and any hypotheses you might have about what you will see.

## Adding organizational structure 

	* Explain components vs. folders and demo making one versus the other
		* components have all the same functionality as projects (wikis, their own contributor settings, their own public/project settings)

Right now our project is pretty flat. It is basically just one big folder with a wiki with some basic content in it. For most projects, we’ll want to add some structure and add sections, so example some way to collect all the materials related to data together, or a way to collect all the files related to our protocol together. If we had set up a project for a lab group or an institution, you might imaging having separate sections for each person in the lab, or each line of research. You can do this in two ways on the OSF depending on your prefer. The major way to add structure and sections to a project is to add components. You do this by clicking the ‘add component’ button on the right of the screen. You can name the component whatever you want (materials, data, protocol, IRB, etc.) and you can also give it a category, though you don’t have to. Once the component is created, we can go into it and see that the inside of all components looks just like an empty project; they have their own file trees, wikis, contributor lists, privacy settings, and we can even nest components within components. So, components add structure, but they also allow you to set up areas which have different privacy settings or contributor lists from other sections in the project, which can be important for controlling access. 
		
		* folders are just ways to organize files, have no other functionality

Folder on the other hand are a little bit different. A folder is literally just a way to group a set of files, nothing more. So, if we click on the OSF storage icon you’ll notice that a ‘create folder’ button will appear. If we do this, a folder will appear which he can then name whatever we want. However, if you click on the folder, it will just expand; you won’t be taken into the folder and it doesn’t have a wiki or it’s own access settings; the access settings are the same as the project/component it lives within. So, folders are just about organizing files together, while components are good for setting up large sections of a project.  

	* Have participants collectively create structure for their project however they like

Now that I’ve explained the difference between components and filers, I’ll give you a bit of time to set up some initial structure for your project. You can set it up however you want, there isn’t necessarily a right or wrong answer. Also, don’t worry, you can always move things if you initially set it up in one way and your realize that it would be better to set it up in another way later on. Just think through what are the major categories of file types you’ll have, and whether you might want to have different contributors or public vs. private access setting for them to determine whether you want to set them up as folders or components.

* Have someone connect and add-on (github or dropbox)
	* other participants make edits to content in those add-ons
