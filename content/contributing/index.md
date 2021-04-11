---
title: "Contributing"
date: 2021-04-05T09:44:07-06:00
draft: false
---

Weazel News RP strives to capture the hard hitting stories that are impacting the citizens of Los Santos. If you're interested in contributing content to Weazel News RP then you're in the correct place. This page exists as a guideline for how to write, format, and submit your articles for consideration. Please note that not all articles received will be published and that it is up to the Weazel News RP editorial staff to make the final decision.

While Weazel News RP has satirical elements we **DO NOT** accept or condone any content that promotes hate speech, spreads hate, or harasses citizens of the city. Such content will be immediately rejected and reported to the proper authorities. Consider yourself warned.

## Who can be a Reporter?

Any citizen who is at least sixteen (16) years old may submit stories. Serious stories are restricted to individuals that are at least eighteen (18) years old.

## What to Report?

### Serious content

From time to time there are serious articles about disputes between characters of the city, be they part of the government or part of the citizenry. These articles should focus on the facts and limit creative writing to a minimum. These stories should help inform the citizens of Los Santos of important pieces of information and happenings in the city. Stories that reference actual citizens, active departments of the government, or active jobs fall in to this category and should be written with care. 

When writing stories about these topics, keep them simple and stay on the facts and quotes from citizens who participated in the event. Avoid supposition and creative liberty. These stories are touching on characters lives and may cause more harm if care is not taken. The only exception here is when the piece is obviously of a jokular nature.

### Jokular content

As we aim to provide a valid mix of entertainment and serious news we want to include topics on the gossip, entertainment, and unique culture of our city. Stories of this kind are lighthearted and meant to entertain the reader. They may include active and/or inactive citizens, locations, or entities within the city. Feel free to take more creative liberty in these stories. The goal is to have fun.


### Active vs Inactive?

An active citizen, place, or organization is one that is active in the city. Places such as Benny's shop, a citizen employed by Benny's, or the LSPD are exampels of active entities in the city. Inactive entities are ones that may/may not actually exist in the city. Organizations such as the Los Santos Fire Department (LSFD), which would exist in an IRL city but do not exist in ours. When you're reporting on an active entity be sure to get your facts straight and keep creative elements to a minimum. 

## How to Report?

First and foremost. He said, she said is the name of the game. Even if you're witness to an event take the time to question witnesses in the area. Speak to the citizen witnesses, police, the mayor, and persons of interest. Once you have the core set of facts which may include all of the the Five-Y's (who, what, where, when, and why). Then start a rough draft. Review it two or three times for syntax, grammar, and wording. While photos are not a requirement use them if they provide context or value to the story.

When speaking with witnesses and experts on a topic try to remain calm and collected. Keep questions about facts on point and simple. Use open ended questions to gather more details. Don't be afraid to ask the hard question; however once the interviewee deems the interview over leave them be. **DO NOT** harass citizens. 

When you feel your story is at a good place submit it for review. Then wait. It could take minutes, hours, or days for your story to be published. There's a lot going on in the city and the front page has limited space. Be prepared for feedback and additional questions. 

## Formatting your story

First, if you're going to use media (photos, videos) be sure to upload them to a public space for linking. YouTube and Imgur are great places. For imgur be sure to grab the link directly to the image. You can obtain this link by clicking on an image to zoom in and then right-clicking and selecting "Copy image location". The URL should look like _i.imgur.com/XQQB508.jpg_. Also note that image file size matters. Try to use a file image quality that provides details but doesn't create large images that require seconds to download. Large images slow down the browsing experience on Weazel News RP.

Second, you're going to have to learn the custom markup language that Weazel News RP uses for its content. Don't worry it's not to difficult, if you've ever used a word editor markdown is a unique syntax for marking sections of content with links, emphasis, and formatting. You may use any text editor to write your story as long as it's submitted as a [markdown document](https://www.markdownguide.org/getting-started/). There are many Markdown editors available and a simple one that we recommend is [Dillinger](https://dillinger.io/). Weazel News RP uses a unique template to help reporters out and is provided below in the section on the story template.

### Story template 

