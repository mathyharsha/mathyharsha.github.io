# Website Redesign - Jon Barron Style

This redesigned website follows the clean, minimalist academic style of Jon Barron's personal website.

## Files Included

1. `index.html` - Main website file
2. `stylesheet.css` - CSS styling file

## Required Images

Create an `images/` folder and add the following images:

### Logo Images (approximately 80px width):
- `helsinki_logo.png` - University of Helsinki logo
- `marvell_logo.png` - Marvell Semiconductor logo
- `uf_logo.png` - University of Florida logo
- `iitgn_logo.png` - IIT Gandhinagar logo
- `svnit_logo.png` - SVNIT logo

### Publication Images (160x160px):
See IMAGE_GUIDE.md for complete list of all 13 publication images needed:
- Main publications (9 images)
- Additional publications (4 images)

Note: If you don't have specific publication images, you can use:
- Simple diagrams from your papers
- Representative figures from the research
- Or placeholder images with solid colors

**Refer to IMAGE_GUIDE.md for the complete naming guide and suggestions for each image.**

## Setup Instructions

1. Create folder structure:
   ```
   website/
   ├── index.html
   ├── stylesheet.css
   ├── images/
   │   ├── (all logo and publication images)
   └── profile_pic_website.jpeg
   ```

2. Add your profile picture as `profile_pic_website.jpeg` in the root directory

3. Add your CV PDF as `Curriculum_Vitae.pdf` in the root directory

4. Place all required images in the `images/` folder

## Key Features

- **Clean, minimal design** - Focus on content, not decoration
- **Two-column layout** for publications with images on the left
- **Hover effects** on links (blue → orange)
- **Responsive** table-based layout that works on all screen sizes
- **Professional typography** using Lato font family
- **Easy to update** - simply edit the HTML to add/remove publications

## Customization

To add a new publication:
1. Copy an existing publication `<tr>` block
2. Update the image path, title, authors, venue, and links
3. Add the paper description

To modify colors:
- Primary link color: `#1772d0` (blue)
- Hover color: `#f09228` (orange)
- These are defined in `stylesheet.css`

## Credits

Website design adapted from [Jon Barron's academic website](https://jonbarron.info/).
Source code available at: https://github.com/jonbarron/jonbarron.github.io
