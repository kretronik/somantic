# Somantic change notes through pull request titles

## v1.1.0 - Improvement updates
- Add below market value and fix API
- Enable cashflow parameter user change and add marker clusters on map
- Add ohne-makler crawler
- Update immowelt and immonet parser
- Fix immowelt multipolygon geo calculation
- Immoscout optimization
- Fix remote run
- Fix immoscout active updater

## v1.0.0 - Production Release (30th June 2024)
- Update bundesland
- Increase sleep osm query
- OSM infinite loop fix
- Redesign somantic
- Add sidebar menu
- Filter through URL
- Deployment changes
- Update constant
- Fix typo
- Split/immo/scraping
- Fix parser
- Active crawler
- Fix display
- Fix active filter
- Add default display
- Hotfix null formatter crash
- Add intial template kleinanzeigen
- Deactivate only active everything else
- Extend scripts
- Feature/save history change
- Price change filter graphql and url
- Fix parameter type
- Price change date fix
- UI/price change indicator
- Remove _id
- Update cookies
- Hotfix cookie
- Session fix
- Spider/immoscout24
- Reload cookies in loop
- Add immolocation spider
- Update descriptions
- Year of construction conversion
- Add metadata to parsers
- Overwrite uptime
- Make filters pretty
- Authenticated access flask app
- Use only localhost db
- Add scrapeops monitoring
- Remote database configuration
- Telegram bot implementation
- Fix dependencies
- Fix message
- Hotfix/increase timeout user query
- Add price and rent model MongoDB and Cluster Map Display OpenStreetMap
- Remove unused imports
- Update train script
- Fix update model query
- Enable filter price_below_market_value and cashflow calculation filter
- Fix filter_digit
- Fix detail page display
- Remove upsert
- Add cashflow subscription
- Model validation
- Added legend and market value percentage
- Verify email address
- Update training script
- Enable email notification
- Authenticate graphql endpoint
- Improv/UI mobile
- Fix sorting
- Update geocoding script
- Add captcha registration
- Multi model support
- Price estimation
- Fix validation
- Bookmark properties

## v0.0.3 - Minimal Viable Product Alpha Release (25th August 2022)
- Change marker to scatter plot
- Added demo gif
- Update node click behavior
- Fix map change with multi selection
- Enable map filter
- Added bundesland filter
- Split bmu calc in seperate sidebar
- Update training with bundeslaender
- Enable node selection for bundesland
- Adjust cookie session

## v0.0.2 - Minimal Viable Product Alpha Release (18th June 2022)
- Expose to internet
- Refresh google refresh token
- Added gunicorn standalone app
- Added gunicorn dependency
- Add connect false mongodb
- Add debug to constants
- Added google analytics
- Update the version number
- Update the energy consumption parsing
- Added authorization graphql for users
- Limit the graphql query output size
- Simplify query limit assignment

## v0.0.1 - Minimal Viable Product Alpha Release (11th June 2022)
- Created Monorepo with bazel
- Created landing page
- Implemented login system with password reset functionality
- Implemented immowelt parser
- Display DataTable from MongoDB
- Enable GraphQL API via python graphene library
- Enable filtering of the DataTable based on the SOM selection
- Display price and rent_price without training
- Enable search by sha in map
- Fixed email sending
- Fixed price/rent map display
- Enable filtering for training
- Added more maps to analyze real estate
- Update zip code
- Calculate mean NA node
- Fix the age processing
