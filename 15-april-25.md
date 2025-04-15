## **Day's Progress Log: Building the Sidebar of a WhatsApp UI Clone**

Today was all about laying the foundation for the left sidebar in my WhatsApp Web clone — a crucial part of the user interface that brings the whole layout to life. From structuring the chat list to adding scroll functionality and styling, here’s a breakdown of what got done:

**Sidebar Layout & Structure**

I started by creating the sidebar using HTML and CSS, setting up a clean container to hold individual chat entries. Each chat entry includes:
* A user avatar 
* The chat name and last message
* A timestamp on the far right
This setup mimics the look and feel of WhatsApp Web, keeping things tidy and user-friendly.

**Added a Search Bar**

A fully styled search bar now sits above the chat list, allowing users to “search or start new chat.” It includes a search icon and a soft background, fitting seamlessly into the WhatsApp aesthetic.

**Scrollbar Customization**
* Custom width
* Light gray thumb
* Rounded corners
* Hover color transition

**Tiny Tweaks That Matter**
* Added spacing between sidebar elements
* Styled avatars to be circular with thin black borders
* Inserted thin horizontal lines as separators (e.g. between Archive and Settings)
* Scoped scrollbar styles to apply only to `.sidebar-chats`, avoiding global changes