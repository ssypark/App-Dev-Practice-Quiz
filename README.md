for studying App Development mid term! Good Luck
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>App Development Quiz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1 {
            text-align: center;
        }
        .answer {
            display: none;
            margin-top: 10px;
            margin-bottom: 20px;
        }
        .show-answer {
            cursor: pointer;
            color: blue;
            text-decoration: underline;
        }
    </style>
</head>
<body>

<h1>App Development Quiz</h1>

<!-- Question 1 -->
<p>1. What triggered the initial boom in mobile app development?</p>
<ul>
    <li>A) The release of the iPhone in 2007</li>
    <li>B) Opening hardware APIs to third-party developers</li>
    <li>C) The invention of smartphones in the late 1990s</li>
    <li>D) The launch of 4G networks</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(1)">Show Answer</p>
<p id="answer1" class="answer">Answer: B) Opening hardware APIs to third-party developers<br>**Explanation**: Opening hardware APIs allowed third-party developers to create apps for mobile devices. This expanded the mobile ecosystem and increased the variety and number of apps available to consumers, leading to the rise of app stores like Apple’s App Store and Google Play.</p>

<!-- Question 2 -->
<p>2. Which of the following is a key advantage of Native Apps?</p>
<ul>
    <li>A) Built using web technologies like HTML, CSS, and JavaScript</li>
    <li>B) Requires only one codebase for all platforms</li>
    <li>C) Provides the best performance and full access to device features</li>
    <li>D) Can be distributed without going through an app store</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(2)">Show Answer</p>
<p id="answer2" class="answer">Answer: C) Provides the best performance and full access to device features<br>**Explanation**: Native apps are built for specific platforms (iOS or Android) using platform-specific programming languages, offering better performance, optimization, and full access to device features like GPS, camera, and notifications.</p>

<!-- Question 3 -->
<p>3. Which app development method is typically most suitable for a small business looking to launch an MVP (Minimum Viable Product)?</p>
<ul>
    <li>A) In-House Development</li>
    <li>B) Out-of-House Development</li>
    <li>C) White-Page/Templated Apps</li>
    <li>D) Hybrid Apps</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(3)">Show Answer</p>
<p id="answer3" class="answer">Answer: B) Out-of-House Development<br>**Explanation**: Small businesses often outsource development to external agencies or freelancers to create a Minimum Viable Product (MVP) due to budget constraints or lack of in-house development expertise. This allows them to launch quickly and iterate based on feedback.</p>

<!-- Question 4 -->
<p>4. What is a Progressive Web App (PWA)?</p>
<ul>
    <li>A) A web app with limited functionality and offline support</li>
    <li>B) A native app that uses push notifications</li>
    <li>C) A web page that functions like an app, with features like push notifications and offline access</li>
    <li>D) A hybrid app designed to work only on Android</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(4)">Show Answer</p>
<p id="answer4" class="answer">Answer: C) A web page that functions like an app, with features like push notifications and offline access<br>**Explanation**: PWAs are web apps that offer a native-like experience with features like offline access and push notifications. They run in browsers but can be "installed" on the home screen without needing to go through an app store.</p>

<!-- Question 5 -->
<p>5. Which of the following monetization models allows users to download the app for free but offers paid features within the app?</p>
<ul>
    <li>A) Pay per Download</li>
    <li>B) Freemium</li>
    <li>C) Subscription</li>
    <li>D) Data Monetization</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(5)">Show Answer</p>
<p id="answer5" class="answer">Answer: B) Freemium<br>**Explanation**: The Freemium model offers the app for free but charges for premium features or services. This model is common in gaming and productivity apps, where basic functionality is free, but users can pay for additional tools or features.</p>

<!-- Question 6 -->
<p>6. Which app is an example of a subscription-based revenue model?</p>
<ul>
    <li>A) Clash of Clans</li>
    <li>B) TikTok</li>
    <li>C) Spotify</li>
    <li>D) Angry Birds</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(6)">Show Answer</p>
<p id="answer6" class="answer">Answer: C) Spotify<br>**Explanation**: Spotify uses a subscription-based model where users pay a recurring fee to access premium features such as ad-free music, offline playback, and higher-quality streaming.</p>

