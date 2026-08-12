# Changelog

All notable changes to Fusion Electronics are documented here.


## [1] 2026-08-12 19:37:21
- feat: add product search debounce for better UX


## [2] 2026-08-12 19:37:24
- fix: resolve cart item quantity overflow on mobile


## [3] 2026-08-12 19:37:27
- docs: update API endpoint documentation for auth routes


## [4] 2026-08-12 19:37:31
- style: improve product card hover animation smoothness


## [5] 2026-08-12 19:37:34
- refactor: extract checkout validation into reusable utility


## [6] 2026-08-12 19:37:37
- perf: lazy load product images to reduce initial load time


## [7] 2026-08-12 19:37:41
- test: add unit tests for NavigationBar component


## [8] 2026-08-12 19:37:44
- feat: add 'Back to Top' scroll button on Shop page


## [9] 2026-08-12 19:37:47
- fix: correct shipping cost calculation on cart total


## [10] 2026-08-12 19:37:51
- docs: add JSDoc comments to apiClient service functions


## [11] 2026-08-12 19:37:55
- style: unify button border-radius across all pages


## [12] 2026-08-12 19:38:00
- refactor: separate product filter logic into custom hook


## [13] 2026-08-12 19:38:03
- fix: prevent duplicate cart additions on rapid clicks


## [14] 2026-08-12 19:38:06
- feat: display stock availability badge on product cards


## [15] 2026-08-12 19:38:09
- test: add integration tests for checkout order creation


## [16] 2026-08-12 19:38:13
- docs: add setup guide for Weaviate vector database


## [17] 2026-08-12 19:38:16
- perf: memoize ProductCard component to avoid re-renders


## [18] 2026-08-12 19:38:19
- style: add skeleton loading placeholders for product grid


## [19] 2026-08-12 19:38:22
- fix: correct JWT expiry handling in auth middleware


## [20] 2026-08-12 19:38:25
- feat: support product filtering by price range


## [21] 2026-08-12 19:38:29
- refactor: move Mongoose connection logic to dedicated module


## [22] 2026-08-12 19:38:32
- test: write tests for product search endpoint


## [23] 2026-08-12 19:38:35
- docs: expand README with Docker deployment instructions


## [24] 2026-08-12 19:38:38
- fix: handle Pinecone timeout gracefully with fallback


## [25] 2026-08-12 19:38:42
- style: improve mobile responsiveness of CheckoutForm


## [26] 2026-08-12 19:38:45
- feat: add recently viewed products section on Home page


## [27] 2026-08-12 19:38:48
- perf: index MongoDB category field for faster queries


## [28] 2026-08-12 19:38:51
- fix: correct email validation regex in checkout form


## [29] 2026-08-12 19:38:54
- docs: document environment variable configuration options


## [30] 2026-08-12 19:38:57
- test: add snapshot tests for Footer component


## [31] 2026-08-12 19:39:01
- refactor: simplify product recommendation ranking logic


## [32] 2026-08-12 19:39:04
- feat: add admin view to list all registered users


## [33] 2026-08-12 19:39:07
- style: add loading spinner to recommendation section


## [34] 2026-08-12 19:39:10
- fix: resolve CORS issue for production API deployment


## [35] 2026-08-12 19:39:13
- test: add tests for user registration and login flows


## [36] 2026-08-12 19:39:15
- docs: add contributing guide with PR and issue templates


## [37] 2026-08-12 19:39:18
- feat: implement 'Forgot Password' email reset flow


## [38] 2026-08-12 19:39:22
- perf: add Redis caching layer for frequently queried products


## [39] 2026-08-12 19:39:25
- fix: sanitize user input before storing in MongoDB


## [40] 2026-08-12 19:39:29
- style: update footer links color for better contrast


## [41] 2026-08-12 19:39:32
- refactor: break down large App.jsx into smaller sub-components


## [42] 2026-08-12 19:39:35
- test: add tests for product details page rendering


## [43] 2026-08-12 19:39:39
- docs: document Pinecone sync process in detail


## [44] 2026-08-12 19:39:42
- feat: add product category sidebar filter on Shop page


## [45] 2026-08-12 19:39:45
- fix: resolve flickering on page transition animations


## [46] 2026-08-12 19:39:49
- style: increase base font size for better readability


## [47] 2026-08-12 19:39:52
- perf: bundle splitting for faster frontend initial load


## [48] 2026-08-12 19:39:56
- test: add tests for cart context state management


## [49] 2026-08-12 19:39:59
- docs: add API rate limit documentation to Swagger


## [50] 2026-08-12 19:40:02
- fix: handle empty product list gracefully on Shop page


## [51] 2026-08-12 19:40:05
- feat: enable sorting products by price low to high


## [52] 2026-08-12 19:40:08
- refactor: consolidate all API error handling into Axios interceptors


## [53] 2026-08-12 19:40:15
- style: add dark overlay to hero banner for text readability


## [54] 2026-08-12 19:40:19
- test: add end-to-end test for full checkout flow


## [55] 2026-08-12 19:40:22
- docs: update CHANGELOG with recent feature additions


## [56] 2026-08-12 19:40:25
- fix: correct product image alt text for accessibility


## [57] 2026-08-12 19:40:29
- feat: add 'New Arrivals' section to the Home page


## [58] 2026-08-12 19:40:32
- perf: defer non-critical JavaScript loading


## [59] 2026-08-12 19:40:36
- style: polish mobile navigation drawer transitions


## [60] 2026-08-12 19:40:40
- test: add tests for order success confirmation page


## [61] 2026-08-12 19:40:44
- refactor: use environment variables for all hardcoded URLs


## [62] 2026-08-12 19:40:48
- docs: add system architecture diagram to README


## [63] 2026-08-12 19:40:54
- fix: resolve race condition in cart update handler


## [64] 2026-08-12 19:40:57
- feat: add wishlist functionality with local storage persistence


## [65] 2026-08-12 19:41:00
- style: apply consistent card shadow depth across all components


## [66] 2026-08-12 19:41:04
- test: add unit tests for product price formatting utility


## [67] 2026-08-12 19:41:07
- fix: ensure 404 page redirects to home after 5 seconds


## [68] 2026-08-12 19:41:10
- docs: add FAQ section to the support documentation


## [69] 2026-08-12 19:41:13
- perf: implement virtual scrolling for large product lists


## [70] 2026-08-12 19:41:17
- refactor: migrate legacy class components to functional hooks


## [71] 2026-08-12 19:41:20
- feat: add product share button with social media links


## [72] 2026-08-12 19:41:23
- test: add tests for search results filtering behavior


## [73] 2026-08-12 19:41:25
- style: improve color contrast ratio for WCAG AA compliance


## [74] 2026-08-12 19:41:28
- fix: prevent form resubmission on checkout page refresh


## [75] 2026-08-12 19:41:32
- docs: document Weaviate sync orchestration workflow


## [76] 2026-08-12 19:41:36
- feat: add coupon code discount field to checkout


## [77] 2026-08-12 19:41:40
- perf: compress product images on upload with Sharp


## [78] 2026-08-12 19:41:44
- test: add tests for forgot password reset email flow


## [79] 2026-08-12 19:41:47
- refactor: standardize HTTP response codes across all routes


## [80] 2026-08-12 19:41:51
- style: add tooltip to icon-only buttons for accessibility


## [81] 2026-08-12 19:41:54
- fix: handle network errors with user-friendly toast messages


## [82] 2026-08-12 19:41:57
- docs: expand deployment guide with Vercel configuration steps

