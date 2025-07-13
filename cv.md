# Viktoriia Berseneva
![Profile Picture](https://i.ibb.co/17zcNJy/photo.jpg)

## Contact Information
- **Email** [victoriaberseneva93@gmail.com]
- **Phone** +420608292780
- **LinkedIn** [https://www.linkedin.com/in/viktoriia-berseneva-8a87b3316/]

## Brief Self-Introduction
I am a versatile and dedicated professional with a robust background in English teaching and philology, holding a Master’s degree in English Philology. My expertise in language education, paired with an artistic foundation from Ivan Shadr Art College, enables me to create engaging, adaptable learning experiences. 
I’m transitioning to a new career path in frontend development after years as an English teacher. With a strong artistic sense and patience honed from teaching, I’m excited about the creative and problem-solving aspects of web development. My artistic background can enhance my design approach, helping create visually appealing websites, while my analytical skills enable me to efficiently identify and solve issues in code. Additionally, my proficiency in English supports my ability to work in diverse teams and engage with resources effectively.

## Skills
- **Languages & Linguistics**: English Philology, English as a Foreign Language Teaching, Linguistics, American & English Literature
- **Artistic Skills**: Academic Painting, Drawing Techniques
- **Tech & Tools**: HTML & CSS, JavaScript, React, Figma, Graphic Design programmes (Adobe Photoshop, Adobe Illustrator, Adobe InDesign)

## Code Examples
- **Codewars task**
- Description:
Our football team has finished the championship.

Our team's match results are recorded in a collection of strings. Each match is represented by a string in the format "x:y", where x is our team's score and y is our opponents score.

For example: ["3:1", "2:2", "0:1", ...]

Points are awarded for each match as follows:

    if x > y: 3 points (win)
    if x < y: 0 points (loss)
    if x = y: 1 point (tie)

We need to write a function that takes this collection and returns the number of points our team (x) got in the championship by the rules given above.

Notes:

    our team always plays 10 matches in the championship
    0 <= x <= 4
    0 <= y <= 4

- Solution:
```function points(games) {
  let totalPoints = 0;
for (let i = 0; i < games.length; i++) {
  let match = games[i];
  let scores = match.split(":");
  let x = Number(scores[0]);
  let y = Number(scores[1]);
   if (x > y) {
     totalPoints += 3;
   }
  else if (x === y) {
    totalPoints += 1;
  }
  
}  
  return totalPoints;
}
```

## Work Experience
### Web Designer (freelance)
Designed and developed modern, responsive websites for various clients. Created custom UI/UX solutions, wireframes, and visual designs aligned with client goals. Specialized in Figma  and front-end implementation using HTML, CSS, and basic JavaScript.


### Technical Support Specialist
Provided technical assistance and support to end users by diagnosing software and network issues. Ensured timely resolution of technical problems through effective troubleshooting and clear communication. 

### English Teacher | 2015 - Present
Taught general and specialized English in both physical classrooms and online platforms, consistently delivering personalized, effective lessons.


## Education

- **IT Guru**, online — Java Script course  (2025)
- **ReactGirls Academy**, Prague, Czech Republic — HTML, CSS, JavaScript, React, TypeScript  (2025)
- **Palacky University**, Olomouc, Czech Republic — Master’s in English Philology (2021 - 2024)
- **Ural State Pedagogical University**, Yekaterinburg, Russia — Bachelor’s in English Philology and Teaching (2015 - 2019)
- **Erasmus Program** — Krosno State College, Krosno, Poland, Exchange in English Philology (Feb - Jun 2018)
- **Ivan Shadr Art College**, Yekaterinburg, Russia — Training in Painting and Art Teaching (2010 - 2015)

## English Language
Proficient in English, with extensive teaching experience and practice in linguistic studies, capable of instructing and working with diverse student groups. 
