# found_color_schemes

Hosting of images for *Found Color Schemes* website. The website is my personal collection of different color schemes from photos, websites, and paintings.

Updated: *14 Apr 2025*

## Steps to updating website

- Create JSON
	- Create entries
		- Name
		- Artist
		- Category
		- Image url
		- Color plane url
		- Oklch colors

	- Run FCS Sublime Text script to add:
		- Color name tags
		- Hex colors
		- ID numbers
		- Export csv

- Handle images
	-Remove color plane background
	-Optimize/Compress with ImageOptim
	-Upload images to Github repo (Found Color Schemes)

- Update Webflow
	- Import csv
		- Double check connections (some fields do not automatically link up)
		- Fix any import errors
	- Publish and check website


	## TODO

	- [ ] Credit artistpigments.org for color planes
	- [ ] Hover over card to make 'close' button more visible.
	- [ ] Check tablet, mobile, and extra large breakpoints
	- [ ] Clean up styles
	- [x] Add json and csv to repo
	- [ ] Add other categories (animation)
			- Need to create space in the design



