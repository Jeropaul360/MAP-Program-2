Start Program Execution

Launch the main function using runApp() to start the Flutter application.

Initialize Main Widget

Create a MaterialApp widget as the root of the app.

Set home to a custom widget called MyDetails.

Disable the debug banner using debugShowCheckedModeBanner: false.

Define Custom Stateless Widget

Create a stateless widget class named MyDetails.

Build UI in build() Method

Use a Scaffold widget to structure the screen.

Set the app bar title to "Personal Details" with a blue accent color.

Set the background color of the screen to light grey.

Create Centered Container

Add a Center widget to center the content on the screen.

Inside Center, use a Container to hold the personal details.

Apply padding and set width to 300.

Set background color to white.

Apply rounded corners and shadow using BoxDecoration.

Display Personal Information

Use a Column inside the container to stack text widgets vertically.

Set alignment to start (left).

Use Text widgets to display:

Name: Paul Jero

Age: 22

Email: jeropaul360@gmail.com

City: Coimbatore

Use SizedBox widgets to add spacing between each item.

Render the UI

Flutter renders the UI as per the build method logic.

End Program Execution

User interface remains visible and interactive until the app is closed.
