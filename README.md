# found_color_schemes

Hosting of images for *Found Color Schemes* website. The website is my personal collection of different color schemes from photos, websites, and paintings.

Updated: *14 Apr 2025*

## Steps to updating website

- Create JSON
	- Create entries
		- Name
		- Artist
		- Category (Paintings, Photography, Websites)
		- Image url
		- Color plane url
		- Oklch colors

		```
		{
		  "posts": [
		    {
		      "name": "A Dreary Day",
		      "artist": "Greg Rutkowski",
		      "category": "paintings",
		      "image": "https://thekymchee.github.io/found_color_schemes/00_images/greg-rutkowski-street-study-1600.jpg",
		      "plane": "https://thekymchee.github.io/found_color_schemes/01_color_planes/color_plane-greg-rutkowski-street-study-1600.svg",
		      "colors": [
		        "oklch(24.93% 0.0102 80.61)",
		        "oklch(36.57% 0.0052 121.72)",
		        "oklch(56.8% 0.0077 145.47)",
		        "oklch(66.15% 0.0045 121.6)",
		        "oklch(86.22% 0.0061 350.82)"
		      ]
		  	}
 		  ]
 		}

		```

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

	- [x] Credit artistpigments.org for color planes
	- [ ] Hover over card to make 'close' button more visible.
	- [ ] Check tablet, mobile, and extra large breakpoints
	- [x] Clean up styles
	- [x] Add json and csv to repo
	- [ ] Add other categories (animation)
		- Need to create space in the design
	- [ ] Fix Webflow audit issues
		- [x] Image alt text
		- [ ] Non-descriptive link content
	- [ ] Update Sublime plugin to export next to file



