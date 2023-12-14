---
layout: default
title: "HCL Domino Discussion Template"
nav_order: 1
description: "HCL Domino Discussion Templatey"
has_children: false
---
<h1>HCL Domino Discussion Template</h1>

<details close markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Info

Property | Value
---|---
Filename | discussion12.ntf
Templatename | StdR12Discussion
Template version | 12.0.1
Signed by | Open Source Template/Domino Development
Optimized for | Notes Client & Web

## To follow a discussion
Select the All Documents view to see a chronological listing of main topics for discussion and their responses.  Select the By Author view to see what individual members of the discussion group have said.  Select the By Category view to browse the group's discussions categorized by main topics.

## To begin a discussion
From the All Documents view, By Author view or By Category view, create a Main Topic document to start a new topic for discussion.  Be sure to enter a category for the topic (Training, Documentation, Technical Tips, etc.).

## To respond to a main topic or a response document

### Menu
If you want to respond to a main topic, first highlight the main topic document and then select Create, Response.  Fill out the response form.  When you are done, press ESC and answer Yes to save your new document.
If you want to respond to the message in a response document, highlight the appropriate response document and then select Create, Response to Response.  Fill out the response form and then save your changes.

### Actions
Open the document you wish to respond to and click the Response action button at the top of the document.  

### Web Browser
Open the document you wish to respond to and click on the New Response hotspot at the top of the document.  Fill out the response form and then click on either the Submit hotspot on the top of the response form or the Submit button at the bottom of the response form.  Response to Response documents are not supported on the Web.

## To create an Author Profile
If you would like people to know something about you, click the "New Author Profile" button at the top of the view.  Fill out the form and add an (optional) picture of yourself.

## To flag a document as Private
You can use the "Mark Private" and "Mark Public" actions in the template to control whether anyone other than yourself can read a specific document.  For example, if you have not completed the writing of a particular document, you can click the "Mark Private" action and others will not be able to see the document.  When you complete the document, you can click the "Mark Public" action to make it available for others to read.
Note:  This action is not available to Anonymous web users.

## To set up an Interest Profile

### Notes
Use the Action menu item Edit Interest Profile to bring up your personal interest profile document. You can elect to be notified via a newsletter if certain conditions are met. These conditions can include the appearance of your name or phrases that you designate.

### Web Browser
Select the Edit Profile hotspot from any of the views in the database to bring up your personal interest profile document. You can elect to be notified via a newsletter if certain conditions are met. These conditions can include the appearance of your name or phrases that you designate.  This feature is not available to Anonymous web users.

## To add the current discussion topic to your Interest Profile

### Notes
Use the Action menu item Add Selected Topic To Interest Profile  to add the current discussion topic to the list of items you wish to track via newsletter.

### Web Users
Open the Main Topic which you would like to be added to your interest profile and select the Add Topic to Interest Profile hotspot.  This action is available whether you are reading or editing a main topic document.  This feature is not available to Anonymous web users.

## Anonymous responses
If you wish to respond anonymously to a discussion, highlight the main topic or a response and select Create, Other.  Then select either Anonymous Response or Anonymous Response to Response.  This feature is not available to web users.  If an anonymous web user is able to open the discussion database,  all documents created on the web will reflect that the user is anonymous.

## Agents

### Newsletters
A user can elect to be notified via e-mail when a new response has been added to certain topic(s) of discussion.  These topics are specified in the user's Interest Profile.  There are seven agents pertaining to newsletters.

* Edit Interest Profile:  The Interest Profile contains individual topics, phrases, keywords or categories of interest to the individual.  It can be tailored to contain as wide or as narrow a selection of topics as the individual is seeking information on.  This document is used by the Send Newsletters and Add Selected Topic to Interest Profile agents, described below.
* WebEditInterest Profile:  Web users equivalent of the Edit Interest Profile agent.
* Web InterestProfileSave:  Saves the Interest Profiles for web users.
* Add Selected Topic to Interest Profile:  Allows the user to add new topics of interest to their individual interest profiles.  After a new topic has been added, a Notes agent will process this request and notify the user via e-mail whenever new responses to this topic are added to the database.  If the error "This is not identified as a thread. Contact the database manager if you want all threads initialized." appears, the database manager must run the agent called Initialize ThreadIds (see description below).
* WebAddTopic:  Web users equivalent of Add Selected Topic to Interest Profile agent.
* Send  Newsletters:  Reviews the "Interest Profile" of each user who has a profile on a server-based Discussion database.  It matches criteria on the profile with any criteria it finds in the topics of the current database.  Each match generates a document link, which will become part of the newsletter; that newsletter is then mailed to the subscriber.  The agent can be run periodically.  Typically this would be on a daily basis.  
* WebRemoveThread:  Removes the selected thread from the web users Interest Profile.  
* Update Thread Maps:  Enables thread mapping for main topics and responses for web users.  Thread mapping displays a list of all topics and responses in the current thread on the document that the user is currently viewing.

## Archiving

### Notes users only
To set up Archiving for the Discussion, click the Archive button on the second tab of the File-Database-Properties infobox.  Fill out the information and click the OK button.  Set up the Archiving task to run on the server.  An archive database will be set up automatically.
Marking documents as "Expired"  
The Archive feature can act upon documents that have been marked as Expired.  

### Notes users
Select a document in the view and choose Mark/Unmark Expired from the Actions menu.

### Web browser users
Put the document into edit mode by clicking the Edit Document hotspot.  Then click the Mark/Unmark Expired hotspot at the top of the document.  

## Subscriptions
This template has a customized subscription form, containing the same fields as are found in the Interest Profile.  Select Create-Subscription to create a new subscription in your Headline database.  

### Converting Interest Profiles to Subscriptions
If you have an existing interest profile, you can convert its data into a subscription.  Select Actions-Convert Interest Profile to Subscription.  Note that this action will convert the data and then delete your existing interest profile.  It can only be used by Notes clients running R5.0 or higher.  Subscriptions are not available for the web at this time.

## Deleting Documents on the Web
You can now delete documents on the web while at the view level.  Click the document once to 'highlight' it and click the "Move to Trash" button.  A trash can icon will appear next to the document.  To remove the document permanently from the database, click the "Empty Trash" button.

## Attaching Files via the Web Browser
Only one file can be attached to a specific document at a time from a web browser.  However, this process can be repeated as many times as necessary to attach multiple files.