<!-- Question 7 -->
<p>7. What is the role of a project manager in app development?</p>
<ul>
    <li>A) Writing code for the app</li>
    <li>B) Designing user interfaces</li>
    <li>C) Coordinating between team members and tracking development progress</li>
    <li>D) Conducting user interviews</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(7)">Show Answer</p>
<p id="answer7" class="answer">Answer: C) Coordinating between team members and tracking development progress<br>**Explanation**: The project manager is responsible for overseeing the app development process, coordinating between developers, designers, and other stakeholders to ensure timelines are met and the project stays on track.</p>

<!-- Question 8 -->
<p>8. What is a key benefit of using a tool like Figma in app development?</p>
<ul>
    <li>A) It allows for real-time collaboration among team members</li>
    <li>B) It provides direct access to app analytics</li>
    <li>C) It is used for coding the app</li>
    <li>D) It automates testing and bug fixing</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(8)">Show Answer</p>
<p id="answer8" class="answer">Answer: A) It allows for real-time collaboration among team members<br>**Explanation**: Figma is a collaborative design tool that allows team members to work together in real-time on app prototypes and UI/UX designs, streamlining the design process.</p>

<!-- Question 9 -->
<p>9. Which onboarding type highlights key features through a guided tour?</p>
<ul>
    <li>A) Self-Select</li>
    <li>B) Quickstart</li>
    <li>C) Top User Benefits</li>
    <li>D) Gradual Introduction</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(9)">Show Answer</p>
<p id="answer9" class="answer">Answer: C) Top User Benefits<br>**Explanation**: The Top User Benefits onboarding process introduces users to key features through a guided tour or carousel. This helps users understand the main benefits of the app right away, improving retention.</p>

<!-- Question 10 -->
<p>10. What does App Store Optimization (ASO) help with?</p>
<ul>
    <li>A) Improving an app’s performance</li>
    <li>B) Reducing app development costs</li>
    <li>C) Increasing an app’s visibility in app store search results</li>
    <li>D) Gathering feedback from users</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(10)">Show Answer</p>
<p id="answer10" class="answer">Answer: C) Increasing an app’s visibility in app store search results<br>**Explanation**: ASO (App Store Optimization) helps improve an app’s visibility by optimizing its metadata (title, keywords, description) and encouraging positive reviews, which leads to higher rankings in app store search results.</p>

<!-- Question 11 -->
<p>11. What is the main advantage of using Hybrid Apps for development?</p>
<ul>
    <li>A) Full access to all native device features</li>
    <li>B) Lower development costs and faster time to market</li>
    <li>C) Superior performance compared to Native Apps</li>
    <li>D) Higher engagement rates than Progressive Web Apps</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(11)">Show Answer</p>
<p id="answer11" class="answer">Answer: B) Lower development costs and faster time to market<br>**Explanation**: Hybrid apps are built using web technologies (HTML, CSS, JavaScript) and can be deployed across multiple platforms, making them faster and cheaper to develop compared to native apps.</p>

<!-- Question 12 -->
<p>12. Which stage in the user journey focuses on ensuring the user quickly understands how to use the app?</p>
<ul>
    <li>A) Awareness</li>
    <li>B) Acquisition</li>
    <li>C) Onboarding</li>
    <li>D) Retention</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(12)">Show Answer</p>
<p id="answer12" class="answer">Answer: C) Onboarding<br>**Explanation**: The onboarding stage helps users quickly understand how to use the app, ensuring a smooth introduction to key features and improving the likelihood of continued engagement.</p>

<!-- Question 13 -->
<p>13. Which company is known for using data monetization as part of its app revenue strategy?</p>
<ul>
    <li>A) Apple</li>
    <li>B) Google</li>
    <li>C) Uber</li>
    <li>D) Facebook</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(13)">Show Answer</p>
<p id="answer13" class="answer">Answer: B) Google<br>**Explanation**: Google monetizes user data by using it for targeted advertising across its products, including Google Search, YouTube, and Gmail, among others.</p>

