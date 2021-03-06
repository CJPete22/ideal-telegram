# 1. Title
Attendex

# 2. Authors
Derek Wautlet (dwautlet@wisc.edu), Carly Peterson (cjpeterson7@wisc.edu), Theo Kachelski (tkachel@wisc.edu)

# 3. Description
 The program keeps attendance and strike records for 100+ employees. It has the ability to mark down a variety of reasons for abscences and tardiness such as various emergencies or midterms. It has the ability to mark a variety of attendance infractions such as no call no show and calling in sick. It will keep the record of the attendance for the last 100 days, and update last 100 based on current date. It will record attendance inquiries and communication details for each employee with the ability to view all inquiries at once.
 
 The program has a simple GUI with a search bar, the ability to add and remove individuals, and a clickable list of each employee with the most important emplyee information listed next to each employee. All categories are sortable in ascending and descending order and clicking on each individual will bring up more information about them. There is also a second tab that keeps track of communication inquires in a priority queue and presents the one without a response for the longest time as highest priority.

# 4. Stakeholders
Primary Stakeholder
* Administrators who are responsible for scheduling and absences of employees.

Secondary Stakeholders
* Supervisors who are responsible for hiring employees and managing. Need strike count in order to determine whether or not an interaction with an employee is required.

# 5. Output
Format
Organized folders, calendar views, and textual output on screen.  
* Employee Id, Employee Name, Number of points per employee, Number of strikes per employee

Example
See Figure3.png and Figure4.png

# 6. Input
Required Data
* Employee name and attendance that corresponds to a point value.

Example: Employee Name - John Smith, Attendance - N (no show)


# 7. Diagrams
### Home page (required)
Re-consider Nielsen's 10 Heuristics of User Interface Design (Links to an external site.)Links to an external site. and address as many as possible within your pages.
Sketch a picture or frame of the main home page for an application that solves this problem. 
Draw a rectangle that is computer monitor shaped (landscape)
Draw and label input/output components like:
* buttons,
* checkboxes,
* text input fields (single-line or multi-line),
* banners,
* etc.  (anything that you think would be good)  

Do not worry about if you know how to program it.  Just worry about what you think is the best interface for the program.

Take a picture, upload, and insert that picture into your Design Document

### Additional Pages
Draw other pages or screen formats that you think will be useful for your program keeping in mind Nielsen's Heuristics.   If entire program design is handled by one page, you may omit this section.

Draw a rectangle for each page
Label or name that "page" so you can refer to it in other places.
Draw and label the components of that page

# 8. Control Flow Graph
Draw an overview (graph) of your program's pages.

Draw a vertex for the home page
Draw a vertex for the output produced
Draw a vertex for the input required
Draw a vertext for other pages
Name and label each vertex
Add edges between the vertices showing the transitions from input to home and home to output and from other pages to one another.
Label each edge with the action (transition) that produces moves data or control from one view to another (not all pages must be reachable from all other pages, but they all should be reachable from the home page in one way or another).

# 9. Class Summary
List and describe the classes that you expect to design and implement.

Classes:

Employee
* Holds the id, names, strike count and point count of the employee.

# 10. Implementation Phases
Assuming that it is not likely a small team can complete entire program at one time, prioritize which operations must be available in each of three phases of the program development.

Phase 1 - GUI operational and ability to store inputted data about each employee.

Phase 2 - Calculating strikes, search functionality, and storing inquiry data and other personal files

Phase 3 - Calendar view and sorting functionality

Future phase - Connect to an email server and be able to send emails (and email templates) from the program.
