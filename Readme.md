### Hi there 👋, I am Badhon Sarker
#### Junior Frontend Web Developer

![I am a junior front end web developer](68747470733a2f2f7777772e6368617270656e692e636f6d2f7374617469632f696d616765732f6172726f772d66756e6374696f6e732d696e2d636c6173732d70726f706572746965732d6d696768742d6e6f742d62652d61732d67726561742d61732d77652d7468696.gif)



### About me:
I am Badhon Sarker, a passionate front-end web developer and Political Science undergrad at the University of Chittagong. My fascination with coding led me to master HTML, CSS, JavaScript, and React, with solid knowledge in Node, MongoDB, and Express JS. Currently, I'm working on various React projects, including full-stack ones.

I strive to continuously learn and master advanced technologies, with the goal of becoming a leading Full Stack developer in the industry.

- 🌱 I’m currently learning **Next JS**

- 📫 How to reach me **badhonsarker38@gmail.com**


<p align="left">
</p>

<h3 align="left">Skills:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> </p>
 


{
  gson: repository(owner: "google", name: "gson") {
    ...RepoFragment
  }
  martian: repository(owner: "google", name: "martian") {
    ...RepoFragment
  }
  keyboard: repository(owner: "jasonrudolph", name: "keyboard") {
    ...RepoFragment
  }
}

fragment RepoFragment on Repository {
  name
  refs(first: 100, refPrefix: "refs/heads/") {
    edges {
      node {
        name
        target {
          ... on Commit {
            id
            history(first: 0) {
              totalCount
            }
          }
        }
      }
    }
  }
}

