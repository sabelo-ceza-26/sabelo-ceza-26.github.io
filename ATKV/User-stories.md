# Sprint Backlog

### Sprint 1
**Day 1: Bilingual Content Management**  
**User Story:**  
As an administrator, I want to create content in English and Afrikaans so that members can read content in their chosen language.

**Tasks:**
- Create English and Afrikaans content fields
- Add a language switch for administrators
- Save content in both languages
- Validate that both languages are completed before publishing
- Display content in the member's selected language

**Day 2: Province-Based Content**  
**User Story:**  
As an administrator, I want to assign content to specific provinces so that members only see information relevant to their area.

**Tasks:**
- Add a province selection option
- Allow content to target one or more provinces
- Set content to national by default
- Save province selections with the content
- Display content to members in the selected provinces
- Add content tags and save them with the content

**Day 3: Resort Facilities and Entertainment**  
**User Story:**  
As an administrator, I want to manage resort facilities and entertainment so that members can easily see what each resort offers.

**Tasks:**
- Add and edit resort facilities
- Add entertainment activities and nearby attractions
- Add English and Afrikaans descriptions
- Upload pictures of entertainment activities
- Allow administrators to upload and replace PDF programmes
- Display facilities and entertainment on the resort page

**Day 4: Resort Accommodation Management**  
**User Story:**  
As an administrator, I want to manage accommodation types and their details so that members can compare options and choose suitable accommodation.

**Tasks:**
- Add and edit accommodation types
- Add accommodation names and descriptions in both languages
- Set the guest capacity and starting price
- Upload and arrange accommodation pictures
- Mark one accommodation type as featured
- Add amenities for each accommodation type
- Display accommodation information in the app

**Day 5: Start a Booking from the Bookings Screen**  
**User Story:**  
As a member, I want to start a new booking from my bookings screen so that I can easily search for accommodation.

**Tasks:**
- Add a `Book a New Stay` button
- Open the accommodation search screen when the button is selected
- Allow members to start a booking without existing bookings
- Ask members to select a resort
- Return members to their bookings screen when they leave the search

### Sprint 2
**Day 1: Sort Accommodation**  
**User Story:**  
As a member, I want to sort accommodation by price, guest capacity, and availability so that I can find options that suit my needs.

**Tasks:**
- Add sorting by price
- Add sorting by number of guests
- Add sorting by availability
- Keep all accommodation types visible when sorting
- Reset the default sorting when the resort or dates change


**Day 2: Display Accommodation Details**  
**User Story:**  
As a member, I want to see the main details of each accommodation type so that I can compare options without opening every listing.

**Tasks:**
- Display the accommodation name
- Show accommodation pictures
- Display the starting price
- Show the number of guests the accommodation can accommodate
- Allow members to browse pictures without leaving the search results

**Day 3: Show Accommodation Availability**  
**User Story:**  
As a member, I want to see which accommodation types are available for my selected dates so that I can choose a suitable place to stay.

**Tasks:**
- Display all accommodation types at the selected resort
- Check availability for the selected dates
- Show available accommodation types
- Mark accommodation as booked when it is unavailable for part of the stay
- Update availability when members change their dates

**Day 4: Display Current Offers**  
**User Story:**  
As a member, I want to see current accommodation offers while searching so that I can take advantage of available deals.

**Tasks:**
- Retrieve current resort offers
- Display offers in the accommodation search
- Keep offers consistent with ATKV's other booking channels
- Hide offers that have expired
- Allow members to sort, filter, and browse accommodation while offers are displayed

**Day 5: Start a Booking from a Resort Page**  
**User Story:**  
As a member, I want to start a booking from a resort page so that I can search the accommodation offered by that resort directly.

**Tasks:**
- Add a `Book Now` button to resort pages
- Open the accommodation search screen
- Select the resort automatically
- Display accommodation belonging to that resort
- Allow members to change the selected resort

### Sprint 3
**Day 1: Filter Accommodation by Resort and Dates**  
**User Story:**  
As a member, I want to filter accommodation by resort and travel dates so that I can find suitable options for my stay.

