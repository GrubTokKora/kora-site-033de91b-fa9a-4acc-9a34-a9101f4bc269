# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: Earthworks Landscaping and Masonry LLC – Stonework & Gardens in Norwalk, CT
purpose: Home page introducing Earthworks Landscaping and Masonry services, pricing, process, and customer reviews in Norwalk and Fairfield County, CT.
sections:
- `#hero` — Hero introduction and call to action: Norwalk, Fairfield County
- `#pricing` — Pricing information for stone patios
- `#offerings` "Services" — List of core landscaping and masonry services: Patios & Walkways, Retaining & Sitting Walls, Outdoor Living, Planting & Garden Design, Drainage & Grading, Lawn & Maintenance, Landscape Lighting, Snow & Ice Management
- `#gallery` "Recent projects, photographed on site" — Photo gallery of completed landscaping and masonry projects
- `#process` "What happens after you call" — Step-by-step description of the project workflow: Site Walk, Design & Price, Build, Walkthrough
- `#story` — Company background and customer service commitments
- `#reviews` — Customer reviews and testimonials: Dee R, Melissa Robinson
- `#faq` "The four things people ask first" — Frequently asked questions and answers
- `#offers` "Two seasonal savings" — Promotional offers and discounts for new customers: Spring Cleanup Special, Leaf Cleanup Season
- `#service_area` "Based in Norwalk, working throughout Fairfield County" — Service areas and towns served: Westport, Wilton, Darien, New Canaan, Stamford, Fairfield, Weston, Greenwich
- `#hours_location` "Out at seven, and on call for storms" — Operating hours, emergency availability, and yard address
- `#contact` "Ready to Build Something That Lasts?" — Contact block and estimate call to action

## about.html → /about
title: About Earthworks | Norwalk CT Landscapers & Masons
purpose: Introduce the family-owned history, brothers, experience, and working principles of Earthworks Landscaping and Masonry LLC.
sections:
- `#story` — Company history, key facts, and operational principles: Norwalk, CT, Fairfield County, Earthworks Landscaping and Masonry LLC, Built Once, Built Right, One Crew, Start to Finish, Clean Site, Every Night, Honest Numbers, Licensed & Insured, Realistic Schedules, Local Norwalk Yard, We Answer Our Own Phone
- `#contact` — Call to action and contact block

## contact.html → /contact
title: Contact Earthworks | Free Estimate in Norwalk, CT
purpose: Provide a project estimation form, contact details, map, and frequently asked questions for Earthworks.
sections:
- `#contact` "Get Your Free Estimate" — contact form and business contact details: Patio or Walkway, Retaining Wall, Outdoor Kitchen / Fireplace, Planting & Garden Design, Drainage & Grading, Lawn Maintenance, Other, Facebook, Yelp
- `#faq` "Answers Before You Call" — frequently asked questions list: What areas do you serve around Norwalk, CT?, Are you licensed and insured?, How much does a stone patio cost?, Do you offer free estimates?, How long does a typical project take?, What’s the best season for masonry work in Connecticut?, Will my retaining wall need a permit?, Do you repair existing patios, walls and steps?, Can you fix a soggy yard or water in the basement?, Do you offer seasonal lawn maintenance contracts?, What kind of warranty do you provide?, How do payments and scheduling work?
- `#hours_location` "Out at seven, and on call for storms" — hours, address, and service area town list: Westport, Wilton, Darien, New Canaan, Stamford, Fairfield, Weston, Greenwich

## gallery.html → /gallery
title: Project Gallery | Earthworks Norwalk CT
purpose: Showcase recent landscaping and masonry projects built by the company in Fairfield County with town-by-town descriptions of the work.
sections:
- `#hero` — introductory text and service area list: Norwalk, Rowayton, Westport, Darien
- `#gallery` "Recent projects, photographed on site" — photo gallery grid
- `#projects` "What we built, town by town" — list of recent projects with locations and descriptions: Backyard Lawn Renovation, Front Entry Walkway, Failing Timber Wall Rebuild, Backyard Patio Build
- `#contact` — call to action for estimates
also: The page title and meta description appear identically in the HTML head and in the JSON-LD schema block.

## services.html → /services
title: Landscaping & Masonry Services | Earthworks Norwalk CT
purpose: List the landscaping and masonry services offered by Earthworks in Norwalk and Fairfield County.
sections:
- `#hero` "Everything Outside the Front Door" — Page hero introducing services in Norwalk and Fairfield County
- `#offerings` "Eight groups, thirty-two services" — Categorized catalog of landscaping and masonry services: Patios & Walkways, Bluestone terraces, Paver patios, Stone steps & landings, Pool surrounds, Retaining & Sitting Walls, Fieldstone walls, Veneer walls, Seat walls, Wall repair & rebuild, Outdoor Living, Outdoor kitchens, Fireplaces & chimneys, Fire pits, Grill islands, Planting & Garden Design, Foundation plantings, Privacy screening, Perennial gardens, Tree & shrub install, Drainage & Grading, French drains, Dry wells, Regrading, Downspout tie-ins, Lawn & Maintenance, Weekly mowing, Spring & fall cleanup, Mulching, Fertilization, Landscape Lighting, Path lighting, Uplighting, Wall washing, Timers & zones, Snow & Ice Management, Plowing, Shoveling & salting, Pre-treatment, Seasonal contracts
- `#process` "What happens after you call" — Project workflow steps and typical timelines: Site Walk, Design & Price, Build, Walkthrough
- `#contact` "Tell us about your yard" — Call-to-action block for estimate requests
also: The page description is mirrored between the meta description tag, the Open Graph description tag, the Twitter description tag, and the JSON-LD WebPage description.
also: The page title is mirrored between the title tag, the Open Graph title tag, the Twitter title tag, and the JSON-LD WebPage name.

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `llms.txt` — 189 bytes — too small to hold content
- `robots.txt` — 45 bytes — too small to hold content
- `sitemap.xml` — 160 bytes — too small to hold content

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
