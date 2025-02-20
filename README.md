git clone https://github.com/monad-developers/foundry-monad


orge verify-contract \
0xbb98Ea4d647EB30d249A51e427FaD0169b2F9c2f
  src/Counter.sol:Counter \
  --verify \
  --verifier sourcify \
  --verifier-url https://sourcify-api-monad.blockvision.org
