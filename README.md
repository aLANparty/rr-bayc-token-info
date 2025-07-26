# Token Metadata Info

## The Ryder Ripps Token: 1

Token 1 uses a custom uploaded ape image in a small jpeg format, named nft.jpg.  This is the only token using a jpg.

The metadata for this token is named metadata.json and is a single line of json.

examples

token 1: `ipfs://Qmb2Wj2QjzYu252aZwv4KyJM2WTLpwoASCTrEj1V2UN5Sb/metadata.json`

## The Hand Minted Tokens: 2 - 1299

Tokens 2 - 1299 (except 5 outliers) all use a manually uploaded bored ape image, named nft.png. While PNGs like the original BAYC images these images have different file sizes, names, and ipfs hashes. I believe the difference comes from Foundation's upload functionality used to create them.

The metadata for these tokens is named metadata.json and is a single line of json.

(A handful of tokens in this range do not follow this format. see: *Outlier Tokens: Various IDs under <1300* below)

examples

token 2: `ipfs://QmRRQqDCNYjukn4NunG8ZZDMBkab9gBR8ztgqfPJu4UfQa/metadata.json`

token 1299: `ipfs://QmZykdui2W2BsAPFJXahCJSnyuAiGnMPhrBnWwUYrA2No9/metadata.json`

## The Website Tokens: 1300 - 9546

Tokens starting at 1300 all use a single IPFS folder hash with numbered json files corresponding to a BAYC id.  The images in the json are all original BAYC ipfs hashes.

The metadata for these tokens is named metadata.json and is a multiline formatted json.

examples

token 1300: `ipfs://QmdXP2KNU2cuqcJBi6Uaf5bhnu2udmrbtJDfm3dMoewzNu/4589.json`

token 9546: `ipfs://QmdXP2KNU2cuqcJBi6Uaf5bhnu2udmrbtJDfm3dMoewzNu/8767.json`

## Outlier Tokens: 946, 947, 959, 972, 977

These tokens use the 1300 and above shared ipfs format despite being less than token id 1300.  They were not missed or minted out of order, but were actually minted in the excepted sequence, but with the later metadata format.  Working assumption is that these mints were tests for the website system, but I've no verification of that.

examples

token 946: `ipfs://QmdXP2KNU2cuqcJBi6Uaf5bhnu2udmrbtJDfm3dMoewzNu/99.json`

token 947: `ipfs://QmdXP2KNU2cuqcJBi6Uaf5bhnu2udmrbtJDfm3dMoewzNu/255.json`

token 959: `ipfs://QmdXP2KNU2cuqcJBi6Uaf5bhnu2udmrbtJDfm3dMoewzNu/88.json`

token 972: `ipfs://QmdXP2KNU2cuqcJBi6Uaf5bhnu2udmrbtJDfm3dMoewzNu/1549.json`

token 977: `ipfs://QmdXP2KNU2cuqcJBi6Uaf5bhnu2udmrbtJDfm3dMoewzNu/463.json`

## The Lost Token: 382

Token 382 was minted, but then burned immediately.  IPFS data is similar to other <1300 tokens, but can not be queried directly with `tokenURI` because of it's burned status.  It's hashes were retrieved by looking at the parameters passed in it's mint transaction.

token 382: `ipfs://QmcfkLubs9pi2VqNzJhkCp5cBNfGJf5RYCvUEcmmTABJ1W/metadata.json`

## Unminted Tokens: 9547 - 10000

These tokens do not exist.

