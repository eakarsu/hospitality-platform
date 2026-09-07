# Feature status — Hotels, travel & recreation stays

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 249 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 2 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 5 | 0 | Native records/view |
| Activity & audit trail | audit | 4 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Franchise agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property room registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PMS revenue ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross room revenue definition | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Royalty calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketing assessment audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reservation fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loyalty program fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Technology system fees | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Opening renovation charges | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exclusion validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Brand invoice reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Brand dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property brand economics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account property mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Room block registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reservation ingestion | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Rate code validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stay-date eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Blackout date control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Last-room availability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Concession package audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Attrition calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cancellation fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commission treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Folio rate correction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account recovery workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property account analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OTA contract and rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property and channel registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PMS stay matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Room-rate parity validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commission base recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax and fee exclusion control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cancellation and no-show audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate commission detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Virtual card reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Merchant settlement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chargeback and refund control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OTA dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement recovery tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Channel profitability analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rooms | records | 1 | 0 | Native records/view |
| Channels | records | 1 | 0 | Native records/view |
| Guests | records | 2 | 0 | Native records/view |
| Housekeeping | records | 1 | 0 | Native records/view |
| Upsells | records | 1 | 0 | Native records/view |
| Reservations | records | 2 | 0 | Native records/view |
| Reviews | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Staff | records | 1 | 0 | Native records/view |
| Promotions | records | 1 | 0 | Native records/view |
| Competitors | records | 1 | 0 | Native records/view |
| Maintenance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue war room | records | 1 | 0 | Native records/view |
| History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Group booking | records | 1 | 0 | Native records/view |
| Guest ltv | records | 1 | 0 | Native records/view |
| Guest segmentation | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| agentic revenue manager continuously opt | records | 1 | 0 | Native records/view |
| guest lifecycle ai predicting ltv and | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dynamic packaging generating room spa di | records | 1 | 0 | Native records/view |
| occupancy smoothing recommending group e | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| reputation review response monitoring ot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| labor optimizer extending laboropsjs wit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dynamic pricing optimizer endpoint ru | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| demand forecaster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| guest segmentation ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| review sentiment analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| competitor rate ai recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| upsell recommendation engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| loyalty program management | records | 1 | 0 | Native records/view |
| real time websocket booking board | records | 1 | 0 | Native records/view |
| webhook surface for ota event | integration | 1 | 0 | Provider request records only |
| file upload for guest documents | records | 1 | 0 | Native records/view |
| multi property fleet management | records | 1 | 0 | Native records/view |
| Users | records | 1 | 0 | Native records/view |
| Slips | records | 1 | 0 | Native records/view |
| Tenants | records | 1 | 0 | Native records/view |
| Boats | records | 1 | 0 | Native records/view |
| Utility readings | records | 1 | 0 | Native records/view |
| Fuel sales | records | 1 | 0 | Native records/view |
| Launch schedule | records | 1 | 0 | Native records/view |
| Dry storage | records | 1 | 0 | Native records/view |
| Transient docking | records | 1 | 0 | Native records/view |
| Winter storage | records | 1 | 0 | Native records/view |
| Work orders | records | 1 | 0 | Native records/view |
| Haul outs | records | 1 | 0 | Native records/view |
| Pump out log | records | 1 | 0 | Native records/view |
| Environmental compliance | records | 1 | 0 | Native records/view |
| Weather data | records | 1 | 0 | Native records/view |
| Ship store sales | records | 1 | 0 | Native records/view |
| Waiting list | records | 1 | 0 | Native records/view |
| Hurricane prep | records | 1 | 0 | Native records/view |
| Parking permits | records | 1 | 0 | Native records/view |
| Amenity access | records | 1 | 0 | Native records/view |
| Financial records | records | 1 | 0 | Native records/view |
| Seasonal rates | records | 1 | 0 | Native records/view |
| Insurance requirements | records | 1 | 0 | Native records/view |
| Cancellation Risk / No-Show Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Upsell Recommendations | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Occupancy Forecast | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Staff Scheduling Optimization | records | 1 | 0 | Native records/view |
| Amenity Demand Prediction | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Review Response AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Online Booking Widget / Public API | records | 1 | 0 | Native records/view |
| Automated Guest Communications | records | 1 | 0 | Native records/view |
| Payment Processor Integration | integration | 1 | 0 | Provider request records only |
| Housekeeping / Maintenance Ticketing | records | 1 | 0 | Native records/view |
| Notifications / SMS System | records | 1 | 0 | Native records/view |
| PMS Integration | integration | 1 | 0 | Provider request records only |
| Reporting & Export | records | 1 | 0 | Native records/view |
| Sites | records | 1 | 0 | Native records/view |
| Checkinout | records | 1 | 0 | Native records/view |
| Utilities | records | 1 | 0 | Native records/view |
| Rates | records | 1 | 0 | Native records/view |
| Longterm | records | 1 | 0 | Native records/view |
| Amenities | records | 1 | 0 | Native records/view |
| Amenity bookings | records | 1 | 0 | Native records/view |
| Store | records | 1 | 0 | Native records/view |
| Transactions | records | 1 | 0 | Native records/view |
| Loyalty | records | 1 | 0 | Native records/view |
| Revenue | records | 1 | 0 | Native records/view |
| Security | records | 1 | 0 | Native records/view |
| Mail | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Propane | records | 1 | 0 | Native records/view |
| Firewood | records | 1 | 0 | Native records/view |
| Dump station | records | 1 | 0 | Native records/view |
| Dynamic pricing | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Review response | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Activity recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketing content | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cancellation risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staff scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dynamic pricing by occupancy demand season | records | 1 | 0 | Native records/view |
| guest lifetime value maximization | records | 1 | 0 | Native records/view |
| occupancy forecasting recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| maintenance routing optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| amenity demand forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| reviewresponsive marketing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| features | records | 1 | 0 | Native records/view |
| Lift Tickets | records | 1 | 0 | Native records/view |
| Season Passes | records | 1 | 0 | Native records/view |
| Lift Operations | records | 1 | 0 | Native records/view |
| Trail Management | records | 1 | 0 | Native records/view |
| Snowmaking | records | 1 | 0 | Native records/view |
| Snow Reports | records | 1 | 0 | Native records/view |
| Ski Patrol | records | 1 | 0 | Native records/view |
| Rental Shop | records | 1 | 0 | Native records/view |
| Ski School | records | 1 | 0 | Native records/view |
| Instructors | records | 1 | 0 | Native records/view |
| Childcare | records | 1 | 0 | Native records/view |
| Lost & Found | records | 1 | 0 | Native records/view |
| Guest Services | records | 1 | 0 | Native records/view |
| Accommodations | records | 3 | 0 | Native records/view |
| Shuttles | records | 1 | 0 | Native records/view |
| Parking | records | 1 | 0 | Native records/view |
| Food & Beverage | records | 1 | 0 | Native records/view |
| Retail | records | 1 | 0 | Native records/view |
| Equipment Maintenance | records | 2 | 0 | Native records/view |
| RFID Access | records | 1 | 0 | Native records/view |
| Weather Stations | records | 1 | 0 | Native records/view |
| Avalanche Control | records | 1 | 0 | Native records/view |
| Staffing | records | 1 | 0 | Native records/view |
| Terrain Park | records | 1 | 0 | Native records/view |
| Snow Conditions | records | 2 | 0 | Native records/view |
| Grooming Optimization | records | 2 | 0 | Native records/view |
| Guest Recommendations | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Staffing Prediction | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Avalanche Risk | records | 1 | 0 | Native records/view |
| Instructor Scheduling | records | 1 | 0 | Native records/view |
| Churn Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue Optimization | records | 1 | 0 | Native records/view |
| revenue per available seatday revpasday opti | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| snow conditions forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| demandbased staffing | records | 1 | 0 | Native records/view |
| guest experience personalization | records | 1 | 0 | Native records/view |
| maintenance predictive scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dynamic dining recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| occupancyforecast for resort busyness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| revenueoptimization bundle pricing | records | 1 | 0 | Native records/view |
| avalancheriskassessment ml | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| equipmentmaintenancescheduling ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| instructorscheduling demand matching | records | 1 | 0 | Native records/view |
| churnprediction returning guest likelihoo | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| realtime lift line wait estimation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| public online lesson booking widget | records | 1 | 0 | Native records/view |
| food ordering pos integration | integration | 1 | 0 | Provider request records only |
| limited weather api integration stations are | integration | 1 | 0 | Provider request records only |
| lift ticket pos integration | integration | 1 | 0 | Provider request records only |
| guest mobile app companion | records | 1 | 0 | Native records/view |
| notificationssms for guests | records | 1 | 0 | Native records/view |
| AI Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Flight Finder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hotel Matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weather Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget Tracker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Activity Finder | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Trip Inspiration | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Day-Of Mode | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Visa Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic Adjuster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trips | records | 2 | 0 | Native records/view |
| Destinations | records | 2 | 0 | Native records/view |
| Transportation | records | 2 | 0 | Native records/view |
| Restaurants | records | 2 | 0 | Native records/view |
| Budgets | records | 2 | 0 | Native records/view |
| Packing Lists | records | 2 | 0 | Native records/view |
| Travel Tips | records | 2 | 0 | Native records/view |
| Emergency | records | 2 | 0 | Native records/view |
| Photos | records | 2 | 0 | Native records/view |
| Document Vault | records | 1 | 0 | Native records/view |
| Collaboration | records | 1 | 0 | Native records/view |
| dynamic itinerary adjustment for real time delay handling | records | 1 | 0 | Native records/view |
| local currency spending tracker with multi currency conversion | records | 1 | 0 | Native records/view |
| travel community features share trips follow travelers | records | 1 | 0 | Native records/view |
| visa document advisor checking requirements by destination | records | 1 | 0 | Native records/view |
| travel insurance recommender assessing needs and plans | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| group trip cost splitter with splitwise style settlements | records | 1 | 0 | Native records/view |
| ai coverage is comprehensive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| vision based receipt expense capture | records | 1 | 0 | Native records/view |
| conversational travel agent voice interface | records | 1 | 0 | Native records/view |
| deep integration with booking platforms expedia booking | integration | 1 | 0 | Provider request records only |
| real time flight price alerts | records | 1 | 0 | Native records/view |
| travel insurance comparison shopping | records | 1 | 0 | Native records/view |
| visa requirement checker | records | 1 | 0 | Native records/view |
| multi currency tracking | records | 1 | 0 | Native records/view |
| webhooks for trip events | integration | 1 | 0 | Provider request records only |
| notifications subsystem | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 249 feature pages were visited in the browser; 247 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 105 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

105 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
