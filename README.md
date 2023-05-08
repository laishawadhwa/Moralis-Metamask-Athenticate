
# Moralis NextJS Auth 

Create a Moralis account.
Install moralis and @moralisweb3/next (if not installed) and next-authdependencies:
npm install moralis @moralisweb3/next next-auth

To implement authentication using a Web3 wallet (e.g., MetaMask), we need to use a Web3 library. For the tutorial, we will use wagmi. So, install the wagmi dependency:
npm install wagmi ethers@^5

Add new environment variables in your .env.local file in the app root:

    APP_DOMAIN: RFC 4501 DNS authority that is requesting the signing.
    MORALIS_API_KEY: You can get it on [moralis.io]
    NEXTAUTH_URL: Your app address. In the development stage, use http://localhost:3000.
    NEXTAUTH_SECRET: Used for encrypting JWT tokens of users. You can put any value here or generate it on https://generate-secret.now.sh/32. 