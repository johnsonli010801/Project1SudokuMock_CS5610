# 📘 README — Project 1: Sudoku Mock Website

## 🔗 Links
- **GitHub Pages Site:** [https://johnsonli010801.github.io/Project1SudokuMock_CS5610/](https://johnsonli010801.github.io/Project1SudokuMock_CS5610/)  
- **GitHub Repository:** [https://github.com/johnsonli010801/Project1SudokuMock_CS5610](https://github.com/johnsonli010801/Project1SudokuMock_CS5610)  
- **Collaborator(s):** None (individual project)  
- **Video Walkthrough:** [Walkthrough Video](https://youtu.be/XM5AJ94jOvY)

---


## 📝 Writeup

### ❓ What was the most challenging piece of this assignment?  
The most challenging part was making the Sudoku grids look correct and aligning the subgrids (3×3 inside 9×9, 2×3 inside 6×6). CSS grid layout took time to get right, especially when combining borders and spacing. I also had to carefully structure my project folders so that each page had its own `index.html` with page-specific CSS while still sharing the `common.css` file. Overall, working with HTML was straightforward, but getting consistent responsive CSS styling was more challenging. This assignment took me around **15 hours** total.  

### 📱 What decisions did you make when you made your site mobile friendly?  
I decided to make the navbar responsive by ensuring it stays fixed at the top on desktop but adapts in mobile view. I used media queries so that elements scale properly and text/images shrink for smaller screens. I also applied flexbox/grid for the Sudoku boards so they keep a square aspect ratio across devices. The result is that the website looks clean on both a desktop browser and on an iPhone Pro 12 simulation in DevTools.  

### 🎨 What did you take into account when you developed the design of your website?  
I wanted the site to feel simple and consistent, so I used card layouts with rounded corners, drop shadows, and a dark-accent theme. The navbar highlights the current page, which makes navigation clearer. I am proud of the Sudoku grids since they look realistic without using JavaScript, and of the overall organization into folders which makes the site easy to maintain.  

### 🚀 Given more time or resources, what additional features would you add to your site in the future?  
I would add real puzzle logic with JavaScript so players could actually solve Sudoku puzzles and check answers. I would also add a functioning timer, a scoreboard that stores data, and user accounts with persistent logins. Another idea is to add theming options so players can switch between light and dark modes.  

### ⏰ How many hours did you spend on this assignment?  
~15 hours.  

### (Optional) Assumptions  
I assumed the timer and high scores only needed to be static mockups, not functional. I also assumed it was fine to use fake author names and user names in the selection and high score pages.  

### (Optional) Code/Design Sources  
- Navbar and grid layout: coded by me, but inspired by general CSS flexbox/grid tutorials.  
- Fonts: default system fonts only (no external imports).  
- Image: `homepage.png` (Sudoku board) stored locally in `/assets/img/`.  
