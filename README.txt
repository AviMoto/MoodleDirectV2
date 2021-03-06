These are the release notes for Moodle Direct V2 which contains a new Turnitin Assignment tool, a Plagiarism plugin and a block to allow access to the new Class Migration Tool.

For installation instructions and trouble shooting please see Installation Instructions.txt and Troubleshooting.txt or the relevant README files within each individual plugin element.

Moodle Direct v2 Release Notes
------------------------------------------------------------------------------------

Date:       2014-April-17
Release:    v2014012403

- Grademark link removed for student if a grade has not been set in Plagiarism Plugin.
- Feedback release date changed on forum with plagiarism plugin to be the same as start date.
- Fixes:
	> Incorrect links to GradeMark and Originality Report for students have been hidden.  

####################################################################################

Date:       2014-February-26
Release:    v2014012402

- Vietnamese Language pack added.
- Option to send draft submissions to Turnitin in Plagiarism Plugin reinstated.
- Diagnostic mode reinstated to disable logging by default.
- Troubleshooting documentation expanded.
- Fixes:
	> Student’s who’d never submitted could not view rubric, they’re now enrolled at this point.
	> Instructor now being enrolled in course when resetting to prevent errors in reading memberships.
	> OR Link was being shown in Plagiarism Plugin for non OR submissions.
	> Submissions now processed in Plagiarism Plugin if due date disabled.
	> Rubric List was not being populated in Plagiarism Plugin settings.
	> Updating of OR scores depending on OR submissions capability fixed in Plagiarism Plugin.
	> Cut off date / late submission issues solved in Plagiarism Plugin (Thanks to Chris Wharton).
	> Generic CSS issues fixed that were breaking some user’s themes.
	> Timezone was not being accounted for when editing part dates in inbox.
	> Editing title in course context is now updated in Turnitin.
	> Submit nothing link removed if submission has been made to Moodle but not yet processed by Turnitin
	> Incorrect grade scale calculation.
	> Previous Turnitin users were not being joined to account on Plagiarism plugin.

####################################################################################

Date:       2014-January-24
Release:    v2014012401

- File type limit removed.
- Ability to accept no file added so that marks / grades can be allocated to non file submissions 
- Dependencies added to plagiarism plugin and blocks
- Fixes:
	> Error occurring in course reset 

####################################################################################
Date: 		2013-December-18
Release:	v2013121801

- Supports Turnitin Originality Checking, GradeMark and PeerMark
- Allows access to the Rubric Manager and Quickmark Manager from within the Moodle environment
- Supports multi-part assignments allowing draft and revision submissions
- Allows instructors to submit work on behalf of students
- Supports Moodle Grade Scales and updates the Moodle gradebook with grades entered in GradeMark
- Supports Moodle Groups
- Allows multiple instructors to access a class and assignments in Turnitin’s web interface
- Supports Moodle’s built-in plagiarism detection thereby allowing access to Turnitin functionality from within Moodle assignments
- Incorporates a Class Migration feature allowing access to classes and assignments that are in Turnitin but not in the Moodle environment

