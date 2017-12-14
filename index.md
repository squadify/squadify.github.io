<div class="container">
  <h1 id="project-club-hub">Squadify</h1>
  <a href="http://squadify.meteorapp.com/">Link to Webpage</a>

<h2 id="overview">Overview</h2>

<p><em>The problem:</em> UH Manoa has over 200 <a href="http://www.manoa.hawaii.edu/studentlife/studentorg/rio.php">Registered Independent Organizations</a>, plus many more that do not have this “official” status but are nonetheless active organizations.  Unfortunately, there is no easy way for students to learn (a) what student clubs (both registered and unregistered) exist, what they do, and how to get further involved.</p>

<p><em>The solution:</em> The Squadify application will provide a centralized directory for UH Manoa student clubs. UH Manoa students can login to browse a well organized directory of all current student clubs, with brief descriptions, URLs to their websites (if any), club contact information, and a few select photos.</p>

<p>Squadify has three user roles where two have to login with their UH ID. Regular users browse the directory without logging in. Admins make sure site content is appropriate, allow club creation and deletion (with initial data population), and ability to edit all pages. Club Admins have the ability to edit the data associated with their club.</p>

<p>The site does not simply support browsing by a list of clubs in alphabetical order, but also allows filtering by interest area. For example, “athletic” clubs, “art” clubs, “music” clubs, etc.  A club can belong to multiple interest areas. There is alos a search bar and search page allowing browsing for names and </p>


<h2 id="mockup-page-ideas">Pages</h2>

<h3>Public Landing Page</h3>
<img src="/images/landing.png">
<p>
  When users access the page, this will be the first page the user will see. The top of the page contains a search bar along with the menu bar. The Search bar will be used to search for clubs or intrests that the user has. The menu bar contains four options which are very simply: <li><a class="item"> home ofcourse leading back to the front page</a> 
  <a class="item">search being a similar function to the search bar feature</a><a class="item">list will display all of the clubs that the unviersity has to offer in alphabetical order.</a> <a class="item">Finally, the login option which would allow you to see the club you manage if you do manage any or if you are an admin you will have admin privledges. </a></li> Underneath the menubar the page will randomly select clubs and displays them in the "Spotlight Organization" section. The club that will be displayed will have their club name at the top and have both a picture and a brief description on what the club is about.
</p>

<h3>Club Leader Page
  
<h3>Search Page</h3>
<img src="/images/search.png">

<h3>Search Page Searched</h3>
<img src="/images/search2.png">
  
<h3>Club Page</h3>
<img src="/images/club-page.png">
  
<h3>Club Edit Page</h3>
<img src="/images/club-edit.png">
  
<h3>Browse clubs by interest area(s)</h3>
<img src="/images/list.png">
  
<h3>Admin List Page</h3>


<h2>How to Install</h2>

<ol>
  <li>Retrieve copy from github</li>
  <li>Extract into folder of liking</li>
  <li>Open command line/prompt or whatever tool and go to squadify/app</li>
  <li>Run the following command: 'meteor npm install'</li>
  <li>If want to repopulate database adjust the initial-collection-data.json file</li>
  <li><ul>
    <li>If want to run locally, just run 'meteor npm run start'</li>
    <li>If on server, push onto server in server's desired manner</li>
  </ul></li>
  <li>Enjoy!</li>
</ol>


<h2>Community Feedback</h2>

<p><em>Disclaimer:</em>  Because we only can let them test the section where they can browse the clubs, their opinion is accurate in terms of that section only. The admin and club leader sections are unavailable for them to test. They also understood not all clubs were listed and only a selection were added.</p>

<p>
  Generally, the people who tested the program liked the UI design, its responsiveness. and the ease it provided compared to searching and browsing through the UH RIO list. Many people made use of the search bar at the top of the page and the search page. As for the filter page, initially they did not recognize that tags can be selected and after some text changes on the site, everyone afterwards recognized that it can be filtered. This was similar with the spotlight club on the landing page before adding a button below which goes to the club's profile page. One person pointed out that the search bar functionality is limited in terms of not catching acronyms, misspellings, and other minor text variations. This, of course, has not been implemented, but was a point of improvement to make in the future.
</p>


<h2 id="beyond-the-basics">Beyond the basics</h2>

<p>After implementing the basic functionality, here are ideas for more advanced features:</p>

<ul>
  <li>Notify admins when club data changes so they can review for appropriateness.</li>
  <li>Provide “expiration date” for club listings (either one semester or one academic year).  To retain a listing, the club admin or admin must login and click a “renew” button for the club to re-list it in the site.</li>
  <li>Allow students to apply to clubs.</li>
  <li>Allow clubs to upload pictures instead of hosting offsite</li>
  <li>Add calendar and club meeting time functionality</li>
  <li>Improve Search functionality by possibly using open source search api</li>
</ul>

<a href="https://github.com/squadify/squadify.github.io">Link</a> to project.

</div>
