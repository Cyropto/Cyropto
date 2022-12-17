const char CRYPTONOTE_NAME[] = "furiouscoin";
set_property(TARGET daemon PROPERTY OUTPUT_NAME "furiouscoind")
const uint64_t MONEY_SUPPLY = (uint64_t)(150000000);
const unsigned EMISSION_SPEED_FACTOR = 18;
const uint64_t DIFFICULTY_TARGET = 120;
bool Currency::getBlockReward(size_t medianSize, size_t currentBlockSize, uint64_t alreadyGeneratedCoins, uint64_t fee, uint64_t& reward, int64_t& emissionChange) const
const int P2P_DEFAULT_PORT = 17236;
const int RPC_DEFAULT_PORT = 18236;
const static boost::uuids::uuid CRYPTONOTE_NETWORK = { { 0xA1, 0x1A, 0xA1, 0x1A, 0xA1, 0x0A, 0xA1, 0x0A, 0xA0, 0x1A, 0xA0, 0x1A, 0xA0, 0x1A, 0xA1, 0x1A } };
const std::initializer_list<const char*> SEED_NODES = {
  "111.11.11.11:17236",
  "222.22.22.22:17236",
};
const uint64_t MINIMUM_FEE = 100000;
const size_t CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE = 20000;
const uint64_t CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX = 0xe9; // addresses start with "f"
const char GENESIS_COINBASE_TX_HEX[] = "";
const char GENESIS_COINBASE_TX_HEX[] = "013c01ff0001ffff...785a33d9ebdba68b0";
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