<!-- Question 14 -->
<p>14. What is Geoff Moore’s Value Positioning Template used for?</p>
<ul>
    <li>A) Optimizing app store descriptions</li>
    <li>B) Highlighting how an app solves a user’s problem</li>
    <li>C) Defining technical specifications for developers</li>
    <li>D) Measuring user retention rates</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(14)">Show Answer</p>
<p id="answer14" class="answer">Answer: B) Highlighting how an app solves a user’s problem<br>**Explanation**: Geoff Moore’s Value Positioning Template helps define how a product or service solves a particular user problem and highlights the main benefits of the app for its target audience.</p>

<!-- Question 15 -->
<p>15. Which of the following is a common risk associated with the Freemium monetization model?</p>
<ul>
    <li>A) High upfront costs for users</li>
    <li>B) Ongoing costs for the developer with no guaranteed revenue</li>
    <li>C) Limited access to native device features</li>
    <li>D) Difficulty in optimizing for app stores</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(15)">Show Answer</p>
<p id="answer15" class="answer">Answer: B) Ongoing costs for the developer with no guaranteed revenue<br>**Explanation**: In the freemium model, developers often incur ongoing costs (e.g., server hosting, support) without guaranteed revenue from users. Monetization relies on users opting into premium features or in-app purchases.</p>

<!-- Question 16 -->
<p>16. What is the primary advantage of using a Minimum Viable Product (MVP) approach?</p>
<ul>
    <li>A) Reduces development time and cost</li>
    <li>B) Guarantees the product’s success</li>
    <li>C) Avoids the need for user feedback</li>
    <li>D) Provides a complete product with all features</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(16)">Show Answer</p>
<p id="answer16" class="answer">Answer: A) Reduces development time and cost<br>**Explanation**: The MVP approach focuses on building a basic version of the product with only essential features, allowing companies to release quickly, gather feedback, and iterate. This helps reduce time and development costs while minimizing risks.</p>

<!-- Question 17 -->
<p>17. Which of the following best describes a native app?</p>
<ul>
    <li>A) A web-based app that runs in the browser</li>
    <li>B) An app that can run on both iOS and Android without modifications</li>
    <li>C) An app built specifically for one platform, using platform-specific languages</li>
    <li>D) An app that runs entirely in the cloud</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(17)">Show Answer</p>
<p id="answer17" class="answer">Answer: C) An app built specifically for one platform, using platform-specific languages<br>**Explanation**: Native apps are developed specifically for one platform (e.g., iOS or Android) using platform-specific languages like Swift for iOS and Kotlin for Android. They offer the best performance and full access to platform features.</p>

<!-- Question 18 -->
<p>18. What is one key benefit of Progressive Web Apps (PWAs)?</p>
<ul>
    <li>A) They provide direct access to hardware features like GPS and camera</li>
    <li>B) They can be used offline and function like native apps without requiring app store installation</li>
    <li>C) They have superior performance compared to native apps</li>
    <li>D) They are limited to iOS devices</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(18)">Show Answer</p>
<p id="answer18" class="answer">Answer: B) They can be used offline and function like native apps without requiring app store installation<br>**Explanation**: Progressive Web Apps (PWAs) behave like native apps but are accessed via a browser. They can be installed on the user’s home screen and often work offline, providing many features without needing to go through an app store.</p>

<!-- Question 19 -->
<p>19. What does a "freemium" app offer?</p>
<ul>
    <li>A) Full access to all features for free</li>
    <li>B) Paid features available only for users who download premium versions</li>
    <li>C) Basic features for free, with additional features available for purchase</li>
    <li>D) In-app purchases without offering any free features</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(19)">Show Answer</p>
<p id="answer19" class="answer">Answer: C) Basic features for free, with additional features available for purchase<br>**Explanation**: In a freemium model, users can access basic features for free, but need to pay for additional features, services, or content within the app. This model is common in apps like Dropbox or Spotify.</p>

<!-- Question 20 -->
<p>20. What is the primary goal of "App Store Optimization" (ASO)?</p>
<ul>
    <li>A) Optimizing the app’s performance</li>
    <li>B) Enhancing user experience</li>
    <li>C) Increasing the app’s visibility in app store search results</li>
    <li>D) Reducing development time</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(20)">Show Answer</p>
