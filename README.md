## Your Name:

# CIDM 3312 Lab 4: Frontend 1

In this lab exercise you will create a razor page advertising the three tiers of ThoughtTronix's MindSync product. MindSync has an ad-supported free edition, a premium edition, and an enterprise edition. You will write a professional web page with the latest Bootstrap components, layouts, and classes. Your final web page should be suitable for a large company to use.

## Task 0: Prepare Your Environment

1. Create an ASP.NET Core Project using the `dotnet new webapp` command.

## Task 1: Make a Razor Page

1. Create a new razor page named `Pricing.cshtml`. You do not need a page model for this assignment.
2. Add a link to your page in the navbar. Edit Pages/Shared/_Layout.cshtml to add the link and call it Pricing.

## Task 2: Use Bootstrap To Create Your UI
1. Make your razor page look like the following (https://i.imgur.com/OqCPpbm.png):

![Image of webpage](https://i.imgur.com/OqCPpbm.png)

2. For this lab, you will use a few Bootstrap classes that you did not use in the lesson. I will explain those classes below.
3. Follow the Bootstrap UI requirements on this image to build your page (https://i.imgur.com/qVPp5uJ.png):

![Requirements](https://i.imgur.com/qVPp5uJ.png)

4. Start by creating the "MindSync Pricing" header and paragraph text underneath. Place both elements within a `<div class="p-3 text-center">`.
    - `p-3` sets padding all the way across at size 3.
    - `text-center` centers all the text that is inside the div.
    - The `<p>` tag will have classes `fs-5` for font-size 5 and `text-secondary` to set the color of the text to the secondary color (For our theme that is a shade of gray).
6. Next, create the row, columns, and cards.
    - Start with one row `<div class="row justify-content-center text-center">`
    - Within that row, place three columns each `<div class="col-3">`
    - Within each column place a Bootstrap Card component.
6. For each card, you will have a header and body. Within the body will be a card-title, card-text, and anchor tag (`<a>`) representing the button.
    - Add the correct classes and styling to each according to the diagram above.
7. After you build the cards, add a Compare plans header using `<h2 class="m-4 text-center text-secondary>`.
8. Next place the table according the requirements in the image.
    - Start with a row `<div class="row justify-content-center">`
    - Next put a column `<div class="col-6">`
    - Next put a `<div class="table-responsive">`
    - Finally add the table and populate it as shown.
    - Bring in the Bootstrap Icon support and use a `bi-check-lg` icon for the checkmarks. `<i class="bi bi-check-lg"></i>`
    - For empty cells in the table, you still need a `<td></td>` tag but it can be empty inside.
    - Use `class="text-start"` to left-align the features in column 1, while the rest of the table remains centered.
9. Your final web page should look very close to the image. It may be slightly different based on the size of your device, but not that much different.
10. Reach out if you have any questions or need help clarifying any of the UI requirements.
    
## Submit your assignment. You are now finished with Lab 5