**Tasks:**
- Add a resort selection field
- Add check-in and check-out date fields
- Set the default dates to the coming week
- Display accommodation for the selected resort
- Keep the search filters visible while scrolling
- Prevent check-out dates from being on or before check-in dates


**Day 2: Confirm Accommodation and Member Details**  
**User Story:**  
As a member, I want my selected accommodation and personal details to appear automatically during booking so that I can confirm my information without entering it again.

**Tasks:**
- Display the selected resort and accommodation type
- Retrieve the member's name and identity number
- Retrieve the member's email address and phone number
- Link the booking to the member's account
- Match the booking to the correct member
- Prevent incomplete bookings from being created

**Day 3: Choose Booking Dates**  
**User Story:**  
As a member, I want to select my check-in and check-out dates so that I can book accommodation for my intended stay.

**Tasks:**
- Add check-in and check-out date selection
- Check accommodation availability for the chosen dates
- Prevent bookings for unavailable dates
- Prevent check-out dates from being on or before check-in dates
- Prevent members from selecting dates in the past
- Display clear messages when dates cannot be accepted

**Day 4: Restaurant Menus and Promotions**  
**User Story:**  
As a guest, I want to view restaurant menus and special-event promotions on a resort page so that I know what food and events are available.

**Tasks:**
- Add a restaurant section to the resort page
- Upload standard restaurant menus
- Upload special-occasion menus
- Add promotional images for restaurant events
- Support English and Afrikaans content
- Display the restaurant section when restaurant content is available

**Day 5: Manage Daily Game Content**  
**User Story:**  
As an administrator, I want to add game content for specific days so that daily games can continue without requiring a new software release.

**Tasks:**
- Add game content for a selected day
- Allow content to be added for multiple days
- Check whether content already exists for a day
- Ask for confirmation before replacing existing content
- Prevent changes to content for rounds that have already been played
- Display which days have content available

**Day 6: Open a Project Season**  
**User Story:**  
As an administrator, I want to open a season for a project so that members can enter the project during the specified period.

**Tasks:**
- Add an option to open a project season
- Set the season's start and end dates
- Allow members to enter while the season is open
- Prevent entries when no season is open
- Prevent two seasons from being open at the same time for one project
- Allow a new season to be opened after the previous season closes

**Day 7: Set Season Requirements**  
**User Story:**  
As an administrator, I want to set the requirements for a season so that members know what to submit and what fees and limits apply.

**Tasks:**
- Add the categories available for entry
- Set the entry fee
- Define what members must submit
- Set submission length and file size limits
- Set the season closing date
- Display submission limits before recording or uploading
- Prevent files that exceed the allowed size
- Send reminders before the closing date

**Day 8: Close a Project Season**  
**User Story:**  
As an administrator, I want to close a season so that entries can no longer be changed and are ready for judging.

**Tasks:**
- Add an option to close a season
- Prevent new entries after closure
- Prevent changes or new submissions to closed entries
- Keep unfinished entries visible to members
- Exclude unfinished entries from judging
- Prevent closed seasons from being reopened
  
**Day 9: Allocate Entries to Adjudicators**  
**User Story:**  
As an administrator, I want to assign entries to adjudicators so that each adjudicator can judge only the entries assigned to them.

**Tasks:**
- Display entries from closed seasons
- Assign entries to adjudicators
- Allow entry assignments to be changed when permitted
- Remove access for adjudicators who no longer have an assignment
- Display entries that have not yet been assigned
- Prevent reassignment after an outcome has been recorded

**Day 10: View Project Entries and Progress**  
**User Story:**  
As an administrator, I want to view project entries and judging progress so that I can monitor the progress of each season.

**Tasks:**
- Display the total number of entries
- Group entries by category
- Show which entries have been judged
- Show which entries still need judging
- Separate unfinished entries from completed entries
- Display scores and answers for completed auto-scored games
- Rank entrants by score where applicable

