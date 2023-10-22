# CS330
1. How do I approach designing software?
- What new design skills has your work on the project helped you to craft?
  - I've chosen simple objects that meet the criteria for the requirements, yet also leave room for greater complexity. I've also used both geogebra and chatGPT to test (x, y, z) vertex coordinates and indices arrays. When drawing triangles between base to base, automating that process was extrememly helpful.
- What design process did you follow for your project work?
  - For each object I determined its' component shapes. I reused previous models, and created new ones if necesary. I decided on the total number of vertices, and sketched out its' coordinates by hand. I then tested it out and adjusted as needed. It was important to keep my objects both to scale and positioned appropriately: in relation to other objects. Doing so allowed me so focus completely on each new object, without having to massively refractor previous code. Good textures that loaded successfully were also used for testing.
  - I also followed learnopengl.com extensively to create my project. I stuck to one library, GLAD, and tried to understand each piece of code I was reusing.
- How could tactics from your design approach be applied in future work?
  - Meeting the requirements with easy to reach goals is super helpful in making consistent progress and staying motivated. Physically sketching and writing pseudocode is also helpful to visualize what your code is doing and know what is going on. Doing so helps you recognize errors when they take place, and allows for an easier time diagnosing problems. It's also important to write descriptive and organized code that can grow, without having to come back and modify it every time something new is added. This is also why it's important to use utility functions and modularize your code, so most of the logical changes can take place all at once elsewhere, without disrupting the main body.
  
2. How do I approach developing programs?
- What new development strategies did you use while working on your 3D scene?
  - I've learned to minimize extra data with glDrawElements. I've also practiced using extensive comments to label vertex data, indices, and objects.
- How did iteration factor into your development?
  - I created a barebones model for each object, making sure it rendered properly, and then finetuned with transformations. I labeled each variable accordingly, and I seperated the new code from the old with updated comments. I also dealocated resources, and reused code when possible. With each milestone, I tried to refractor and clean up my code— through condensing and implementing classes and utility functions.
- How has your approach to developing code evolved throughout the milestones, which led you to the project’s completion?
  - It's important to stay organized; Although, I may not use as many comments that are in the samples and tutorials. I've really seen the benefit in adding descriptive comments to code, not only to distinguish between sections, but to aid in manipulating data. Modularizing code within external Classes is also very helpful to aid in high level manipulation and organization. The low-level logic can be encapsulated within objects. As the sheer amount of lines of code increased, it became more and more important to appropriately name my variables and create placeholders for data. As an example, having variables for radius, angle, and alpha sped up development speed when needing to make quick changes to 20+ lines of code.
  - 
3. How can computer science help me in reaching my goals?
- How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?
  - Writing in C++ is useful practice for any future courses using C++ and Java. Ironically, taking this class solidified my current educational pathway. I am happy with my current major bs.csc, and I have no interest in game development or graphics at this time. However, parts of this course gave me a similar feeling to rendering components with React.js, which I hate using, so hopefully this experience will leave me with a bit more patience in the future.
- How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway?
  - Using Windows and C++ are useful experience to have with backend web development. OpenGL ES is also something I may explore sometime in the future.
