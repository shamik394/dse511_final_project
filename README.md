# dse511_final_project_sb

Problem:

  Ever since fifth or sixth grade, I’ve been captivated by the wonders of space flight. Back then, I dreamed of becoming an astronaut, though I didn’t yet grasp the immense risks involved or the sheer difficulty of being selected for NASA’s Astronaut Corps. In sixth grade—which now feels like a lifetime ago—I was given an assignment to document the names of all the manned Apollo missions, their crews, and their historical significance. That assigment opened a door to a lifelong fascination. I poured over the stories of the Mercury Seven astronauts, the ten Gemini missions, and all eleven Apollo missions (from Apollo 1 and Apollo 7 through Apollo 17). My curiosity was fueled by Alan Dyer’s book Mission to the Moon, which brought these incredible achievements to life.

  While I’m not solving a specific problem here in this project, I think it would be visually captivating to create a timeline of key NASA missions and their launch dates. I also visualized a simplified, hypothetical 3D flight paths for Apollo 8 and Apollo 13, showcasing the beauty and complexity of these iconic missions.

The breakdown:

Part A: I visualized a timeline of key NASA missions, including Friendship 7 , Gemini IV, and Apollo 11.

Part B: Creates a simplified, hypothetical 3D flight path for Apollo 8, illustrating its Earth orbit, trans-lunar trajectory, lunar orbit, and return to Earth.

Part C: Simulates a hypothetical 3D flight path for Apollo 13, incorporating the trans-lunar trajectory, lunar approach, and the critical Service Module (SM) explosion event.

Data:

Part A: I gathered data for this section from two key sources:

Note 1: Apollo 13 by Jim Lovell, the mission’s Commander, and coauthor Jeffrey Kluger. 

Note 2: A Man on the Moon: The Voyages of the Apollo Astronauts by Andrew Chaikin.

Note 3: I can provide the specific pages in the books that support my data if needed.

Part B: Hypothetical data

Part C: hypothetical data

Approach: 

Part A: For Part A, I created a timeline visualization of key NASA missions: Mercury (Friendship 7), Gemini IV, and Apollo 11. The approach involved the following steps:

1. Define the Mission Class: I implemented a Mission class to represent each space mission. This class includes attributes such as the mission name and its launch date, stored in a structured format.

2. Create Mission Instances: Using the Mission class, I instantiated objects for the selected missions:

- Mercury with a launch date of February 20, 1962.
- Gemini IV with a launch date of June 3, 1965.
- Apollo 11 with a launch date of July 16, 1969.

3. Helper Function for Parsing Durations: I wrote a helper function, parse_duration, to process mission durations in string format and convert them into a timedelta object. While not used directly in this section, it lays the groundwork for further analysis of mission timelines.

4. Plot Launch Dates: Using matplotlib, I visualized the launch dates of the missions as points on a timeline. Each mission was represented as a marker on the x-axis, labeled with its name.

5. Customizations:

- Removed the y-axis ticks for simplicity.
- Added a title and x-axis label for clarity.
- Included a legend to associate each marker with its respective mission.

Part B: 

  For Part B, I dcreated a simplified 3D flight path for Apollo 8 using Python's matplotlib. Key mission phases—Earth orbit, trans-lunar trajectory, lunar orbit, and return to Earth—were represented as distinct paths. A blue scatter marked Earth as the starting point, and a grey scatter represented the Moon as the final destination. This visualization highlights the mission's significant milestones.

Part C: 

  For Part C, I simulated a hypothetical 3D flight path for Apollo 13. The trans-lunar trajectory and return path included a critical event: the Service Module explosion, marked along the trajectory to emphasize its dramatic course correction. The visualization provided a clear depiction of this pivotal mission's challenges.



  

