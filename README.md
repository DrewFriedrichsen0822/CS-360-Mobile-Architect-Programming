# CS-360-Mobile-Architect-Programming


1. Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The app was designed to help users manage and track inventory items efficiently from a mobile device. Its core goal was to provide a simple, reliable way for users to log in, view their inventory, and receive alerts when stock levels were low. The app addressed user needs such as quick access to item details, the ability to update inventory on the go, and automated SMS notifications to prevent stockouts.


2. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app required several key screens: a login screen, an inventory grid displaying all items, an item‑detail or edit screen, and an SMS permission screen. Each screen was designed with clarity and simplicity in mind—large buttons, readable text, consistent spacing, and intuitive navigation. The UI kept users in mind by minimizing steps to complete tasks and presenting information in a clean, organized layout. These designs were successful because they reduced cognitive load and made the app easy to use even for someone unfamiliar with Android apps.


3. How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached coding incrementally, building one feature at a time and testing it before moving on. I relied heavily on separating UI layout work from Java logic, which made debugging and updates much easier. I also used consistent naming conventions and modular methods to keep the code organized. These strategies can be applied to any future project because they support maintainability, reduce errors, and make it easier to scale or modify features later.


4. How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the app by running it frequently in the Android emulator and verifying each feature as it was implemented. This included checking login behavior, verifying that inventory items displayed correctly, and ensuring SMS permissions triggered as expected. Testing is essential because it catches issues early and confirms that the app behaves as intended. Through testing, I discovered small layout issues, logic errors, and permission‑handling quirks that I was able to fix before finalizing the app.


5. Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One area where I had to innovate was handling the SMS permission workflow. Android’s permission system can be tricky, so I had to design a clear user flow that explained why the permission was needed and gracefully handled cases where the user denied it. I also had to troubleshoot project structure and Gradle configuration issues early on, which required adapting my approach and learning how Android Studio organizes resources and dependencies.


6. In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I was particularly successful in designing and implementing the inventory grid screen. It required combining UI layout skills, data handling, and event‑driven logic to create a functional and user‑friendly interface. This component showcased my ability to connect Java code to UI elements, manage data effectively, and follow Android design guidelines to produce a polished final result.
