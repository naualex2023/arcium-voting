# TODO

- Get Docker https://docs.docker.com/desktop/setup/install/mac-install/
- Start Docker desktop (docker daemon not running)
- unset RUSTUP_TOOLCHAIN
- arcium build
- arcium test

```
arcium test
Checking if encrypted instructions are up to date.
Encrypted instructions are up to date. Skipping build.
warning: Patch `proc-macro2 v1.0.97 (https://github.com/arcium-hq/proc-macro2.git#b52c9661)` was not used in the crate graph.
Check that the patched package version and available features are compatible
with the dependency requirements. If the patch has a different version from
what is locked in the Cargo.lock file, run `cargo update` to use the new
version. This may also occur with an optional dependency that is not enabled.
Error: Function _ZN109_$LT$arcium_client..idl..arcium..utils..Account$u20$as$u20$core..convert..TryFrom$LT$$RF$$u5b$u8$u5d$$GT$$GT$8try_from17hcd1e61a65fb2633fE Stack offset of 721512 exceeded max offset of 4096 by 717416 bytes, please minimize large stack variables. Estimated function frame size: 721536 bytes. Exceeding the maximum stack offset may cause undefined behavior during execution.

   Compiling voting v0.1.0 (/Users/mikemaccana/Code/arcium-voting/programs/voting)
    Finished `release` profile [optimized] target(s) in 1.76s
warning: Patch `proc-macro2 v1.0.97 (https://github.com/arcium-hq/proc-macro2.git#b52c9661)` was not used in the crate graph.
Check that the patched package version and available features are compatible
with the dependency requirements. If the patch has a different version from
what is locked in the Cargo.lock file, run `cargo update` to use the new
version. This may also occur with an optional dependency that is not enabled.
   Compiling voting v0.1.0 (/Users/mikemaccana/Code/arcium-voting/programs/voting)
    Finished `test` profile [unoptimized + debuginfo] target(s) in 0.94s
     Running unittests src/lib.rs (/Users/mikemaccana/Code/arcium-voting/target/debug/deps/voting-305195452a852ab6)
Removed artifacts/arx_ata_C4nh_hWb5.json
Removed artifacts/wallet_acc_B6Kq_MP8U.json
Removed artifacts/arx_ata_GUkV_CTWr.json
Removed artifacts/wallet_acc_GUkV_CTWr.json
Removed artifacts/arx_ata_B6Kq_MP8U.json
Removed artifacts/wallet_acc_C4nh_hWb5.json
Removed artifacts/arcium_clock.json
Removed artifacts/vote_raw_circuit_0.json
Removed artifacts/arcium_fee_pool.json
Removed artifacts/mxe_keygen_comp.json
Removed artifacts/executing_pool_acc.json
Removed artifacts/cluster_acc_0.json
Removed artifacts/init_vote_stats_raw_circuit_0.json
Removed artifacts/wallet_acc_callback_9nfL_Ayf4.json
Removed artifacts/wallet_acc_callback_F5Ls_Agh5.json
Removed artifacts/arx_node_GUkV_CTWr.json
Removed artifacts/arx_node_C4nh_hWb5.json
Removed artifacts/operator_acc_C4nh_hWb5.json
Removed artifacts/operator_acc_GUkV_CTWr.json
Removed artifacts/arx_mint.json
Removed artifacts/mempool_acc.json
Removed artifacts/reveal_result_raw_circuit_0.json
Removed artifacts/mxe_acc.json
Removed artifacts/mxe_keygen_comp_def.json
Clean completed successfully!
Generating accounts with owner pubkey: B6Kqrc3VPSKfhqKNq8xdB7YKqYUtNbAKdePHYV7tMP8U
Creating genesis accounts...
Starting anchor localnet...
Waiting for solana localnet to come online at http://127.0.0.1:8899...
Solana localnet is online ✔️
Starting Arcium node(s)...
Waiting for the arcium nodes to come online...
Arcium nodes are online ✔️
Solana localnet & Arx nodes are online! 🎉

Found a 'test' script in the Anchor.toml. Running it as a test suite!

Running test suite: "/Users/mikemaccana/Code/arcium-voting/Anchor.toml"

yarn run v1.22.22
$ /Users/mikemaccana/Code/arcium-voting/node_modules/.bin/ts-mocha -p ./tsconfig.json -t 2000000 'tests/**/*.ts'
(node:13120) [MODULE_TYPELESS_PACKAGE_JSON] Warning: Module type of file:///Users/mikemaccana/Code/arcium-voting/tests/voting.ts is not specified and it doesn't parse as CommonJS.
Reparsing as ES module because module syntax was detected. This incurs a performance overhead.
To eliminate this warning, add "type": "module" to /Users/mikemaccana/Code/arcium-voting/package.json.
(Use `node --trace-warnings ...` to show where the warning was created)


  Voting
MXE x25519 pubkey is Uint8Array(32) [
   79,  66,  79, 194, 161, 135, 205, 192,
  196,  60, 226,  97,  87, 191, 114, 132,
  197, 251, 251, 231,   5, 222, 246, 237,
  109, 212,  59, 148,  12, 185, 121,  11
]
Initializing vote stats computation definition
Init vote stats computation definition pda is  FLpEeHKkzCKwVvC7LMV3GBSLAsmhWSvEx2z4PYKWZk6U
Init vote stats computation definition transaction 3URG4XirGsBMd4p32xr48M8WpYbfpRuWw5td4xYADbegzrMkjEPAovBPWwHcQwD3wDCBe9pfyAVn8Vt3VjobvV2p
Vote stats computation definition initialized with signature 3URG4XirGsBMd4p32xr48M8WpYbfpRuWw5td4xYADbegzrMkjEPAovBPWwHcQwD3wDCBe9pfyAVn8Vt3VjobvV2p
Initializing voting computation definition
Vote computation definition pda is  56C5qv1MZEVhURaEpTcx1bMaC96jF1VLRAHSevR5ugTh
Init vote computation definition transaction P5LKNATYne8wQCwicjjJhAdPrGFo1Nnaz2xDBwUnKLaZa6U5NjEoeqByjbzaaZmJngmZbQYUbRyA4ysnLUhAMYq
Vote computation definition initialized with signature P5LKNATYne8wQCwicjjJhAdPrGFo1Nnaz2xDBwUnKLaZa6U5NjEoeqByjbzaaZmJngmZbQYUbRyA4ysnLUhAMYq
Initializing reveal result computation definition
Reveal result computation definition pda is  22cm6pHNoWnK6aRJx4DFQdf246fwHTXJDnvb7MD7pwgG
Init reveal result computation definition transaction hjcneGoPj4dXdJsW2Uh54chWuvtX7uPiKVWnaUDsGpFrccdD1kehthFBi1GFdakYRfQRCRXoYsAjJT7SeFdFG9d
Reveal result computation definition initialized with signature hjcneGoPj4dXdJsW2Uh54chWuvtX7uPiKVWnaUDsGpFrccdD1kehthFBi1GFdakYRfQRCRXoYsAjJT7SeFdFG9d
Poll 420 created with signature GYhub55EAFjEJCUiMzmLt3FVVxsV8defxSiB2F6uUVjBh2Mj8ckQEkpzDVC873DWn4M5h5BcKKzciLcqcLHBxqx
Finalize poll 420 sig is  34E7B5ofy14HndNXvfptVTtRTjrQgCUdfxL2eievsqHzm8WUH1D5h1i4dhC67z9RgV5bsVdY6rw6kAc1NvnruTQa
Poll 421 created with signature 67DYiADUCbsM3gKscfobY7rr8Cyhf5ytBWGBcoUzn1AQyaZrTHP4sBzidfYcJ48UY8kwTTiZnfRzUkpekuxG4i9q
Finalize poll 421 sig is  4c65kGzwvdid4fojC1zqbffdAVYdaZJXwBW162Wxoy1Aj39rZVQvNb7hECZNivLe9eAm7bgoD1aQ9AhJ8u9rbZ3x
Poll 422 created with signature t6QtiosstKTy9Xb7ci3955CrSwYZT9eAP9tMwhHPwMqLp4cnDHZuchPoNmLGGy8HT7LHeQDX3zrqA26zM7b14UU
Finalize poll 422 sig is  27i5Qoe5vtecMMwhJ9R1V7LTM2cfviihmrGeuoBUDrc2ysz4fJUDRmJAcnL1eNpFSigV3iebcVmTUxWKH3nwUqET
Voting for poll 420
Queue vote for poll 420 sig is  2cECRBkZUsUBRTVnGuLXQbafxxgCXQYfw86SujJVxfWnFEW96961ibeV4adiF9ojHD8E1c7RAiRnbR8NMckFs79H
Finalize vote for poll 420 sig is  3cMmFcbJKMn1ZSzCR3EiKC2sEfkRMLp9gCW2guBanhZsfWRARVgQsozcNjq1cBanYtsyG96QQ4RdV9TFUw7TpoDR
Vote casted for poll 420 at timestamp  1759944655
Voting for poll 421
Queue vote for poll 421 sig is  Ypaygz768kHA23t3MRmSNsyR2fsj97QHxVnq91mvvyyhZoecVG3V1TaAgVxs7pK3rZBW49Zvd8CqujvpkCYCyiR
Finalize vote for poll 421 sig is  bJVzw4nmRYQ9BM6eW7ecaHRtYGJthpN5VQa3b67D7UjCC6zQ5rKfWJqLdSk5YR1WrvxfyKjRdpDQnmPyAWddnLm
Vote casted for poll 421 at timestamp  1759944656
Voting for poll 422
Queue vote for poll 422 sig is  5viJRXYeaL9HGhotY5WZa57aKvxmWnqW8GWuJCDzrGDr8y1pSvQWXU4HLVLjc8V5T2L6dRPXEAvvRpCMgPbUFQS1
Finalize vote for poll 422 sig is  qzGxm7NmSzRjwzbBgeYRYzHupm5UFSW1wxJjrFXepdL4pHbjZyu1PJgRdWejYDaSUEWrDouiLxsX82dzcekAAdf
Vote casted for poll 422 at timestamp  1759944657
Reveal queue for poll 420 sig is  rNa4j6GABA2SbANSVJfdTjuGUzuwmuaT97HoaJcax2biGtZXUMRrrAUmcUPeE3izy9B1UWFVGeJPpszGHFVJ12j
Reveal finalize for poll 420 sig is  2qR5CKPVmBnwz6LoM6EDwXY2zvSPsyMCtAeMjyx3TCpMmujgvZZ4wXj5QZTariUjC4JWTFZmdbDREq3Y7moxEi5f
Decrypted winner for poll 420 is  true
Reveal queue for poll 421 sig is  3NJ468bvhExeUayjqSfdeebKZjDL86esPFvAy6ZuKtWhjnqCmQdb3tcYYuCgp5sCBpYBEgnrKeZQVtfhPp44qa5d
Reveal finalize for poll 421 sig is  2EvhuMhdJnt1yHBBwcsHaUHFE6Zgsd6KKzopqjKFtWG3uujTGjP4x16zJGYZmiwSca8A4j77tLQZDq2kUBqgi3T5
Decrypted winner for poll 421 is  false
Reveal queue for poll 422 sig is  5nV9cZ3NayNtcQ1rxkooLTL3YE7468zcLqw2dZcQnJGPzztgB9zj8DspoKxDckoFax5PbuxhZo2AuPwCuRfhQ21E
Reveal finalize for poll 422 sig is  3SG4hDrLgVND3pF8vHh4EPrmMfr8Cc6Vz6sMAQoeK1T3fXCAs1tabeoctEhTqh9CoXUqt2D3dXgjLkXXvjUUboar
Decrypted winner for poll 422 is  true
    ✔ can vote on polls! (11609ms)


  1 passing (12s)
```

# Anonymous Voting with Arcium

This project demonstrates how to implement truly anonymous voting on Solana using Arcium's confidential computing capabilities. It showcases how to create private polls where individual votes remain confidential while still allowing for verifiable results.

## Why Arcium is Necessary for Anonymous Voting

Traditional blockchains are transparent by design, making it impossible to implement truly anonymous voting without additional privacy layers. Here's why Arcium is essential:

- **Public Nature of Blockchains**: All data on a regular blockchain is visible to everyone
- **Privacy Requirements**: Votes must remain confidential to ensure anonymity
- **Security Concerns**: Even encrypted votes would require decryption keys, creating vulnerabilities
- **Distributed Trust**: Arcium uses Multi-Party Computation (MPC) to achieve a trust-minimized setup for confidential computing

## How It Works

### 1. Poll Creation

```typescript
const pollSig = await program.methods.createNewPoll(
  POLL_ID,
  `Poll ${POLL_ID}: $SOL to 500?`,
  new anchor.BN(deserializeLE(pollNonce).toString())
);
```

- Creates a new poll with a unique ID and title
- Uses a cryptographic nonce for security operations
- Establishes the voting context on-chain

### 2. Voting Process

```typescript
const vote = BigInt(true);
const plaintext = [vote];
const nonce = randomBytes(16);
const ciphertext = cipher.encrypt(plaintext, nonce);
```

- Votes are encrypted using x25519 (key exchange) and RescueCipher
- Each vote uses a unique nonce for security
- Votes remain confidential even when stored on-chain

### 3. Confidential Computation

```typescript
const queueVoteSig = await program.methods.vote(
  POLL_ID,
  Array.from(ciphertext[0]),
  Array.from(publicKey),
  new anchor.BN(deserializeLE(nonce).toString())
);
```

- Encrypted votes are processed using MPC across multiple parties
- Computation is distributed across the Arcium network
- Individual vote values remain confidential throughout the computation

### 4. Result Revealed

```typescript
const revealQueueSig = await program.methods.revealResult(POLL_ID);
```

- Only the final result (e.g., majority vote) is revealed
- Individual votes remain confidential
- Results are computed through MPC and only the outcome is published
