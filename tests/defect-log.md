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
