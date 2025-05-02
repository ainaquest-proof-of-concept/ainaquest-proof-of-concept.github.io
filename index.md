<div class="centered-header">
   <h1 style="font-size: 2.5em;"> Project Description </h1>
</div>
**Proof of Concept:**  is an easily accessible mobile app designed to foster a deeper connection with the natural world-specifically, the plants that surround us. With this app, users can simply point their mobile device at a plant in any real-life environment to quickly identify it. Upon scanning, the app generates a collectible card for the plant, providing interesting facts, care tips, and ecological information.

We are actively developing a dynamic point-based reward system and interactive leaderboard. This system not only gamifies plant identification, but also encourages users to explore and learn about the diverse flora in their local area. Users earn points through every successful plant scan and identification, with the points varying based on the plant's category (canoe, native, or invasive). This encourages users to gain a deeper understanding of their environment.

---

<div class="centered-header">
   <h2 style="font-size: 2.5em;"> Updates </h2>
</div>


---

### Meeting 1 (Jan 27, 2025) 

**Kick-Off Week**
We began this project with a brainstorming session to explore multiple creative directions. This included:
1. **Plant Card Game**: Gamified approach of collecting and trading cards
2. **Point and Leaderboard System** Methods to award users based on amount of plants identified, fostering friendly competition.
3. **Virtual Garden**: An ability to visualize what the user has collected over time.

---

### Meeting 2 (Feb 5, 2025)

After evaluating our initial ideas, we decided to focus on collecting plants on a **Point and Leaderboard** system. During this week, our team refined the concept, and began outlining the data structures and scoring mechanisms that will form the backbone of the interactive leaderboard.

---

### Meeting 3 (Feb 12, 2025) 

**Weekly Tasks:**
1. **Integration:**
   Worked to get last semester's codebase running for all members.
2. **API Exploration:**
   We dove deeper into the API used by the previous team to understand its strengths and limitations, streamlining the process.
3. **Leaderboard Implementation:**
   Initial coding efforts began to lay the groundwork for the leaderboard page, setting up the UI framework and basic logic.

<div style="text-align: center; padding-bottom: 1em 0;">
   <h3> <strong> Leaderboard Implementation: Beginning </strong></h3>
   <img src="/assets/images/Expo_Go.jpg" alt="Leaderboard Implementation" style="max-width: 35%; height: auto;">
</div>

---

### Meeting 4 (Feb 20, 2025)

**Weekly Tasks:**
1. **Legacy Support:**
   Ensured the last semesters was fully operational for Delsin and Lloyd
2. **API and Hosting Transition:**
   We began migrating the PlantNet API integration transferring DigitalOcean hosting responsibilities from the previous team to now.
3. **Enhanced Leaderboard Functionality:**
   Further development on the leaderboard's functionality was undertaken, including creation of the UI and point allocation.

<div style="text-align: center; padding-bottom: 1em 0;">
   <h3> <strong> Leaderboard Implementation: Final </strong> </h3>
   <video controls style="max-width: 35%; margin: 0 auto;" width="560">
      <source src="assets/videos/Expo_Go_Video_Final.mp4" type="video/mp4">
      Your browser does not support this video.
   </video>
</div>

---

### Meeting 5 (Feb 27, 2025)

**Weekly Tasks:**
1. **Global vs. Friends Leaderboard:**
   Held detailed discussions to define the goals and metrics for implementing a dual leaderboard system-one for friends-based rankings and another for global standings.
2. **Profile Page Initialization:**
   Introduced and finalized concepts for the profile page to enhance user personalization and engagement.
3. **Plant Reference Database:**
   A preliminary list of plants was compiled to serve as in-app references, ensuring capture has a defined dataset.
4. **Camera Functionality:**
   Initial steps were taken to integrate and optimize the camera functionality, the key for scanning and identifying plants, as previously it was reported to have bugs pertaining to its responsiveness

---

### Meeting 6 (March 06, 2025)

**Weekly Tasks**
1. **API Integration**
   - Switched over the new plant identification endpoint.
   - All requests now point to the PlantNet V2 identification endpoint.
   - Authentication keys now loaded from environment variables.
2. **Login and Logout Pages (Front-end)**
   - User identification and authentication flows.
   - "Sign in" and "Sign out" pages designed in React Native/Expo
   - Toggled in navigation and styled in place in the user menu.
3. **Authentication Backend**
   - Django REST frameworks was incorporated into the backend for user registration, login, and logout.
   - Registration and JWT token issuance incorporated (work in progress) but introduced via /api/register/ & /api/token/.
   - Logout endpoints clearing the token cache.
4. **Friends and Global Toggle**
   - UI to switch between Friends view and Global Leaderboard.
   - Toggle button renders and switches state.
5. **Leaderboards Pages**
   - Displays user leaderboard ranking globally and amongst friends.
   - Both screens fully implemented on the front-end.
   - Static/sample data rendering correctly.
6. **Profile Page**
   - Implementation and UI aesthetic in progress.

---

### Meeting 7 (March 13, 2025)

