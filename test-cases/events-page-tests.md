TEST CASE 1
Title: User can open Events page from menu
Preconditions: 
  - User is on the main page
  - Navigation menu is visible
Test Steps
Step 	Action 	                        Data 	                  Expected Result
1     Click on link button "Events"   -                       Events page is opened
                                                              URL corresponds to Events page
                                                              Page title "Events" is displayed

TEST CASE 2
Title: User can create own event.
Preconditions: 
  - User is logged in
  - User is on Events page
Test Steps
Step 	Action 	                        Data 	                  Expected Result
1     Click on button "Create event"  -                       Event creation form is opened
2     Enter name for the event        "Football match"        Text is entered successfully
3     Choose Initiative type          "Environmental"         Option is selected
4     Select Event type               "Open", "All"           User can select options from dropdown
5     Fill Events Description         "We invite you to join  User can enter description text
                                      us to watch a football
                                      match!"
6    Choose a date                    "March 27, 2026"        Selected date is displayed correctly
7    Choose  Start/End time           13:00 - 15:00           Selected time range is displayed                                                            
8    Choose Location Checkbox         Place                   Offline location field becomes enabled
9    Enter event offline place        Lviv, Park Art of Rest  Entered location is displayed correctly
10   Click "Publish" button           -                       Event is created successfully
                                                              Event appears in events list
                                                              All entered data is saved correctly

TEST CASE 3
Title: User can add a comment for event
Preconditions: 
  - User is logged in
  - User is on Events page
  - Event list is available
Test Steps
Step 	Action 	                       Data 	                 Expected Result
1     Click on button "More"         -                       Event details page is opened
      for any event                                          Selected event information is displayed
2     Enter comment                  "Text for testing"      Text is entered successfully
3     Click "Comment" button         -                       Comment is created successfully
                                                             Comment appears in comments list
                                                             Comment text matches entered data

TEST CASE 4
Title:  Error message is shown when a user left empty event title
Preconditions: 
  - User is logged in
  - User is on Create event page
Test Steps
Step 	Action 	                       Data 	                  Expected Result
1     Click on text field            -                        Field is active for text entry
2     Leave field empty and          -                        Error message "Enter a title up 
      click outside the field                                 to and including 70 characters" 
                                                              is displayed under the field
                                                              Event title field is highlighted
                                                              as invalid  
