This is meant for custom Shopify apps that just need to get a access token, without creating entire backend.

Usage:

1. Note Client ID & Client Secret of the app
2. Set App URL to: https://kvmsc.github.io/shop-custom-app-auth/?client_id={client_id}
3. Add Allowed redirection URL(s): https://kvmsc.github.io/shop-custom-app-auth/
4. Open or Install the app
5. Open browser console and click redirect link
6. Open browser console and copy cURL request to grab access token
7. In the cURL request body, set Client Secret to your app secret