A story is broken down in to two parts. First is a section called **frontmatter**. This section is a meta-data section used to provide additional information to the Weazel News RP website. This section is defined by a block that starts with three dashes (-) and ends with three dashes. It must appear as the first section of the document. Following the frontmatter section is the story content. In the story content section is where your story will go and is where markdown will be used. Please note that all of the frontmatter fields shown in the template below are required and any missing fields may cause your story to be rejected.

#### frontmatter

<dl>
	<dt>draft<dt>
	<dd>A boolean value of "true" or "false". Stories MUST have this value and it MUST be "true". Failure to do so will result in your story being rejected.</dd>
	<dt>title<dt>
	<dd>A short summary of the story. It should be clear, conscise, and eye catching. Serious stories should avoid click-baity titles.</dd>
	<dt>author<dt>
	<dd>The name of the reporter submitting the story</dd>
	<dt>categories<dt>
	<dd>A list containing a single phrase that represents the category that the story will be filed under. Valid values are: "Law and Order", "Gossip", "Entertainment", and "Life and Styles"</dd>
	<dt>tags<dt>
	<dd>A short list of phrases that represent the overarching facts of the story.</dd>
	<dt>thumbnail<dt>
	<dd>A valid URL that points to the image that will be used as a thumbnail image for the story.</dd>
</dl> 

#### template

```markdown
---
draft: true
title: Shots Fired at LSPD
author: Tony Hills
date: 2021-04-05
categories:
  - Law and Order
tags:
  - LSPD
  - Olympic Freeway
thumbnail: https://i.imgur.com/XCWSfAu.jpg
---

&lt;img src="https://i.imgur.com/DjVnG9A.jpg" alt="The officer chasing another suspect of the shooting after Keebo [LNAME] was receiving medical care" title="The officer chasing another suspect of the shooting after Keebo [LNAME] was receiving medical care" class="photo photo-left"/&gt; Yesterday reports came in of shots being fired on or near the Olympic Freeway near the LSPD. Witnesses in the area stated that they were standing near the LSPD station building when up to six shots were heard coming from the direction of the freeway. Shortly thereafter officers were dispatched and came to investigate. During their investigation a vehicle pulled up to the front of the LSPD and a one Keebo [LNAME] approached the reporter on site and started to share a story about the LSPD. 

&lt;img src="https://i.imgur.com/XQQB508.jpg" alt="Mr. [LNAME] is seen unconcsious in the vehicle after the officer opened fire" title="Here Mr. [LNAME] is seen unconcsious in the vehicle after the officer opened fire" class="photo photo-right"/&gt; It was at this time that a cadet approached Mr. [LNAME] and asked him to stand down and surrender peacefully to the officers on site. Mr. [LNAME] then made way towards his vehicle and entered it despite repeated requests from the officer. Once in the vehicle the police officer drew his weapon and warned Mr. [LNAME] to step out of the vehicle. When Mr. [LNAME] refused to comply the officer fired a single shot into the vehicle severely wounding Mr. [LNAME]. 

&lt;img src="https://i.imgur.com/XCWSfAu.jpg" alt="Keebo [LNAME] about to receive medical attention from EMS" title="Keebo [LNAME] about to receive medical attention from EMS" class="photo photo-left"/&gt; EMS was then called onto the scene and began to administer aid to the victim. Sources at the Pill Box reported that the patient made a speedy recovery after surgery to remove the bullet. When the officer, a new cadet to the Los Santos police force, who fired the shot was questioned by Weazel News, they stated that it wasn't intentional and that he chose the incorrect tool from his gear due to the confusing placement based on SOP (standard operating procedure). Weazel News reached out to Chief D. Taylor for comment on this story who had this to say: "This was an unfortunate situation where the LSPD is evalauting training procedures. The LSPD will make sure that cadets receive the proper training on their equipment so that they may appropriately apply non-lethal force."
```

#### embeding images

Note that in the template above we avoid the use of the markdown format for embedding images. This is because we want to control where  the image lays in the story. We use a "zipper" layout where images alternate from being aligned to the left and the right side of the story well. To accomplish this simply follow the template example.

