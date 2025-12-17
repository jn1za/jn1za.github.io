---
layout: project
type: project
image: img/team-uhp/TeamUHp-Graphic.png
title: "TeamUHp! Connecting Students to collaborate on large scale projects."
date: 2025
published: true
labels:
  - Web Application
  - Front-End Development
  - Back-end Development
  - Group Project
summary: "Worked with a group of student developers in ICS314 to create the TeamUHp web application designed for UH students to connect across areas of study by enabling them to upload project postings and recruit collaborators."
--- 



<img src="../img/team-uhp/TeamUHp-Banner.png" style="display: block; margin: 0 auto; width: 100%;">
<!-- <img src="../img/team-uhp/TeamUHp-Banner-XWide.png"> -->

<em>
  The TeamUHp! web application is deployed through Vercel cloud hosting at
  <a href="https://team-uhp.vercel.app">team-uhp.vercel.app</a>.
  <br>
  Other information such as application, user, and developer’s documentation
  is available at TeamUHp’s home page at
  <a href="https://team-uhp.github.io">team-uhp.github.io</a>.
</em>

## All From An Anecdote
<hr>
It all started from a simple conversation checking in on the first week of the Fall semester. My friend who is studying mechanical engineering happens to tell me about a class he’s taking which is focused on one big project: build a robot that can climb 2 winds of stairs in Holmes Hall, retrieve an egg, and bring it back down within 6 minutes. Unfortunately, he tells me that all of the members of his team are strictly mechanical engineering students, and nobody really knows how to code or has dabbled in robotics to the extent of programming! Their solution? It was agreed that one member of the team be left alone to his own task: learn how to program and make the robot remote-controlled.

For a mechanical engineering student, such a project can be quite a great hands-on experience, but feel very out of scope. In a professional enterprise environment, such tasks would be split to those specific in the area of study, which may include a contractor onboarded for programming, a contractor to provide the ordered hardware, or a consultant to guide the team to progress through what is unfamiliar on their own. If only there was a way for students to gain experience with such collaboration during their student life…

## TeamUHp! Connecting Students to collaborate on large scale projects.
<hr>
Many college students want to build real-world experience and strengthen their resumes through hands-on projects. However, the scope and complexity of meaningful and large-scale projects may exceed their current technical skills or confidence. Such a gap makes it difficult for students to initiate or complete projects that truly showcase their abilities. 

TeamUHP! is a platform for students to connect across areas of study by enabling them to upload project postings and recruit collaborators. Whether it’s a class assignment or a passion project, students can find teammates with complementary skills and allow each contributor to play a meaningful role that aligns with their field of study. This medium of collaboration helps students to gain practical experience, build teamwork skills, and add completed projects to their resumes.

## My Role in TeamUHp!
<hr>
In the nature of such a project, I was able to experience both the front-end and back-end fields of implementation. A lot of the changes I made dabbled in many different pages, whether it be a global pass at all UI design for the entire application, or the backend-added features that displayed themselves in sections of certain pages. 

