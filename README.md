1 // Set your keys
2 const DAPP_ID = "65f95e4c-8b0a-42b2-a017-da3c49c2e4b4";
3 const API_KEY = "3cb4f2ff-0c8e-47fa-ac83-1dd165cfebaa";
4
5 // Initialize SDK
6 const handler = await bunzz.initializeHandler({
7 dappId: DAPP_ID,
8 apiKey: API_KEY,
9 });
10 const contract = await handler.getContract("Token (ERC20)");
