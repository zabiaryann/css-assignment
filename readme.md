# Cloning and Pushing to Your Own Repository

1. Fork this repository by clicking the "Fork" button in the top right corner of this page. This will create a copy of this repository in your GitHub account.
2. Clone your forked repository to your local machine using the following command in your terminal:
    - `git clone https://github.com/your-username/css-assignment.git`
    - Replace `your-username` with your GitHub username.
3. Make changes to the files in your local repository as directed in the exercises.
4. After making changes, add, commit and push your changes to your remote repository using the following commands in your terminal:

```
git add .
git commit -m "Add changes as directed in the exercises"
git push origin main
```

Replace `main` with the name of the branch you want


# Section 1: Selectors in CSS + Box Model

## Task 1: Targeting Elements by Tag Name + Border
- Select all 'p' tags and change the font-size to 16px
- Finally, add a border around all p elements with a 1px solid line of any color you choose

## Task 2: Targeting Elements by Class + Padding
- Find the 'nav' element in index.html
- Give it a class (make sure it is descriptive and easy to understand)
- Below this comment, target the class you just made and give it a pretty background color
- Give it 20px of padding - note that the background color 'grows' around the text

## Task 3: Targeting Elements by ID + Margin
- Take a look at the input element with id="name" in index.html
- Below this comment, target that element by its ID and give it a border radius of 2em
- Finally, add 15px of margin to the bottom of that element. Note that it pushes the other inputs down

## Task 4: Targeting Elements by Descendant Selectors
- Take a look at the structure of the unordered list in the <nav> element
- Below this comment, target all <a> tags that are inside of <li> tags and give them text-decoration: none and a new color of your choice (this will make them look less like hyperlinks)

### Note:
- In this section, we'll cover the basics of CSS selectors and the box model, which are essential to understand when working with CSS.
- Each task will focus on a specific selector or property, and will provide instructions on how to use it to style elements on the page.

# Section 2: Display and Positioning in CSS

## Task 1: Inline-block
- Change the display property of the li items with class .inline-block to "inline-block". 
- Give it 5px of padding as well to space them out

## Task 2: position: relative
- Change the positioning of the .hero class to "relative" 
- Play around with its top, right, bottom, or left properties to position it wherever you want
- Give it text-align: center to make the text centered on your page

## Task 3: Display Grid
- Change the display property of the .features class to "grid"
- Give it 3 equal columns by using grid-template-columns: 1fr 1fr 1fr;
- Create a gap of 20px using the 'gap' property

## Task 4: Position Fixed 
- Change the positioning of the footer section to "fixed" 
- Adjust its bottom and left values. 
- Note that wherever you scroll on the page, it remains fixed on your viewport! 

### Note:
- In this section, we'll cover the basics of display and positioning in CSS, which are essential to create dynamic and responsive layouts.
- Each task will focus on a specific property, and will provide instructions on how to use it to position and style elements on the page.
