Theme Purchased from https://themeforest.net/item/lavar-portfolio-agency-jekyll-theme/15679321 - signed up as ajay610@gmail.com

Documentation: http://localhost:4000/doc/documentation.html

Jekyll templates updated with ideas from https://github.com/uracreative/ura.design
Permission: https://github.com/uracreative/ura.design/issues/6
Website: https://ura.design/

Theme for many xgolf centers: https://themesinfo.com/jupiter-child-wordpress-theme-rzh/latest
example: https://www.xgolfshelby.com/

## Tech notes
* Site switches between desktop and mobile at 1025 pixel width
    * Desktop styling: style.css
    * mobile styling: responsive.css

==================

## TODO
- Expand words on the website.
- Integrate with booking system, compare the booking system from Purnendu
- Need event enquiry form
- Separate Leagues page?
- Separate membership page
    - Member appreciation event 3 hours on a Thursday: closest to the pin challenge, longest drive challenge - with prizes
- Junior programs
    - How do we make it fun for kids?
    - Kids parties
    - high performance junior golfers.
- Corporate memberships
    - Platinum?: All inclusive: $25,000 per year
    - ____ - 4 hour slot per week on a Tuesday?
    - Employee and clients appreciation
    - Corporate recruiting events?
- Womens night, and specials (eg: 5i golf)
- NFL Sunday ticket (eg: 5i golf)
- Millitary discount
- Events page - Upcoming events (topgolf.com/events)
    - NFL Sunday ticket: Book 3 to 4 hours - charge an entry fees
    - Fund raising - First Tee
    - Line up Fund raising events
    - FCC events?
    - Team building
- Can we provide / maintain a USGA Handicap for players?
- Add to rates:  
- Pages should have an image on the first 3rd of the page OR a background image
  - Kids membership
  - Family membership
  - Birthday parties
  - Holiday celebrations?
  - Full facility buyout
  ? November offer? Free 30 minute swing analysis - introductory offer.
  ? Active Military discount 
- Lessons page
    - Why take lessons on trackman?
    - Need photo of Allen teaching a kid - lesson in action
    - Group lessons only on off-peak days
    - Need pics and bios of teaching instructors
    - Trackman makes coaching more fun and it enables us to get better results with students faster - quote from instructor
- Play/Learn
    - Spicing up the coaching sessions with supervised playing
- 404 must have a golf related image (see 404.html)
- Uncomment / Fix / Get testimonials on index.html
- All images must have an alt tag
- All pages must have tags, title, description - Define page.tags - see head.html for use / seo!
- Find/buy better stock photos
- Check XGolf Shelby and San Antonio location websites. 
- Fix desktop version
    - Phone number at top (for desktop version)
    - Top bar has a line through it!


## Getting Started

Install jekyll: https://jekyllrb.com/docs/installation/

```
gem install jekyll bundler

cd <WEBSITE>

bundle exec jekyll serve --host 0.0.0.0

# Install gems
bundle install

# Create a Gemfile
bundle init
# Add discovered dependencies
bundle add jekyll
bundle add jekyll-paginate
bundle add jekyll-compose
bundle install

# for the server to be available from outside:
bundle exec jekyll serve --host 0.0.0.0


# Probably not required!
# cannot load such file -- jekyll-paginate
gem install github-pages


```

## New Posts
New posts can be added by creating a new Markdown file (.md) inside the _posts directory. The file name should start with YYYY-MM-DD-post-name and have the .md extension in order to be recognized and for it to be live in the final website.

## Caching
There is caching applied on most of the static elements such as the logo, css and js files to increase the page access speed and lower overhead on the server (this also helps lower the total number of requests to the server by using locally cached files, read more [here](https://gtmetrix.com/leverage-browser-caching.html)).

