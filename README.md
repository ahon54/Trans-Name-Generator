# Trans Name Generator React App

This is a React app made for a hackathon. 
The concept is for people transitioning from male to female or vice versa to provide name suggestions for them that are phonetically similar.
Name suggestions are found comparing the user input name and a list of names with levenshtein distance (difference in two words by counting the minimum number of changes to turn one word to the other).

Another update to be done would be an additional option to choose gender neutral names as a more generalist choice, since gender is not that straightforward for 2 ways.

To run this application: <br>
Clone the repo. <br>
Run npm ci or npm install on the folder <br>
Install Expo on a phone (tested on Android OnePlus 6). <br>
Run npm start <br>
Using Expo, scan the QR code generated by the running program.

### Main screen, mode selector

<img src="https://github.com/user-attachments/assets/f4b14d99-00b9-4852-8069-b862fcca1a18" alt="Screenshot" height="300">

### Name search

<img src="https://github.com/user-attachments/assets/45da055f-a503-46ca-82ed-a357058892f4" alt="Screenshot_20240412-164722" height="300">

### Choosing to start with a first letter of the name instead of doing a name input

<img src="https://github.com/user-attachments/assets/18cdd6f6-1488-46bf-b44b-b68dc0ae44c3" alt="Screenshot_20240412-164716" height="300">

### Example output for Adrian

<img src="https://github.com/user-attachments/assets/3516f671-2bb8-4064-a9c2-6b4234d36b4e" alt="Screenshot_20240412-164507" height="300">