**Weekly Tasks**
1. **Completion of Sign In - Sign Up**
   - All UI Components for Sign-in Sign-Up are complete and styled.
   - Form inputs validate basic requirements (non-empty, email format)
2. **Work on Profile Page**
   - Layout and placeholder components are in place.
   - Navigation to/from profile page working.
3. **Plant Database Integration**
   - Connecting the mobile app to the plant identification API database (PlantNet)
   - Initial API client code added to the project.
   - Test requests return sample JSON in the console.

---

### Meeting 8 (April 08, 2025)

**Weekly Tasks**
1. **Collection Page Redesign**
   - Revamp the "Collections" screen to improve functionality, visual appeal, and data presentation.
   - Wireframes and Mockup completed.
   - New Layout components (cards, filters) scaffolded in React Native.
2. **Plant Identification Workflow Improvement**
   - Streamline the code and processes that take a users' photo, call the PlantNet API, and render results in the app.
   - Core API Integration is functional but lacking (occassional failures, inconsistent parsing).
   - Basic Result UI (plant card) displays sample data.
3. **AR Mini Project in Unity**
   - Exploring Augmented Reality interactions for plant identification or visualization using Unity and AR Foundation.
   - New Unity Scene and Project created.
   - Experimented with AR plane detection and object placement with sample picture placeholder and asset.
   - Prototype inspiration: [Let's Make an AR App in 15 Minutes! (Beginner Friendly)](https://www.youtube.com/watch?v=GfS72wqKQ_g)
4. **Authentication Flows Finalization**
   - Completed the end-to-end login, logout, and signup functionality completely across front-end.
   - Screens for the above are built and styled.
   - Backend endpoints for registration in JWT-based login and logout exist, but need integration.
  
<div style="display: flex; justify-content: center; gap: 2em; flex-wrap: wrap;">
   <div style="text-align: center;">
      <h3><strong>Sign In</strong></h3>
      <img src="/assets/images/sign-in.png" alt="Sign In" style="max-width: 200px; width: 100%; height: auto;">
   </div>
   <div style="text-align: center;">
      <h3><strong>Sign Up</strong></h3>
      <img src="/assets/images/sign-up.png" alt="Sign Up" style="max-width: 200px; width: 100%; height: auto;">
   </div>
</div>
---

<h2 style="text-align: center"> Poster has been started, and in progress, will have the final output by April 17th.</h2>

---

### Meeting 9 (April 17, 2025)

**Weekly Tasks**
1. **AR Demo Enhancement**
   - Core AR demo complete: Can detect certain surfaces and place plant model/cards in the environment.
   - Future Changes:
     - Polish interactions (tap to zoom, drag to reposition)
     - Optimize performance
     - Dynamic model generation
2. **Completion of Collection Page**
   - Fully revamped the "Collections" screen to display user plant cards with improved layout.
   - Redesigned UI implemented with enhanced styling.

---

<h2 style="text-align: center;"> Poster Draft Completion. </h2>

---
### Meeting 10 (April 24, 2025)

**Weekly Tasks**
1. **Camera Integration**
   - The in-app camera feature captures plant images for identification.
   - All camera related bugs have been resolved, image capture and preview work reliably.
2. **AR Module Development**
   - Augmented reality prototype for visualizing plant data in a real-world context.
   - AR demo now up and running; basic plant detection and object placement operational.
3. **Fixes and Refinements**
   - Polishing, and listing critical fixes to be resolved.
   - Priority in focusing on the more important features to be presentable before the deadline.

<div style="text-align: center; margin: 2em 0;">
   <h3> <strong> Camera Functionality Example </strong> </h3>
   <video
      controls
      style="max-width: 35%; margin: 0 auto;" width="560"
   >
   <source src="/assets/videos/plant-recording.mp4" type="video/mp4">
   Your browser does not support this video.
   </video>
</div>

---

### Meeting 11 (May 01, 2025)

<div class="centered-header">
   <h2 style="font-size: 2.5em;"> Final Meeting </h2>
</div>

**Weekly Tasks**
1. **Point Management**
   - Points are now being calculated correctly, stored, and displayed on the user dashboard.
   - Varies based on the plant type (canoe, native, invasive).
   - Incremental updates (when a new plant is identified) refresh total without errors.
2. **Plant "Found" Tracking**
   - The app marks each plant as found once the user identifies it, preventing duplicate rewards and enabling collection progress.
   - The "found" flag toggles correctly on identification and persists in the local collection state.
   - Duplicate scans do not grant extra points.
  
<div style="display: flex; justify-content: center; gap: 2em; flex-wrap: wrap;">
   <div style="text-align: center;">
      <h3> <strong> Plant Card </strong> </h3>
      <img src="/assets/images/plant-card.jpg" alt="Sign In" style="max-width: 200px; width: 100%; height: auto;">
   </div>
   <div style="text-align: center;">
      <h3> <strong> Plant Identification </strong> </h3>
      <img src="/assets/images/plant-information.jpg" alt="Sign Up" style="max-width: 200px; width: 100%; height: auto;">
   </div>
</div>
