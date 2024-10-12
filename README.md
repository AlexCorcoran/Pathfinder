### Pathfinder Web Application for Web Development Class Spring 2024
Pathfinder was built using Flask, SQLite, Bootstrap, HTML, CSS 


## Team
- Team Lead: Alex Corcoran
- Team: Conor Weiss

## Project Description
Pathfinder is a Portland-specific directory of tech and tech-related businesses. It is a full-stack application that allows users to register, login, and search/favorite businesses of interest. There are several ways to filter businesses, such as by industry, zip code, keyword, and business type. Each business has a profile page and map location. Pathfinder is intended to be a resource to learn about companies that are either smaller/less well known, not partnered with or highlighted by the Roux, or have tech positions open but are not explicitly tech companies, like banks or healthcare systems.

## Current Prototype Screenshots
Home Page<br>
![](images/Current/HomePage.png)
<br>
<br>
<br>

Home Page with Industry Hover<br>
![](images/Current/HP_Industry.png)
<br>
<br>
<br>

Logged In Showing A-Z Filter with Keyword Hover<br>
![](images/Current/LogIn_AZ_Keyword.png)
<br>
<br>
<br>

Map View of A-Z Companies<br>
![](images/Current/AZ_MapView.png)
<br>
<br>
<br>

Company Full Profile View<br>
![](images/Current/Company_Full_Profile_View.png)
<br>
<br>
<br>

Favorites Page<br>
![](images/Current/YourFavorites.png)
<br>
<br>
<br>

## User Stories

|User Story 1 |Casual Research|
|---------------------|-----------------------------------------------------------------|
|Primary actor | Unregistered or not-logged-in site visitor|
|Actor’s Goal| To learn about companies with tech-related positions in Portland, ME that are not featured at the Roux or may not have an active online presence.|
|Preconditions| The site has been populated with data about local companies|
|Scenario|1. Site visitor navigates to home page <br>2. Site visitor selects “View Directory” <br> 3. Site visitor clicks “Filter” <br>4. Site visitor enters keywords, or selects from a set of presented options<br>*Keywords include type of company, industry, and whether the company has an established relationship with the Roux<br>5. Site visitor enters a zip code to further filter companies by location.<br>6. Site visitor is presented with a narrowed list of companies that match their filter options.<br> 7. Site visitor can select one of these companies to view its profile.<br>8. Profile page shows information about the company, including its location on a google map.|

<br>
<br>

|User Story 2 |Registration|
|---------------------|-----------------------------------------------------------------|
|Primary actor | Unregistered site visitor|
|Actor’s Goal| To create a profile to enhance use of the site.|
|Preconditions| The site has a functional registration system and a backend that stores users’ profiles|
|Scenario|1. Site visitor navigates to landing page <br>2. Site visitor selects “Join” <br> 3. Site visitor enters a name, email, and password <br>4. Site visitor is shown an “Account Created” message and routed to a log-in page.|


<br>
<br>

|User Story 3 |Persistent Search|
|---------------------|-----------------------------------------------------------------|
|Primary actor | Registered User|
|Actor’s Goal| To identify companies that match their skills or location and retain for future site visits without needing to filter or search again.|
|Preconditions| The User has an account, and the site’s company data is populated.|
|Scenario|1. Site visitor navigates to landing page <br>2. Site visitor selects “Login<br> 3. Site visitor enters their email and password and is logged in. <br>4. Logged-in user rerouted to home page, now showing personalized welcome message.<br> 5.Logged-in user is clicks “Profile” to view their profile page.<br> 6. As in use case 1, “Casual Research,” steps 2-7, the user is able to navigate to the directory, filter the companies, and select a single company.<br> 7. Logged-in user clicks “Favorite” (or Heart symbol), which updates to show that the company has been recorded as a favorite.<br> 8. Logged-in user returns to their profile pag<br> 9. Logged-in user selects “My Favorites”<br> 10. Logged-in user is shown a list of companies that they have favorited.|

<br>
<br>

|User Story 4 |Request Inclusion|
|---------------------|-----------------------------------------------------------------|
|Primary actor | Local Company Representative|
|Actor’s Goal| To get their company listed on Pathfinder|
|Preconditions| None|
|Scenario|1. Local company representative navigates to landing page <br>2. Local company representative selects “List Your Company"|


<br>
<br>


|User Story 5 |Contact Admins|
|---------------------|-----------------------------------------------------------------|
|Primary actor | Any Site Visitor|
|Actor’s Goal| To report an inaccuracy in data or an issue using the site|
|Preconditions| None|
|Scenario|1. Site visitor navigates to landing page <br>2. Site visitor selects “Contact"<br> 3. Site visitor is directed to a Web Form that requests name, email, subject, and message<br> 4. Web Form Info is stored on the backend for retrieval by site administrators, who act on the issue. |

<br>
<br>

|User Story 6 |Read Messages|
|---------------------|-----------------------------------------------------------------|
|Primary actor | Admin users|
|Actor’s Goal| To read messages sent in via web forms
|Preconditions| Webform message data is stored successfully|
|Scenario|1. Admin logs in and admin options are made available on home page <br>2. Admin selects “Read User Contacts”<br> 3. Admin selects “Company Requests”<br> 4. Admin reviews web form submissions to the company web form.<br> 5. Admin returns to “Read User Contacts”<br> 6. Admin selects “User Messages”<br> 7. Admin reviews web form submissions to the user contact web form. |

<br>
<br>

## Initial Database Design
ER Diagram:<br>
![](images/ER_Diagram.png)


Relational Model:<br>
![](images/Relational_Model.png)

## Initial UI Design
Referenced Builtin, LinkedIn, and The Roux Institute’s websites for design and layout inspiration and information design. The logo was created in Illustrator.

Color Accessibility:<br>
(via Adobe Color)<br>
![](images/WebDev_ColorAccessibility.png)
<br>
<br>


Home Page:<br>
(designed on Figma)<br>
![](images/pathfind_homepage.png)
<br>
<br>

User 1 - Industry Hover Example:<br>
(designed on Figma)<br>
![](images/pathfind_industry_hover.png)
<br>
<br>


User 2 - Join Example:<br>
(designed on Figma)<br>
![](images/pathfind_register_2.png)
<br>
<br>

User 3 - Company Profile Page Example:<br>
(designed on Figma)<br>
![](images/pathfind_profile_page.png)
<br>
<br>

User 5 - Contact Form Example:<br>
(designed on Figma)<br>
![](images/pathfind_contact_form.png)
<br>
<br>
<br>