### Sprint 4
**Day 1: Manage Daily Game Offers**  
**User Story:**  
As an administrator, I want to update the information and pictures describing a daily game's offers so that members know what the game offers.

**Tasks:**
- Add wording describing the game
- Upload a picture for the game
- Save and display game information
- Allow administrators to update the information without a software release
- Hide the offer description when no content has been added

**Day 2: Set the Required Playing Streak**  
**User Story:**  
As an administrator, I want to set the number of consecutive days required for a playing streak so that ATKV can change the requirement without a software release.

**Tasks:**
- Add a setting for the required number of days
- Save the selected streak length
- Measure members' playing streaks against the setting
- Allow the setting to be changed
- Validate that the streak length is a positive whole number
- Keep existing play records unchanged when the setting changes

**Day 3: Remove Submitted Entry Material**  
**User Story:**  
As an administrator, I want to remove submitted entry files after judging so that ATKV does not keep recordings and other private material longer than necessary.

**Tasks:**
- Allow material to be removed for a whole season
- Allow material to be removed from an individual entry
- Confirm the removal before deleting files
- Prevent removal while entries still need judging
- Keep entry details, outcomes, and certificates
- Inform members when their submitted material has been removed
- Prevent deleted material from being restored

**Day 4: Cancel a Project Season and Refund Payments**  
**User Story:**  
As an administrator, I want to cancel a season and refund payments so that members receive their money back when ATKV cannot run the project.

**Tasks:**
- Add an option to cancel a season
- Confirm the cancellation before proceeding
- Request the reversal of invoices through iMIS
- Refund fees already paid by members
- Prevent cancelled entries from being judged
- Inform members that the season was cancelled
- Display refund information to affected members
- Prevent cancellation after an outcome has been recorded

**Day 5: Control Adjudicator Access**  
**User Story:**  
As ATKV, I want adjudicators to access only their assigned entries so that members' private submissions are protected.

**Tasks:**
- Restrict adjudicators to their assigned entries
- Prevent direct access to entries assigned to others
- Display a message when no entries have been assigned
- Restrict adjudicators to the adjudication section
- Remove access when an entry is reassigned

**Day 6: View and Open Submitted Entries**  
**User Story:**  
As an adjudicator, I want to open and view an assigned entry so that I can judge it and record the outcome.

**Tasks:**
- Display the entry's details and category
- Open submitted recordings in the portal
- Allow documents and artwork to be viewed
- Display scores and answers for auto-scored entries
- Display the entrant's name
- Show only the latest submitted material
- Display the member's confirmation of category eligibility

**Day 7: Download Recordings for Judging**  
**User Story:**  
As an adjudicator, I want to download an assigned recording so that I can judge it without depending on a continuous internet connection.

**Tasks:**
- Add an option to download assigned recordings
- Allow adjudicators to access downloaded recordings on their devices
- Ensure only assigned recordings can be downloaded
- Provide the latest submitted version of a recording
- Require adjudicators to record outcomes through the portal

**Day 8: Record an Entry's Outcome**  
**User Story:**  
As an adjudicator, I want to record the outcome of an entry so that the entrant can view their result and receive their certificate.

**Tasks:**
- Display the outcome options for the season
- Allow adjudicators to record an entry's result
- Validate that all required outcome fields are completed
- Prevent outcomes from being recorded for entries assigned to other adjudicators
- Prevent judging while a season is still open
- Allow corrections before judging is finalised
- Make results and certificates available after the outcome is saved

**Day 9: Record Outcomes for Team Entries**  
**User Story:**  
As an adjudicator, I want to record a separate outcome for each speaker in a team entry so that every speaker receives an individual result and certificate.

**Tasks:**
- Display all speakers listed in a team entry
- Record an outcome for each speaker
- Prevent a single outcome from being recorded for the whole team
- Identify speakers who still need to be judged
- Generate a separate result for each speaker
- Provide each speaker with a certificate in their own name
- Notify each speaker when their result and certificate are available
