Q: Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

A: The Weight Tracking Application was developed with the primary goal of helping users monitor and log their weight consistently over time. This mobile application serves as a personal health companion, making it easy for users to track changes, remain mindful of their fitness goals, and maintain healthy habits. Designed with user needs in mind, the app addresses the challenge of inconsistent weight logging by providing an accessible and intuitive platform for entry and review of weight data. Features such as daily or weekly weight entry, a scrollable history log, and SMS-based feedback (if enabled) work together to enhance motivation and health awareness.


Q: What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

A: To support these user needs, several key screens and features were integrated into the app. The user journey begins with a splash screen that welcomes the user and transitions smoothly into the SMS permission screen. This screen ensures that proper access is granted before enabling features that rely on SMS functionality. Following this, the main menu serves as a central hub for navigation. From there, users can access the weight entry screen, where they can input and save their current weight. A highlight of the app is the weight history screen, implemented using a RecyclerView, which displays all past entries in a clean and scrollable format. The user interface was designed to be minimalistic and intuitive, with clearly labeled buttons, easy-to-navigate menus, and responsive layouts that adapt to various screen sizes. These thoughtful design choices contributed to a user-centered experience that is both accessible and efficient.


Q: How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

A: From a development standpoint, the app was built with modularity and maintainability in mind. The process involved creating separate Java classes for core components such as MainActivity, DataActivity, and HistoryActivity. Key development strategies included using structured code, clear naming conventions, and modular logic separation to simplify testing and future updates. RecyclerView was chosen to display dynamic historical data efficiently, and runtime permission checks were added to handle SMS operations securely. Best practices in Java were followed throughout, ensuring a clean and scalable codebase. These techniques not only enhanced the current app but also serve as a reusable foundation for future mobile development projects.


Q: How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

A: To verify functionality, the app underwent thorough manual testing on both emulators and real Android devices. Each feature was tested for responsiveness, input validation, and edge cases such as empty entries, denied permissions, or unexpected input formats. Logging was used to debug and verify sensor data, where applicable. Testing played a vital role in identifying and resolving bugs, optimizing user flow, and ensuring that runtime permissions were handled gracefully. This process highlighted areas of improvement early, allowing for targeted refinements.


Q: Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

A: The design and development process was not without challenges. One significant hurdle involved ensuring that users granted SMS permissions before proceeding to the app’s core features. This required customizing the app flow to block navigation until permissions were validated, which was accomplished through conditional checks and activity gating. Another innovative aspect was converting the original static layout of the weight history into a dynamic RecyclerView, which dramatically improved performance and user experience for viewing multiple entries.


Q: In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

A: One of the most successful components of the app was the RecyclerView integration. This feature not only enhanced visual presentation but also demonstrated strong knowledge of Android UI patterns, including adapter design, ViewHolder optimization, and data-binding. The efficient handling of historical data in this manner greatly contributed to the app’s polished appearance and functionality.

In conclusion, the Weight Tracking Application reflects a comprehensive approach to mobile app development—from planning and UI/UX design to code implementation, testing, and problem-solving. The result is a well-rounded application that effectively meets its goal of helping users track their weight while showcasing solid development practices and attention to user-centered design.

