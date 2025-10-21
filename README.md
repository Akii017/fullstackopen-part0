# Full Stack Open - Part 0 Submission

This folder contains my solutions for **Part 0** of the [Full Stack Open](https://fullstackopen.com/en/) course.  
In these exercises, I created **sequence diagrams** using **Mermaid syntax** to explain how the browser and server communicate in different situations.

---

## Exercise 0.4 - New Note Diagram

In this exercise, I illustrated what happens when a user writes a new note and saves it in the **traditional web app** version.  
The diagram shows:

- The browser sending an HTTP **POST** request to the server with the note content.  
- The server saving the note to the database and responding with **201 Created**.  
- The browser then reloading the page to show the updated list of notes.

---

## Exercise 0.5 - Single Page Application (SPA) Diagram

Here, I explained how the browser loads the **Single Page Application (SPA)** version of the app.  
The diagram includes:

- The browser requesting the main **HTML**, **JavaScript**, and **CSS** files from the server.  
- The JavaScript running in the browser and making a **GET** request to fetch existing notes in **JSON** format.  
- The browser then rendering the notes dynamically on the page without a full reload.

---

## Exercise 0.6 - New Note in SPA Diagram

In this exercise, I showed what happens when a user adds a new note in the **SPA** version.  
The diagram demonstrates:

- The browser sending a **POST** request with the note data to the server.  
- The server saving the note and returning a success response (**201 Created**).  
- The browser updating the notes list dynamically **without reloading the page**.

---

## How to View

You can open the `.md` files in VS Code or GitHub to view the rendered Mermaid diagrams.  
If using VS Code, install the **Markdown Preview Mermaid Support** extension for the best viewing experience.

---

**Name:** Akhil  
**Course:** Full Stack Open  
**Part:** 0 - Fundamentals of Web Apps
