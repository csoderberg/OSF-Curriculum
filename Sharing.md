# Sharing your Work


## Learning Objectives
* Understand the motivations for open sharing
* Understand important considerations before making data public
* Understand how to make your research discoverable	
* Understand how to get credit for your work


## Why share?

Now that we have created our project, uploaded all the materials, and documented our workflow, we need to decide if we want share our work, and if so what parts of it do we want to share? There are many different reasons why you might want to share your work. Many journals and funders now require that data and code be shared upon publication or at the conclusion of a grant. Additionally, there is evidence to suggest that papers with open data get cited more often than papers that do not. Finally, sharing materials and data make it easier for others to try to reproduce and build off your work. Therefore, there are both internal and external reasons that may motivate researcher to share some or all their research.

## Sharing

As was previously mentioned, everything on the OSF is private by default. You can make the entire project and/or subproject or components of the project public at any point by clicking the `public` button on each project/component page. Now that we are finished with our research study, we need to decide how much information we want to make public. One important thing to consider before making any information public is whether it contains sensitive data that cannot be made public for legal or ethical reasons. This might include materials that are copyrighted, files that contain identifyin information, or datasets that you can only make public after anonymizing the data per your IRB.  It is important to organize our project in a way that we make public only the parts we want, while keeping other parts private as necessary. 

As you may recall, I mentioned that our datafile has geotags, so we can’t make the raw_data file public. We’ve already created a anonymized (or ‘cleaned’) data file, which we can make public. But right now I have both files in the same ‘data’ component, so I can’t make one public and keep the other private.

> Activity (Question): What could I do so that I could share my clean data file but not reveal my raw data file with the geolocation variable in it?

One thing I could do would be to create another component under `Data` and move my raw data file to that component. Any file can be moved by simply clicking and dragging it to whichever part of the project you want to move it to. 

![moving files](Sharing_figs/moving_files.png)

> Activity: Now that I’ve shown you how to move files, discuss how much of your project you can/want to make public. Make those sections of your project public, and if you need to reorganize any parts of your project to accomplish that, please do that now.

![shared project]

## Increasing discoverability
 
I already mentioned that all projects, subprojects/components, and files on the OSF have GUIDs. So, if I want to send people to my project I can send them that GUID, or put it in my paper to help people navigate to my materials. However, we also want to make sure that our materials can be found by people who don’t already know it exists. We want to make sure it is discoverable.

Work posted on the OSF can be discovered in a couple of different ways. The first is through the search function within the OSF itself. We can search for anything we want, a project title, a general topic, a person’s name, and the system will bring up anything related to our search.  

![search example](Sharing_figs/osf_search.png)

You’ll see it will also make suggestions about ways to potentially refine your search.

![search results](Sharing_figs/search_results.png)

Public project on the OSF are also indexed by google, so they can be discovered outside the system. So, for example, if we go to google and search for ‘Daniel Lakens effect size’ his OSF project related to effect sizes comes up. 

![daniel google search](Sharing_figs/lakens_google.png)

Finally, information that has been registered on the OSF is discoverable through the SHARE notification service. If we go to ‘osf.io/share’, this will allow us to search through the contents of over 50 different providers. For SHARE specifically, only public registrations show up in the search results, which is another reason to register projects when you want to release a stable version of them.

![share image]

Part of making our work discoverable is making sure the right people find it through searches, so we want to make sure we understand how are work is being searched. Currently, the search on the OSF will search through contents in the wiki, project/component names, and tags. But it won’t search through individual files. So, if you think there are a few important key words that people might use to search for your project that don’t appear in the wiki or project name, where do you put this information? We can add `tags` to our project to make it more discoverable. You’ll notice this ‘tags’ area to the right of the screen. I can put whatever descriptors or keywords in here that I want to make it easier to discover my project for searching for related words/topics. 

![tags](Sharing_figs/tags.png)


> Activity: And add some tags that you think might be relevant to your project.


## Getting credit

So a big part of academia and the job market is being able to show that your work has impact. The classic way many fields often talk about this is citation counts. Now, we know this isn’t a great metric, particularly for newer papers, but since there is still a heavy emphasis places on it, we want to make sure that whatever we make open can be cited by other people who used it. We talked before about how you can get DOIs for your work through public registrations. Every project and component on the OSF also has an automatically generated citation which uses the GUID of the page, so as long as you have the correct contributor list on your project, everyone can get credit for it.

[citation widget]

But, since citation counts have limitations, what else could we use to measure the impact of our work? Well, two things we might be interested in are views and downloads. For all public projects we track how many people are visiting a page, and we track how often all files are downloaded. Now, your projects aren’t particularly old, so they probably won’t have very many views. But, if we search for ‘Daniel Lakens’ and click on this project, we can see how views and downloads can give vastly different information than citation counts. So, this is an OSF project associated with an article published in Frontiers, which is an open access journal. The paper and supplemental materials were also made publicly available on the OSF. Now, last time I check, this paper has had a bit under 100 citations, which isn’t bad, but it’s not a huge amount of impact. If we click on the files tab, that will allow us to see the download counts for all the files. You can see that the paper has been downloaded around 1500 times, which is a ton. 

[download counts]

Additionally, if we go to the statistics tab, we can see how many people are viewing the cite and where in the world they are viewing it from. So, these view and download numbers are telling a much more impressive story than the citations; a lot of people are interested this project because they find the materials useful.

[statistics page view]

* Recap of general things they’ve learned
