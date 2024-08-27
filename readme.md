# The Defsafe Cat Adoption Platform - Developers Test

## Overview:
You've been selected to create the website for the prestigious institution "The Defsafe Cat Adoption Platform." This will be a two-part application with both frontend and backend components. Your task is to develop a cat adoption platform where administrators can manage cat records, and users can view available cats and adopt them.

## Part 1: Admin Panel
This section is where an authenticated administrator can manage the cat listings on the platform.

### Requirements:

1. **Admin Login:**
   - Implement an authentication system allowing the admin to log in securely.
   - The admin should be required to log in before accessing any other functionality.
   - The submission must include the username and password for the admin account.

2. **CRUD Operations for Cats:**
   - **Create:** Allow the admin to add new cat profiles, including the following fields: name, description, and an image.
     - The image field can either accept a URL or allow the admin to upload an image directly.
   - **Read:** Display a list of all cat profiles.
   - **Update:** Enable the admin to edit the details of existing cat profiles.
   - **Delete:** Allow the admin to remove cat profiles from the platform.

3. **Stack:**
   - Use **Nuxt.js 3** server functions for handling all API operations.
   - **Prisma ORM** should be used for managing the database.
   - **Supabase** should be used for user authentication and database management.

## Part 2: Public Frontend
This section is where users can view the cats available for adoption and submit an adoption request.

### Requirements:

1. **Cat Listing Page:**
   - Display a list of all cats available for adoption.
   - Each cat's profile should include their name, description, and image.

2. **Adopt Button:**
   - Implement an "Adopt" button for each cat.
   - When clicked, the user should be able to fill out a simple adoption form.
   - Once submitted, the adoption request should be stored in the database.

3. **Confirmation:**
   - After submitting the form, display a confirmation message to the user.

4. **Frontend:**
   - Use **Nuxt.js 3** for the frontend.
   - Use **Nuxt.js 3** server functions for API requests.
   - Style the website using **Tailwind CSS**.
   - Use **Pinia** for State Management.
   - Use **Zod** for Validation.

## Page Designs

## Designs
- Page designs for both the App and Admin Panel are in the "/assets/Elements" folder

## Sources:
- **Color Palette:** [https://coolors.co/ffffff-4e2096-f9f8fb](https://coolors.co/ffffff-4e2096-f9f8fb)
- **Images:** Use assets from the `/assets/Elements` folder.
- **Font:** Inter (Google Fonts)
- **Icons:** Iconify

## Test Scoring:

### Points Table:
- **5 points:** Delivering the test with both frontend and backend in a single repository
- **5 points:** Correctly implementing authentication and protecting the admin backend
- **5 points:** Implementing all CRUD operations using Prisma
- **5 points:** Displaying the cat listing on the frontend
- **5 points:** Making the "Adopt" button functional and storing adoption requests
- **5 points:** Using Nuxt.js 3 server functions for the backend

### Bonus Points (Optional but recommended, calculated as a tiebreaker):
- **+5 points:** Making the website fully responsive
- **+5 Points:** Implement a feature that tracks the adoption status of each cat and disables the "Adopt" button for already adopted cats.
- **+5 Points:** Implement a random name generator for cat profiles.
- **+5 Points:** Implement an image upload feature for the cat profile images.
- **+3 Points:** Include comprehensive Unit Testing for both frontend and backend.
- **+3 Points:** Add a fade-out/in effect when transitioning between different cat profiles on the public frontend.

## TIPS
- You may use any Nuxt library you may see fit.
- Don't reinvent the wheel! Use Supabase Authentication to save time.
- Pay attention to the design details.

## Questions
- To make this process fair for everyone, this test is self-explanatory.
- We will not take or reply to any questions about the test itself. Every developer will get the exact same information. 
- If you have any doubts or questions, feel free to use your logic and deduction to solve the test however you see fit.

## Feedback and Hiring
- Completing this test on time guarantees you a feedback from our team.
- Competing this test on a minimum satisfaction level will grant you an interview with our team.
- This test is part of our hiring process, which consists of a test and an interview.

## Submission Instructions:
To finalize and submit the solution, ensure that both the frontend and backend are in a single GitHub repository. Deploy the solution on Vercel and send us an email to the address you received with the test link, with the subject "Defsafe Application Test - [Your Full Name]" including the following details:

- **Live Admin Panel URL hosted on Vercel:** [Insert URL here]
- **Admin Username and Password:** [Insert credentials here]
- **Live Website URL hosted on Vercel:** [Insert URL here]
- **GitHub Link for the code repository:** [Insert URL here]