Among the first major changes I added, I turned many of the basic skeleton mockups from Milestone 1 into a more fleshed out and standardized web page. To do so, I created a shared "sketches" file to save relevant color hexes, mockup drafts, and other saved aesthetic choices to keep as a resource for the team: See ["TeamUHp Layout/Design Sketches"](https://docs.google.com/presentation/d/1oOsBEic-QJjPBjZlVcT_8FZ7k5hBBjZrkPhcwUM7L6E/edit?slide=id.g3aa0f5c5864_0_0#slide=id.g3aa0f5c5864_0_0). The growth of our project's aesthetic became more fleshed out as the UI developed further:

<div style="display: flex; justify-content: center; gap: 30px; margin-top: 12px;">
  <img src="../img/team-uhp/project-list-before.png"
       style="height: 375px; max-width: 48%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
  <img src="../img/team-uhp/project-list-after.png"
       style="height: 375px; max-width: 48%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
</div>

<em style="display: block; text-align: center; font-size: 0.85rem; margin-top: 8px;">
  Project list page after Milestone 1, and the same page after Milestone 2.
</em>

<div style="display: flex; justify-content: center; gap: 30px; margin-top: 12px;">
  <img src="../img/team-uhp/project-page-before.png"
       style="height: 375px; max-width: 48%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
  <img src="../img/team-uhp/project-page-after.png"
       style="height: 375px; max-width: 48%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
</div>

<em style="display: block; text-align: center; font-size: 0.85rem; margin-top: 8px;">
  Individual project pages after Milestone 1, and the same page after Milestone 2.
</em>

<div style="display: flex; justify-content: center; gap: 30px; margin-top: 12px;">
  <img src="../img/team-uhp/recruit-before.png"
       style="height: 375px; max-width: 48%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
  <img src="../img/team-uhp/recruit-after.png"
       style="height: 375px; max-width: 48%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
</div>

<em style="display: block; text-align: center; font-size: 0.85rem; margin-top: 8px;">
  Recruit for Opening page after Milestone 1, and the same page after Milestone 2.
</em>

<br>

Generally, I had the objective of standardizing all pages in the application to have uniformity. This includes the similar schemes as Add Project, Edit Project, Edit Opening, Edit Profile, Profile Pages, Applications pages, and more!:

<div style="
  display: grid;
  grid-template-columns: 1fr 1fr;
  width: 100%;
  row-gap: 12px;
  text-align: center;
">
  <div>
    <img src="../img/team-uhp/opening-page.png"
         style="height: 350px; width: 100%; object-fit: contain; display: block; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Individual Opening Pages</em>
  </div>
  <div>
    <img src="../img/team-uhp/application-admin.png"
         style="height: 350px; width: 100%; object-fit: contain; display: block; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Application Page</em>
  </div>
  <div>
    <img src="../img/team-uhp/forgot-password.png"
         style="height: 350px; width: 100%; object-fit: contain; display: block; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Forgot Username/Password Pages</em>
  </div>
  <div>
    <img src="../img/team-uhp/forgot-password-2.png"
         style="height: 350px; width: 100%; object-fit: contain; display: block; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Forgot Username/Password (on Submit)</em>
  </div>
  <div>
    <img src="../img/team-uhp/landing-page.png"
         style="height: 350px; width: 100%; object-fit: contain; display: block; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Team UHp official landing page.</em>
  </div>
  <div>
    <img src="../img/team-uhp/helpful-tools-page.png"
         style="height: 350px; width: 100%; object-fit: contain; display: block; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Helpful Tools page and external links.</em>
  </div>
</div>

<em style="display: block; text-align: center; font-size: 0.85rem; margin-top: 12px;">
  (See more images at TeamUHp's home page, or interact directly at our website). 
</em>
<br>

After fleshing out many of the UI standardizaiton and initial implementations, I added the bookmark/save projects feature, add/remove contacts feature, and included more diverse skills to select which were also grouped by fields of study. 

I first implemented the add/remove contacts button to be visible when viewing all other profile pages (besides the current session user). This referenced the `contacts[]` and `contactsOf[]` attributes in the schema, then displayed them on the actual contacts page which was created by another team member.

<div style="display: flex; justify-content: center; gap: 12px; margin-top: 12px;">
  <img src="../img/team-uhp/add-contact.png"
       style="height: 325px; max-width: 48%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
  <img src="../img/team-uhp/remove-contact.png"
       style="height: 325px; max-width: 48%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
</div>

<em style="display: block; text-align: center; font-size: 0.85rem;">
  Add/Remove contact toggle when viewing other profiles.
</em>

<br>

I also added new attributes in relation to the database schema to track saved projects: `savedProjects[]` and `savedBy[]`. This was included after I implemented the "Save Project" button in each of the project pages. Subsequently, I included a feature to filter projects by toggle in the projects list page.

<div style="
  display: grid;
  grid-template-columns: 1fr 1fr;
  width: 100%;
  row-gap: 12px;
  text-align: center;
  margin-bottom: 12px;
">
  <div>
    <img src="../img/team-uhp/saved-project.png"
         style="height: 350px; width: 100%; object-fit: contain; display: block; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Team UHp official landing page.</em>
  </div>
  <div>
    <img src="../img/team-uhp/filter-saved.png"
         style="height: 350px; width: 100%; object-fit: contain; display: block; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Saved Projects appear through the toggle filter.</em>
  </div>
</div>

Another major change was in adding a more robust set of skills to the `Skills` enum. This involved researching inclusive [CIP codes](https://nces.ed.gov/ipeds/cipcode/browse.aspx?y=56) to add skills of major fields that would adhere to the user audience. Relevant skills were grouped during research in a personal excel sheet: 

<div style="display: flex; justify-content: center; gap: 12px; margin-top: 12px;">
  <img src="../img/team-uhp/sheet-skills.png"
       style="margin-bottom: 12px; height: 375px; max-width: 100%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
</div>

After including all skills into the general skills enum, I grouped them by created a helper file typescript file in the `utilities` library so that certain fields of study could be selected in the many pages. Part of this issue was also implementing the areas in which this would be used, and so I implemented the feature on all of the pages where selection is included, such as the Add/Edit Opening and Edit Profile forms. Skills can be added nondiscriminately of their respective fields of study, so I also included a summary of all selections to view/remove them.

<div style="text-align: center; margin-bottom: 16px;">
  <img src="../img/team-uhp/skills-select-section.png" style="display: block; margin: 0 auto; width: 70%; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
  <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Field dropdown available to select skills. </em>
</div>

Additionally, I updated the initial search function by skill select fron all skills to a selection narrowed by field, to which multiple tags could be applied in the filter, and results would display for all of any of the tags applied:

<div style="text-align: center; margin-bottom: 16px;">
  <img src="../img/team-uhp/search-filter.png" style="display: block; margin: 0 auto; width: 70%; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
  <em style="font-size: 0.85rem; display: block; margin-top: 4px;">Results populating by skill tags added to the filter.</em>
</div>

Nearing the finalization of the project, since I had been involved with a part of all of the pages, I had also taken up the minor fixes issues to make a final pass on all small UI fixes or bugs with data handling. Such were listed and completed as follows (viewable in Milestone 3 project management panel in our Github):

<div style="
  display: grid;
  grid-template-columns: 1fr 1fr;
  width: 100%;
  row-gap: 12px;
  column-gap: 12px;
  text-align: center;
  margin-bottom: 12px;
  align-items: start;
">
  <div style="display: flex; flex-direction: column;">
    <img src="../img/team-uhp/m3-minor-fixes-1.png"
         style="height: 350px; width: 100%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; margin-top: 4px;">
    </em>
  </div>
  <div style="display: flex; flex-direction: column;">
    <img src="../img/team-uhp/m3-minor-fixes-2.png"
         style="height: 350px; width: 100%; object-fit: contain; border: 1px solid #ccc; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.12); box-sizing: border-box;">
    <em style="font-size: 0.85rem; margin-top: 4px;">
    </em>
  </div>
</div>

Part of my tasks included actively updating the overview, user guide, team display cards, development history, community feedback, and continuous integration sections in the github.io Home Page as the project progressed. I served as the primary editor for these documentations.

## Team Collaboration & Project Management
<hr>
This is truly the first time I’ve worked on such a large project, and saw how necessary it was to create such a thing by the contribution of many members. I got to experience what makes project management so essential to achieving the goal, and how explicitly listing of tasks, planning for deliverables, distributing efforts, and effectively documenting it all is so pivotal to succeeding. In no way would I have truly grasped the scale of it all had I not gone through it hands-on in this project, made and corrected the minute mistakes, and reflected on the experience for the better.

## Building A Project & Building Myself
<hr>
Working on this project, in a way, fulfilled the mission of the platform itself. I’ve always wanted to make my own app and it be something both beautiful and functional, and I’ve felt that same thing where I can imagine ideas that can really benefit a community, but the scope of such a project seems a little daunting. Having worked on this project, it is like manifesting those plans into something real and usable, and is opening the doors to all the more dreams becoming tangible. 

I wonder if it is because of this that I start to imagine daily life as a set of persistent problems and infinitely, though yet to be, discoverable solutions. There are so many ways I can put these skills to use now beyond a personal project. If I put it into perspective, the modern world is still creating solutions to basic human needs and civilization’s necessities, like biomedical disease detections, long-term sustainability in industrial systems, clean energy and energy-efficiency, and so much more. The fortunate thing about being a student in technology is the idea that there is always an opportunity to be a part of all of that as the world progresses to utilize tech more. When I am able to better my skills and build my experiences, the closer I am to seeing where exactly *my place* is in all of that. 
