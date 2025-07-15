**Bug Report Fields**

**ID:** Bug-01
**Title:** Form Submitted Without Filling the Requirement Field
**Test:** Submit form without required fields
**Github Link:** https://github.com/Akpos123/Diamond-Testers/issues/1
**Steps:**
**Start:** Do not fill the required field
Submit the form
Observe the output if it was submitted
**Expected:** Error messages should appear
**Actual:** Date field doesn't show validation error
**Risk Priority:** High

**ID:** Bug-02
**Title:** When Filter by "Eldoret" location display Nairobi
**Github Link:** https://github.com/Akpos123/Diamond-Testers/issues/2
**Test:** Filter by "Eldoret" location
**Steps:**
Start Select Eldoret in location
The output will display Nairobi
**Expected:** Show only Eldoret requests
**Actual:** Shows Nairobi requests instead
**Risk Priority:** High

**ID:** Bug-03
**Title:** Using Screen reader on Awareness page
**Test:** Use screen reader on Awareness page
**Github Link:** https://github.com/Akpos123/Diamond-Testers/issues/3
**Steps:**
**Observe:** if any missing alt text for images
**Expected:** Images should have descriptions
**Actual:** Date Missing alt-text on all images
**Risk Priority:** low

**ID:** Bug-04
**Title:** UI State Testing
**Test:** Use "Mark as Scheduled" button in Admin panels
**Github Link:** https://github.com/Akpos123/Diamond-Testers/issues/4
**Steps:**
**Observe:** if the UI refresh when updated
**Expected:** UI should update immediately
**Actual:** UI doesn't refresh (check localStorage)
**Risk Priority:** High

**ID:** Bug-05
**Title:** Boundary Testing issue
**Test:** Enter very long text in form fields
**Github link:** https://github.com/Akpos123/Diamond-Testers/issues/new
**Steps:**
**Start:** enter lengthy text on the form
Submit the form
Observe the output if it was submitted
**Expected:** Should handle gracefully
**Actual:**  cause layout issues
**Risk Priority:** High


**Automated Testing
The project includes React Testing Library for automated testing:
npm test
Test Data
The application comes with pre-filled mock data:
•	Sample Requests: REQ001-REQ005 with various statuses
•	Sample Feedback: FB001 for REQ004
•	Locations: Nairobi, Kisumu, Mombasa, Eldoret
•	Waste Types: General, Recyclable, Hazardous



📱**Responsive Design**
    The application is designed to be mobile-friendly with:
•	Responsive navigation
•	Mobile-optimised tables
•	Flexible grid layouts
•	Touch-friendly buttons



**Reflection Requirements**
•	Individual Reflection: I was exposed to testing of software and it importance in the SLDC. Although   
    There was time contraint which affected the testing process 
•	Team Reflection: Collaboration effectiveness was accomplish through meeting on Microsoft Team and 
    Whatsapp
•	Process Reflection: Testing methodology used was Manual and Automated testing
•	Future Improvement: More time should be giving to test of the software
**Reflection Questions**
•	Manual techniques testing was carried out by our team
•   Some of the Dependencies where more installed and this affected the Automated testing?, so there was 
    Communication barrier and time difference which a meetings.
•	Try to ensure more collaboration among the team
•	This Project has really increase my knowledge in software and QA
