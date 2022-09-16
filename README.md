# Plotly email template demo

A repo for code reproducing an HTML email mockup for Plotly.

## Notes

Assets were exported from the Figma mockup where possible (the Plotly logo would not export as a single merged file so I used the brand logo from plotly.com). As such the logo is slightly pixelated - and for time I exported the social icons as a single image.  

In the final section, the side-by-side 50% columns are not exactly sized like the 60%-40% of the mockup. The second row of these 50-50 cols also stacks text-first, instead of duplicating the image-text order of the first row. With more time I would reverse this to be consistent, as well as tweak the spacing/padding/height between all columns on mobile. I chose to focus on reproducing the general layout, making it responsive, adding a dark version, and doing a minimum QA pass to address email client variability.

Images are hosted on gh-pages and are accessible for email clients.

Dark mode version is available at `dark.html`.

Parcel bundler was used for development.

Email was tested in gmail, hotmail, outlook clients, on MacOS desktop and iOS iPhone.