# Fleet Desk Assessment

This is the documentation for the Assessment on how to run the project locally and how i came to this design decision

### This is a React Project

#### Execute the code

---

- you'll be needing **_npm_** to run the project

1. Head over to the root of the project and do a `npm install` to install the dependencies
2. run `npm start` to start the project

#### Run the Project

---

1. After `npm start` head to the **_localhost://3000_** to view the project
2. You'll be seeing 4 Columns and 4 Tasks on the page
3. Drag a Task and Drop it to the next column i.e **in progress** , **awaiting review** and **DONE**

**_Note_**: _The Drag and Drop is implemented in a way that if a task is not in progress yet it can't be directly moved to done, so it has to be in the next column first to reach the final column_

### DESIGN AND COLOR PARAMETERS

- The Design of this Projet is Very Simple, There are only 3 colors used apart from black and white

1. **<span style="color:red">RED</span>**: Denotes the Pending Task (_Red color gets the **<span style="color:red">attention</span>** of the user_)
2. **<span style="color:yellow">YELLOW</span>**: Denotes the Ongoing Tasks (Yellow implies a state of activity or **<span style="color:yellow">progress</span>** without being fully completed or resolved.)
3. **Green**: Denotes the Tasks that are completed (Green color gives a sense of **<span style="color:green">Completion</span>**)

### LIVE URL

[FleetDesk Assessment Live Url](https://fleetdeskassessment.vercel.app)