<p id="answer20" class="answer">Answer: C) Increasing the app’s visibility in app store search results<br>**Explanation**: ASO focuses on improving an app's metadata (keywords, title, description) and reviews to make the app more discoverable in the app store search results, thereby attracting more downloads.</p>

<!-- Question 21 -->
<p>21. Which of the following is NOT an app monetization model?</p>
<ul>
    <li>A) Pay per Download</li>
    <li>B) In-App Advertising</li>
    <li>C) Freemium</li>
    <li>D) Continuous Integration</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(21)">Show Answer</p>
<p id="answer21" class="answer">Answer: D) Continuous Integration<br>**Explanation**: Continuous Integration refers to a development practice where code changes are frequently integrated into a shared repository, not a monetization model. The other options (Pay per Download, In-App Advertising, Freemium) are valid monetization methods.</p>

<!-- Question 22 -->
<p>22. What is the primary purpose of wireframes in app development?</p>
<ul>
    <li>A) To create high-fidelity visual designs</li>
    <li>B) To visualize the layout and structure of the app’s user interface</li>
    <li>C) To code the app’s functionality</li>
    <li>D) To write app store descriptions</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(22)">Show Answer</p>
<p id="answer22" class="answer">Answer: B) To visualize the layout and structure of the app’s user interface<br>**Explanation**: Wireframes are low-fidelity sketches used to plan the layout, structure, and navigation of an app’s interface. They are a crucial step in the UX/UI design process, helping teams visualize the flow and user interactions.</p>

<!-- Question 23 -->
<p>23. What is one major disadvantage of hybrid apps compared to native apps?</p>
<ul>
    <li>A) They can only run on Android devices</li>
    <li>B) They have reduced performance compared to native apps</li>
    <li>C) They require separate codebases for each platform</li>
    <li>D) They cannot access web-based features</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(23)">Show Answer</p>
<p id="answer23" class="answer">Answer: B) They have reduced performance compared to native apps<br>**Explanation**: Hybrid apps are built using web technologies and wrapped in a native container. While this allows them to be deployed across multiple platforms, they often have slower performance and less access to native device features compared to native apps.</p>

<!-- Question 24 -->
<p>24. Which of the following tools is best for creating interactive app prototypes?</p>
<ul>
    <li>A) Adobe Photoshop</li>
    <li>B) Figma</li>
    <li>C) GitHub</li>
    <li>D) Visual Studio</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(24)">Show Answer</p>
<p id="answer24" class="answer">Answer: B) Figma<br>**Explanation**: Figma is a popular collaborative design tool used for creating interactive prototypes and wireframes for app development. It allows real-time collaboration and design iteration, making it ideal for UI/UX design work.</p>

<!-- Question 25 -->
<p>25. In the user journey, which stage focuses on converting a potential user into a customer?</p>
<ul>
    <li>A) Awareness</li>
    <li>B) Acquisition</li>
    <li>C) Retention</li>
    <li>D) Advocacy</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(25)">Show Answer</p>
<p id="answer25" class="answer">Answer: B) Acquisition<br>**Explanation**: The acquisition stage focuses on converting potential users into actual users or customers. This is typically achieved through marketing, ads, and app store optimization.</p>

<!-- Question 26 -->
<p>26. Which app monetization model is best suited for a gaming app with in-game purchases?</p>
<ul>
    <li>A) Pay per Download</li>
    <li>B) Freemium</li>
    <li>C) Subscription</li>
    <li>D) Data Monetization</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(26)">Show Answer</p>
<p id="answer26" class="answer">Answer: B) Freemium<br>**Explanation**: For many mobile games, the Freemium model works well. Users can download and play the game for free but must make in-app purchases for virtual goods, extra lives, or power-ups, providing continuous revenue.</p>

<!-- Question 27 -->
<p>27. Which type of app is built using HTML, CSS, and JavaScript, and is then wrapped in a native container?</p>
<ul>
    <li>A) Native App</li>
    <li>B) Hybrid App</li>
    <li>C) Progressive Web App (PWA)</li>
    <li>D) Desktop App</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(27)">Show Answer</p>
