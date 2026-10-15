# CampusRide

A static student travel-pass website with route and pickup-time estimates, passenger details, demo OTP verification, payment-method selection, and a parent-contact SOS message flow.

## Deploy with Vercel

1. Import `TharunRepository/pdss` into Vercel.
2. Select the `main` branch and keep the project root as the root directory.
3. Choose the `Other` framework preset. Leave the build command empty; the site is served directly from the repository root.
4. Deploy. Vercel serves `index.html` as the home page and `checkout.html` as the checkout page.

No environment variables or build dependencies are required for the static demo.

## Important

Prices are sample estimates. OTP verification is simulated, payment is not processed, and SOS opens a message for the user to send. Live SMS, payment processing, and vehicle scheduling require secure backend integrations.