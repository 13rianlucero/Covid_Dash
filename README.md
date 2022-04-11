![GATSBY](https://img.shields.io/badge/Gatsby-%23663399.svg?style=for-the-badge&logo=gatsby&logoColor=white)
![YARN](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)
![NETLIFY](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)
![VSCODE](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![REACT](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

-------------------------------------------------------

# Covid Dashboard
- Created a dynamic, COVID-19 dashboard website that updates Global Statistics in Real-Time
- Interactive World Map (Leaflet API): displaying each country's Covid Stats
- Statistical Analysis: Case & Recovery Data tables, Critical Cases per death Data Chart
- Historical Metrics: 2 Time Data Charts, Today vs. All-Time
- Hosted live via Netlify: [![COVID DASHBOARD](https://img.shields.io/badge/Vanilla-Covid%20Dashboard%20Website-blueviolet)](https://vanilla-covid-dashboard.netlify.app/)

```
CREATING a GATSBY LEAFLET STARTER
(1) gatsby new directory_name
(2) cd directory_name
(3) yarn develop
(4) chrome on localhost:8000    (should see the (gatsby astronaut...)

############## SKIP ##################
(5) download from https://github.com/colbyfayock/gatsby-starter-leaflet
(6) manually replace the file by file, or folder by folder, as appropriate
try to run this again
(7) yarn develop (it fails, it wants sass)
######################################

(8) npm install sass --legacy-peer-deps
and after a few warnings, it will run
(9) yarn add charts.css This is for the chart css files
(10) yarn develop   (one more time, you should now see a gatsby leaflet map, 
                    with an astronaut centered on Washington, D.C.)
                   
                    
https://www.freecodecamp.org/news/how-to-add-coronavirus-covid-19-case-statistics-to-your-map-dashboard-in-gatsby-and-react-leaflet/

lsof -i tcp:8000    to find the pid of a process running on port 8000
kill -9 PID_OF_PROCESS

```
![ezgif-4-b01db5bea1](https://user-images.githubusercontent.com/47013770/162826938-db9196cd-0e8a-48ea-9ac3-8456e6eb0580.gif)