<p id="answer27" class="answer">Answer: B) Hybrid App<br>**Explanation**: Hybrid apps are built using web technologies like HTML, CSS, and JavaScript, but are packaged inside a native container that allows them to run on mobile devices. They are a cross-platform solution but offer lower performance than native apps.</p>

<!-- Question 28 -->
<p>28. What is the key benefit of using an MVP approach in app development?</p>
<ul>
    <li>A) Allows for testing the market with minimal resources</li>
    <li>B) Includes all features of the final product</li>
    <li>C) Avoids the need for user feedback</li>
    <li>D) Requires no iteration after the initial release</ul>
<p class="show-answer" onclick="toggleAnswer(28)">Show Answer</p>
<p id="answer28" class="answer">Answer: A) Allows for testing the market with minimal resources<br>**Explanation**: An MVP (Minimum Viable Product) allows companies to release a basic version of the product, test the market, and gather feedback with minimal resources. This helps reduce risk and focuses on iterating based on real-world user feedback.</p>

<!-- Question 29 -->
<p>29. What is the purpose of prototyping in app development?</p>
<ul>
    <li>A) To create the final version of the app</li>
    <li>B) To test and refine the user experience and functionality before full development</li>
    <li>C) To write the codebase</li>
    <li>D) To generate revenue</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(29)">Show Answer</p>
<p id="answer29" class="answer">Answer: B) To test and refine the user experience and functionality before full development<br>**Explanation**: Prototyping allows teams to test the app's design, flow, and functionality in a low-fidelity version. This helps identify potential issues and improvements before committing to full development, saving time and resources.</p>

<!-- Question 30 -->
<p>30. Which app development platform provides the best access to device features like GPS, camera, and push notifications?</p>
<ul>
    <li>A) Native Apps</li>
    <li>B) Hybrid Apps</li>
    <li>C) Progressive Web Apps</li>
    <li>D) Cross-Platform Apps</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(30)">Show Answer</p>
<p id="answer30" class="answer">Answer: A) Native Apps<br>**Explanation**: Native apps are built specifically for a single platform (iOS or Android), allowing them to fully access all device features, such as GPS, camera, push notifications, and more. This makes them ideal for performance-intensive applications.</p>


<h1> Bonus Questions! <h1>
    <p>1. What is the purpose of prototyping in app development?</p>
<ul>
    <li>A) To create the final version of the app</li>
    <li>B) To test and refine the user experience and functionality before full development</li>
    <li>C) To ensure that the app’s design meets technical specifications</li>
    <li>D) All of the above</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(1)">Show Answer</p>
<p id="answer1" class="answer">Answer: B) To test and refine the user experience and functionality before full development<br>**Explanation**: Prototyping is used to test user flows, design, and functionality early in the process before committing to full-scale development.</p>

<!-- Question 2 -->
<p>2. Which of the following languages is primarily used for iOS app development?</p>
<ul>
    <li>A) Kotlin</li>
    <li>B) Swift</li>
    <li>C) Java</li>
    <li>D) Python</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(2)">Show Answer</p>
<p id="answer2" class="answer">Answer: B) Swift<br>**Explanation**: Swift is the primary programming language for developing iOS apps. It was introduced by Apple to replace Objective-C and is widely used for building apps for iPhones and iPads.</p>

<!-- Question 3 -->
<p>3. What does the Agile methodology emphasize in app development?</p>
<ul>
    <li>A) Fast prototyping</li>
    <li>B) Iterative development with regular feedback</li>
    <li>C) Strict adherence to the project plan</li>
    <li>D) All of the above</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(3)">Show Answer</p>
<p id="answer3" class="answer">Answer: B) Iterative development with regular feedback<br>**Explanation**: Agile focuses on iterative development, continuous feedback, and flexibility to accommodate changes, which makes it an ideal approach for app development projects where requirements may evolve.</p>

<!-- Question 4 -->
<p>4. Which of the following are benefits of using cloud services for app development?</p>
<ul>
    <li>A) Scalability</li>
    <li>B) Cost-efficiency</li>
    <li>C) Flexibility in managing resources</li>
    <li>D) All of the above</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(4)">Show Answer</p>
