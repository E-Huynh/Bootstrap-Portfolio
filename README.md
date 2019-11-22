# Responsive Portfolio
## What this project encompasses
---
The purpose of this project was to incorporate the Bootstrap framework in order to create a responsive portfolio page.
The page utilizes Boostrap's classes to layout the content and have it scale appropriately to the device's viewport.
Media queries were utilized in conjunction with flex box to create a navbar that stacked @640px width and changed appearance @768px.

[Project image](https://lh3.googleusercontent.com/IB2RHE8dzxTrNhGKICASZW3obOY7WzXwyZ2IX49EJxtixmCOdEzQNSrq0DOae3bdxaEXPBhZLfhtGlvJdWuuHWXw_oiuY1cS_Bfa8rOhDBG3Z4SGCZpbQJoNEDBQPTk7ttBlT2ldkD8SLmeqkeGadAS6A_nQIWQ8KVzkdtEMTaJYD4bHsOnTAUtH5xWSbtoM8HvcxTMBBk4gyAatnGmTt10fDIWBfWfeu55H9hsfQ-j__JnsRFRtRD9GgzsG7cvBuq-uJcyU2cthTWKYCG2arXUdQqhWF1vqD4UF3qnE_yPUHjULMXuDKGkvhl1PNrZIsH9qGA-2FhqZ3K7qiykrhLhwEEGlJ6iI3_A24w-Emw4AMTvwjwAwLvF-U78T1pxnRhhvIFN8NwwsBopOcv3cquIccAJyGrYMmu5HVLL0zgernNiY7QujtzlqQuJxdEUoGRoXB3wxWXZQYDb88zUWnFQ4VUo_fszJkT8eOgME1HjUnFyvQgnXDtY8Ag8sXPqx0JZh4di6aQA40XMWXpLPKhNzpAoE5m95mVHGYSjz2TfYfSaEd6fSexxISs7b1zy2rWD1-SZxP7SjT0y_lu6__B-9Xm6K2W5SP0Pnkss1XghTjnCO8fbfxFXXUzI5DcDTTo3J0vXcbCK7dqFdCSnXcklFcCPT0MXVRsdzSFP8AI7DWtr7Hmd2-1X3=w618-h854-no)
## Functionality
---
Below list some of the functionality written into this portfolio:

### Navbar
- At 640-768px the navbar is design to stack the Name and Link sections.
- Increasing the resolution to >768px, results in an appearance change.
- The navbar centers with the main content at all Boostrap breakpoints.
- Logo and links redirect to the appropriate page.

### Footer
- A sticky footer was utilized to be always be present at the bottom of the viewport.

### Content
- The size of the content div scales appropriately with size of the viewport.

   **About me page**
- The bio image takes up the entire width of the content div at <768px.
- Higher resolutions result in the image floated to the left, allowing the text to wrap.

   **Portfolio**
- The projects displayed here respond to the viewport width.

**Note to self** Replace the classes as so: projects **col-xs-4 col-sm-6 col-md-4**
- At <= 575px, a single project spans the entire width of the content div.
- At 576px - 780px, projects are displayed two to a row.
- At 780+px, projects are displayed 3 to a row.
   **Contact**
- Input fields scale to the width of the content div.
- Placeholder text in input form
