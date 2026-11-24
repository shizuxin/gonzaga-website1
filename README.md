# gonzaga-website

# DES.ART | Digital Creative Portfolio and Commission Website

A personal portfolio and commission website for **DES.ART**, where I can showcase my creative works and offer services such as video editing, motion graphics, digital illustration, and graphic design.

This website is my project for **FT-LAB Activity 2: Website Proposal & Landing Page Development**.

**Status:** Draft / Front-end Prototype  
**Target Completion:** November 30, 2026

---

## About the Project

DES.ART is a personal creative website where visitors can view my artworks, check the services I offer, and see their starting prices. It also includes an availability calendar where clients can check my schedule before sending a commission request.

The website is also designed to make it easier for interested clients to contact me. They can use the booking form to submit their requests or the message form to send inquiries.

Please note that submitting a booking request does not automatically confirm a commission. I still need to review and approve the request first.

## Website Features

- **Home** – Introduces DES.ART with a short description and buttons that lead to the booking form and the portfolio.
- **Portfolio** – Shows a collection of 13 digital artworks that open in full size when clicked, with a link to my Facebook page for more samples.
- **Services & Rates** – Lists the seven services I offer, including their starting prices in Philippine pesos.
- **Availability** – Displays a December 2026 calendar showing which dates are available, busy, or unavailable.
- **Commission Info** – Explains the commission process through five steps and includes frequently asked questions.
- **Book Now** – Contains a form where clients can submit their commission details.
- **Contact / Message Me** – Shows my contact information and provides a form for sending messages.
- **About the Creator** – Includes a short introduction about me and the software I use for my creative works.

## Folder Structure

```text
gonzaga-website/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── bg-green.jpg
│   ├── digital-art-01.jpg
│   ├── digital-art-02.jpg
│   └── ... digital-art-13.jpg
└── README.md
```

- `index.html` – Contains the main content and structure of the website.
- `css/style.css` – Handles the website's colors, fonts, spacing, and overall layout.
- `images/` – Contains the background image and the digital artworks used in the website.
- `README.md` – Contains the project information and instructions.

## How to Run the Website

1. Download or clone the project from its repository.
2. Open the project folder.
3. Find and open `index.html` using Google Chrome or Microsoft Edge.
4. If you're using Visual Studio Code, you can also right-click `index.html` and select **Open with Live Server**.
5. Make sure the `css` and `images` folders stay in the same location as `index.html`. Otherwise, some styles and images may not display properly.

## Tools and Technologies Used

- Visual Studio Code – for writing and editing the code.
- HTML – for the structure and content of the website.
- CSS – for the design and layout.
- Git and GitHub – for version control and project storage.
- Google Chrome – for testing and checking the website.

## Design and Color Scheme

For the overall appearance, I chose a dark green theme with a clean and minimal style. The colors come from my green-haired girl artwork, and I wanted the website to look modern while still matching the style of my digital artworks and creative projects.

| Color       | Hex Code  | Purpose                                      |
| ----------- | --------- | -------------------------------------------- |
| Dark green  | `#0E1A12` | Main background                              |
| Forest green| `#16281B` | Header, calendar, contact box, and form fields |
| Leaf green  | `#7FD24A` | Buttons, step numbers, and prices            |
| Soft cream  | `#F1F5EC` | Main text                                    |
| Sage gray   | `#B8C5B0` | Small and descriptive text                   |
| Moss        | `#2A4030` | Lines and borders                            |
| Amber       | `#D49A45` | Busy dates on the calendar                   |

**Fonts:**

- Poppins – for headings and body text.
- Arial – as the backup font if Poppins does not load.

## CSS Techniques Used

While developing the website, I used different CSS techniques to organize the content and make the layout easier to manage.

- **CSS Grid** – Used for the calendar and the forms.
- **CSS Columns** – Used to arrange the portfolio gallery.
- **CSS Counters** – Used to automatically number the steps in the Commission Info section.
- **HTML `<details>` element** – Used for the FAQ section so visitors can click and expand the answers.
- **Media Queries** – Used to adjust the website layout for smaller screens, particularly mobile devices with a screen width of 700px and below.

## Notes and Limitations

There are still some things that need to be improved in this version of the website.

- The website is currently front-end only. The booking and message forms are available visually, but they do not send or store submitted information yet.
- A backend, database, or external form service will be needed to make the forms fully functional.
- Some JavaScript features, such as clickable calendar dates, were included in the original plan but have not been implemented yet.
- The prices and commission policies currently displayed are sample information and can still be updated.

## Developer Information

**Destiny Andrea Gonzaga**  
Bachelor of Science in Information Technology (BSIT)  
Central Mindanao University

- **Phone:** 09195123105
- **Email:** shizuxin1@gmail.com
- **Facebook:** [facebook.com/sh1zu.1](https://www.facebook.com/sh1zu.1)

---

© 2026 DES.ART. All rights reserved.