<p id="answer4" class="answer">Answer: D) All of the above<br>**Explanation**: Cloud services offer scalability, cost-efficiency, and flexibility in managing resources, making them a popular choice for hosting, storage, and app infrastructure.</p>

<!-- Question 5 -->
<p>5. What is an example of a cross-platform framework?</p>
<ul>
    <li>A) Swift</li>
    <li>B) React Native</li>
    <li>C) Kotlin</li>
    <li>D) All of the above</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(5)">Show Answer</p>
<p id="answer5" class="answer">Answer: B) React Native<br>**Explanation**: React Native is a popular cross-platform framework that allows developers to write code once and deploy it on both iOS and Android. It uses JavaScript and React for building mobile applications.</p>

<!-- Question 6 -->
<p>6. Which of the following are common revenue models in mobile apps?</p>
<ul>
    <li>A) Freemium</li>
    <li>B) Subscription</li>
    <li>C) In-app Advertising</li>
    <li>D) All of the above</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(6)">Show Answer</p>
<p id="answer6" class="answer">Answer: D) All of the above<br>**Explanation**: Freemium, subscription, and in-app advertising are all common revenue models used in mobile apps to generate income. Developers often use a combination of these models depending on the app’s purpose and audience.</p>

<!-- Question 7 -->
<p>7. What does "responsive design" refer to in app and web development?</p>
<ul>
    <li>A) The app’s ability to load faster</li>
    <li>B) The app’s ability to adapt to different screen sizes and resolutions</li>
    <li>C) The app’s ability to send notifications</li>
    <li>D) The app’s ability to store user data locally</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(7)">Show Answer</p>
<p id="answer7" class="answer">Answer: B) The app’s ability to adapt to different screen sizes and resolutions<br>**Explanation**: Responsive design ensures that an app or website looks good and functions well on various devices, including smartphones, tablets, and desktop computers, by adjusting layouts and elements based on screen size.</p>

<!-- Question 8 -->
<p>8. What is an advantage of using APIs in app development?</p>
<ul>
    <li>A) Allows for integration with third-party services</li>
    <li>B) Reduces the need for custom code</li>
    <li>C) Speeds up development time</li>
    <li>D) All of the above</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(8)">Show Answer</p>
<p id="answer8" class="answer">Answer: D) All of the above<br>**Explanation**: APIs (Application Programming Interfaces) allow developers to integrate third-party services, reduce custom coding needs, and speed up development by providing pre-built functions and data.</p>

<!-- Question 9 -->
<p>9. What is a key characteristic of the Waterfall methodology in app development?</p>
<ul>
    <li>A) Flexibility to accommodate changes</li>
    <li>B) Sequential phases with clearly defined goals</li>
    <li>C) Continuous feedback and iteration</li>
    <li>D) Emphasis on user testing early in development</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(9)">Show Answer</p>
<p id="answer9" class="answer">Answer: B) Sequential phases with clearly defined goals<br>**Explanation**: The Waterfall methodology follows a linear, sequential approach where each phase of development (e.g., design, coding, testing) must be completed before moving to the next. It’s less flexible than Agile and doesn’t handle changes as well.</p>

<!-- Question 10 -->
<p>10. What is the key difference between Native and Hybrid apps?</p>
<ul>
    <li>A) Native apps are built specifically for one platform, while hybrid apps work across platforms</li>
    <li>B) Native apps require fewer resources to develop</li>
    <li>C) Hybrid apps offer better performance</li>
    <li>D) Native apps can be written in any programming language</li>
</ul>
<p class="show-answer" onclick="toggleAnswer(10)">Show Answer</p>
<p id="answer10" class="answer">Answer: A) Native apps are built specifically for one platform, while hybrid apps work across platforms<br>**Explanation**: Native apps are built specifically for one platform (e.g., iOS or Android) using platform-specific languages, while hybrid apps are built using web technologies and can run on multiple platforms.</p>

<script>
    function toggleAnswer(questionNumber) {
        const answerElement = document.getElementById('answer' + questionNumber);
        if (answerElement.style.display === 'none' || answerElement.style.display === '') {
            answerElement.style.display = 'block';
        } else {
            answerElement.style.display = 'none';
        }
    }
</script>

</body>
</html>
