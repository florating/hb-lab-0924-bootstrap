# LAB INSTRUCTIONS
This lab exercise was originally assigned on 9/24/21.
* Check out bootstrap.html (in templates) to see our navigation bar. (Work in progress!)
* Check out content.html (in templates) to see the content for the webpage. (Work in progress!)
* Unused: base.html (in templates)


### Resources
- [0924: lab instructions](https://fellowship.hackbrightacademy.com/materials/serft8/exercises/bootstrap/)
- [0924: bootstrap lecture](https://fellowship.hackbrightacademy.com/materials/t3/lectures/bootstrap/)
- [project handbook](http://fellowship.hackbrightacademy.com/materials/resources/project-toolkit-march-2017.pdf): with some details about wireframing
- [bootstrap](https://getbootstrap.com)
    - [navbar documentation](https://getbootstrap.com/docs/5.0/components/navbar/)
    - [Flex behavior](https://getbootstrap.com/docs/5.0/utilities/flex/)
    - [Display property](https://getbootstrap.com/docs/5.0/utilities/display/): show/hide content


### Task List
- [x] Setup
- [ ] Plan: quickly wireframe the content
- [x] Connect: include the CSS files for Bootstrap, Bootstrap icons, etc.
- [ ] Navigation
    - [ ] Connect this HTML with the HTML for page content!
    - [x] Make about, Contact, and Shop on the left.
    - [ ] Make Login, Favorite Melons, Settings, and Profile on the right.
    - [x] Add a brand.
- [ ] Content:
    - [x] Setup structure of divs using grid spacing
    - [x] Add a row with a table that's only visible on medium and large devices
    - [ ] Add text to the page that's similar to the demo screenshot
- [ ] Style:
    - [x] Add a link to a stylesheet with your own styles
    - [ ] Modify the stylesheet


### Extra Notes
`me-auto` - within a div class, it makes sure there's whitespace on the right side of the page, if there's room for it

> `mr-auto` - DON'T USE! this is likely deprecated and no longer works like `me-auto` for Bootstrap 5

`ml-auto` - within a div class, it makes sure there's whitespace on the left side of the page, if there's room for it


### CODE EXCERPTS
Example of grid-spacing within a div container.
```html
<body>
  <div class="container">
    <div class="row">
      <div class="col-3">
        <!-- SMALL COLUMN -->
      </div>
      <div class="col-9">
        <!-- LARGER COLUMN -->
      </div>
    </div>
    <div class="row">
      <div class="col-7">
        <!-- LARGER COLUMN -->
      </div>
      <div class="col-5">
        <!-- SMALL COLUMN -->
      </div>
    </div>

  </div>
</body>
```

