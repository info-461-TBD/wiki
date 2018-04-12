# Design Specification

## Problem

Homelessness is a serious issue all across America. In a recent study, it was found that over half a million people are considered homeless in the United States. There are over 11,000 people that are homeless in Seattle alone, 47.1% of which are suffering without shelter. We know that there are several organizations in our city that are working towards ending homelessness once and for all, but the issue will not disappear overnight. No matter how noble their mission may be, they still need help.

Homeless shelters can range from all sorts of mission statements. Whether they want to offer a space for the homeless to come and eat volunteer-cooked food or they provide clothing to prepare for harsher conditions, these organizations could always use help with donations. Organizations often receive charitable gifts, but there is a disconnect between the way that society can reach out to these groups. The information about what these organizations are gathering is located all over the place so it can be difficult for a person to find where they can donate these goods. The lack of donated items does not stem from the scarcity of resources, but rather in the inefficient information on where to donate said goods.

## Solution

Our solution to combating homelessness in Seattle is to centralize the information that will help homeless shelters receive the proper donations they need. Through our website, organizations can post donation requests based on any specific events or drives that they are running. Some organizations are smaller and may not have the opportunity to advertise for help outside of their immediate circle of connections. But with this website, volunteers and donors can view these posts from any organization to see what items or resources that they can give to these causes. We simply want to connect those who need help with those who can offer it.

As a minimally viable product, our website will provide organizations the means of registering and verifying their information with us, and then posting a request to the main page for volunteers to view. On the main page, listings of all of the requests should be visible, along with the methods of filtering through these posts to narrow down what they can give. Each post should have more information to give about the request and organization itself. After connecting the volunteer and the shelter, the responsibility of communication is then given up to them. All we are doing is setting up this connection.

We believe that this can really help fight against homelessness. We believe in the organizations that are working hard to provide resources for those in need. We believe in the people that want to help see better living conditions for all. And we believe in the common people of society, who can really make a difference by laying down what they have. We know that our solution will help connect all of these people to make society a better place.


## Design Rationale

### Homepage - List of Posts
As the first page new users and potential volunteers see, it is important that we effectively communicate our mission, our brand, and what the site has to offer. To accomplish this, we chose to display a short banner at the top of the page that reaffirms our mission: “Connecting shelters in need with people who can help”. Below this will be a prominent button that says “Donate Goods”. Below this button is less prominent text, stating: “Are you a homeless shelter or organization helping homeless in Seattle? Register here.” There will be a link that takes the user to our organization registration page when clicked on. When  the “donate now” button is pressed, it will hide the banner section discussed above and use the screen area to display a list of active requests/posts from participating organizations.

By default, this list will be sorted by the date the request was posted to our site, newest first. Each list item will have an icon denoting which type of item requested by the poster. The donation types we chose are clothing, foods, household items, personal care, and leisure. We chose not to include an “other” type because we felt it would be confusing to users. Next to the will be the name of the organization followed by the neighborhood/city where the items can be dropped off. Also listed in text form is the ‘type’ of donation request and short blurb taken from the first ~140 characters of the the ‘more information’ section specified by the organization when submitting a request. When clicked on, the user will be taken for the detail page, showing the post they chose to view in more detail. There will be a means to sort posts by date and geographic location based on zip code (entered by user) and a means to filter out donation types.

![alt text](https://github.com/info-461-TBD/wiki/blob/master/Organization%20Posts%20Page.png)

### Individual Post Page
Much like how shoppers on Amazon and eBay can click on an item to get more information, potential donors and patrons can click on listings posted by different organizations and nonprofits. Donors need to be able to learn more about the needs of the organizations to figure out if they are able to meet them. If the donor believes that they have items that satisfy the organization’s requests, they will be able to reference the contact information provided to talk with the organization and learn more about the process. This page serves to get donors connected with organizations and establish rapport.

Full information about the items will be needed. This will include the item names, and the item description, which will both be posted by the organization. This will make sure that people have a clear idea of what is required, and hopefully eliminate any ambiguity donors may have about whether or not they are able to meet these needs. Contact information will also be required from the organization. The organization’s email and phone will be listed, as well as their locations’ address and hours of operation. There will also be a field to submit a message to the organization, in which people will have to put their own contact information too so that a rapport may be established. The contact will now be between the user and the organization.

![alt text](https://github.com/info-461-TBD/wiki/blob/master/Individual%20Item%20Listing.png)

### Organization Post Form
This is the view where organizations are able to fill out the information needed for a new request and post it. They would need to fill out the form, with some fields being required. Fields that are on this form are items such as the location, date needed by, items needed and a description behind the request. We want organizations to be as detailed as possible so that volunteers can quickly understand what the request is for and to see whether or not they can help. Once filled out correctly, the post will then be sent to the home page for volunteers to view. 

The organization post page will have forms that need to be filled out, including contact number and email, date needed by, items needed, location, and a description for why these items are needed. The only field that is not required is the description, but it is strongly recommended that they do fill that out because we want each post to be as specific as possible. There is a submit button at the bottom of the page that will verify if all the required fields are filled out and if done correctly, should submit the post.

![alt text](https://github.com/info-461-TBD/wiki/blob/master/Organization%20Request%20Form.png)

### Organization Registration Page
The purpose behind the organization registration page is to verify whether an organization is legitimate and reliable. There needs to be accountability on the organization’s side if they are going to be asking for donations from volunteers. Therefore, any homeless shelter that will be using our website will need to provide their information, purpose and main point of contact. Organizations that cannot prove their authenticity will not be able to post on the website.

They will need to fill out simple information about the organization itself. This information will show up on future request posts. They will need to enter the organization’s name, public phone number, public email, main address and website, if applicable. If a donator wants to find out more about an organization, they should have all the information they need in order to directly contact them or to research their website. The terms of agreement is to make sure that the organization fully knows what they are signing up with. It helps keep them responsible for any request that they post. They will verify that they read the terms of agreement and then enter in a contact’s name, email and signature. 

They will fill out the information in normal input forms, where our system will email their contact to verify the organization. Once all the information is filled in, the user can submit the organization registration form. Our website will make sure there is no information missing. If everything checks out, the organization should be able to post a request at any time.

![alt text](https://github.com/info-461-TBD/wiki/blob/master/Organization%20Registration%20Page.jpg)
