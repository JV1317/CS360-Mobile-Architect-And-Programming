# CS360-Mobile-Architect-And-Programming

### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
<p>The primary purpose of this application will be to provide a simple and intuitive way for users to track and manage inventory. This application will need to consist of a user interface front end where users can view and manage their inventory and a database back end that will hold inventory information.</p>

### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
<p>The application design consists of an interface where a user can log into the application. Different user accounts may have different permissions. The login screen will prompt users for their username and password. These credentials will be checked against the users table in the database. Once logged in, users will be presented with a home screen containing a grid with each item in their inventory. The grid is be consistently spaced and in line in accordance with the Android Design and Quality Guidelines. The widget will have a text name and a numerical count of the number of that item currently in stock. Users will also be able to add, remove, and update items in thier inventory using the buttons on the home screen. The design is layed out in a very intuitive way making this design successful in my mind.</p>

### How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
<p>I found the use of wirefreames and story boards to be very useful when designing and developing the app. I started with the UI then developed the code to implement the functionality.</p>

### How did you test to ensure your code was functional? Why is this process important and what did it reveal?
<p>For this project functional testing primarily consisted of debugging and walking through the code to ensure aspects were functioning properly. This is crucial to any project to not only ensure that your program is functioning properly but also that any exceptions are handled correctly and will not crash your application. .</p>

### Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
<p>I would say the primary challanges and where I needed to innovate the most was during the implementation of the DB and the different components concerned with adding, removing, and updating items and users to the database.</p>

### In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
<p>I would say the database as a whole allowed me demonstrate these traits. I was able to imploy what was essently a singleton instance of the db that could be called and utilized from the multiple activities of the application and I was able to add, remove and update items fromt the tables within that DB. </p>
