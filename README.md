# Virtual-Art-Gallery

# About The Application
Virtual Art Gallery is an Augmented Reality Android mobile application, developed using Unity 3D, Vuforia SDK and Android Studio. 
If you want to buy a painting or a sculpture or center piece for your tea table from an artist across the world, 
you can do so online through several e-commerce websites that sells art works. How do you decide, if the painting goes well with the interiors of your house? how big would the art work be on your wall ? 

Virtual Art Gallery is the one stop solution, which lets you virtually view the painting on your wall with its actual size and 
see how that center piece looks on your corner table or see how well the garden sculpture goes with the landscape of your front yard!

You can download and install the application from Google play store , it comes with a trigger image which should be color printed 
full size on an A4 sheet, paste the trigger image on wall where you want to try painting, or place it on table where you want to see 
the sculpture. open the app, browse through all the paintings and sculptures, click on them to see the Augmented reality camera launching, 
now point the camera on the trigger image to see the art work virtually appear on it.

# APPLICATION REQUIREMENTS

Front End
Unity 3D
	        -> Version     -    5.3.4
	        -> Project      -    Unity Project

Vuforia SDK
	        -> Version     -    5.5

Android studio                  
	        -> Version     -    2.1

Smartphone running on Android OS
	        -> Version     -    4.4 and above
          
# The UI has 3 main scenes. 

-> Scene 1 is the welcome screen. The entire screen is a button. On clicking on the screen, the next scene loads.
-> Scene 2 is the gallery page. It displays a gallery of images. To implement this screen, a horizontal scrolling view was implemented. In this scrollview, a background with floodlight and wooden walls is sent. Paintings are added to the gallery in a horizontal fashion one after the other. Paintings are big thumbnails which are visible completely as a thumbnail itself. The user need not click on it to be completely visible. Each of these paintings are available in rectangular image views. each of these image views are buttons that lead the user to the next scene on clicking.The gallery also has sculptures. On clicking on it, the application goes to scene three.
-> Scene 3 is where the Augmented reality is actually applied. Scene 3 looks like a camera. The user points the camera at the wall that he/she wants to augment the painting to. The user must have taped the identifier image to the wall. Once that is done, the application identifies the image and replaces it with the painting selected by the user. The scene has virtual buttons through which the user can go back or augment the next or previous image in the gallery to the wall. 
