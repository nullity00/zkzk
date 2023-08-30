# Outline of ZK Topics I'd love to learn

## Basics

### 1. Algorithms

- [MIT 6.046J Design and Analysis of Algorithms, Spring 2015](https://youtube.com/playlist?list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp) 
- [Computational Complexity Lectures](https://youtube.com/playlist?list=PLdUzuimxVcC0DENcdT8mfhI3iRRJLVjqH)

### 2. ZK Languages
- [circom](https://github.com/iden3/circom)
- [zokrates](https://zokrates.github.io/)
- [lurk](https://github.com/lurk-lab/lurk-rs)
- [leo](https://leo-lang.org/)
- [cairo](https://www.cairo-lang.org/)
- [noir](https://noir-lang.org/)

### 3. Maths
- [PBC Math](https://crypto.stanford.edu/pbc/notes/)
- [Introduction to Mathematical Cryptography](https://github.com/isislovecruft/library--/blob/master/cryptography%20%26%20mathematics/An%20Introduction%20to%20Mathematical%20Cryptography%20(2014)%20-%20Hoffstein%2C%20Pipher%2C%20Silverman.pdf)
- [Modern Computer Algebra](https://maths-people.anu.edu.au/~brent/pd/mca-cup-0.5.9.pdf)
- [Explicit-Formulas Database](http://hyperelliptic.org/EFD/)
- [Abstract Algebra](http://abstract.ups.edu/download/aata-20220728.pdf)
- [Algebraic Number Theory](https://kashanu.ac.ir/Files/Content/ANT.pdf)
- [Computational Introduction to Number Theory and Algebra](https://shoup.net/ntb/ntb-v2.pdf)
- [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_4.pdf)
- [Lattice Cryptography](https://eprint.iacr.org/2015/939.pdf)

### 4. Cryptography
- [Crypto101](https://www.crypto101.io/)
- [Real World Cryptography - David Wong](https://www.manning.com/books/real-world-cryptography)
- [Uncloak - Cryptography in Rust](https://uncloak.org/courses/rust+cryptography+engineering/course-Rust+Cryptography+Engineering+Study+Group+Syllabus)
- [The Arithmetic of Elliptic Curves](https://www.pdmi.ras.ru/~lowdimma/BSD/Silverman-Arithmetic_of_EC.pdf)
- [Elliptic Curves Number Theory And Cryptography](https://people.cs.nctu.edu.tw/~rjchen/ECC2012S/Elliptic%20Curves%20Number%20Theory%20And%20Cryptography%202n.pdf)
- [Pairings for Beginners](https://static1.squarespace.com/static/5fdbb09f31d71c1227082339/t/5ff394720493bd28278889c6/1609798774687/PairingsForBeginners.pdf)

## NIZK

### 1. Proofs
- [Proofs, Arguments, and Zero-Knowledge](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf)
- [The MoonMath Manual to zk-SNARKs](https://leastauthority.com/community-matters/moonmath-manual/)
- [Validity Proofs vs. Fraud Proofs](https://starkware.medium.com/validity-proofs-vs-fraud-proofs-4ef8b4d3d87a)

### 2. STARKs
- [Part I: STARK Overview](https://aszepieniec.github.io/stark-anatomy/overview)
- [Part II: Basic Tools](https://aszepieniec.github.io/stark-anatomy/basic-tools)
- [Part II: FRI](https://aszepieniec.github.io/stark-anatomy/fri)
- [Part IV: The STARK Polynomial IOP](https://aszepieniec.github.io/stark-anatomy/stark)
- [Part V: A Rescue-Prime STARK](https://aszepieniec.github.io/stark-anatomy/rescue-prime)
- [Part VI: Speeding Things Up](https://aszepieniec.github.io/stark-anatomy/faster)
- [Brainfuck STARK Tutorial](https://neptune.cash/learn/brainfuck-tutorial/)

### 3. SNARKS
- [Nova: Recursive SNARKs without trusted setup](https://github.com/microsoft/Nova)
- 

### 4. IOPs
-

### 5. PCS
- [Rust Lib for PCS](https://github.com/arkworks-rs/poly-commit)
- [Benchmarks](https://github.com/recmo/pc-bench)
- [KZG Rust](https://github.com/adria0/a0kzg)
- [KZG Go](https://github.com/arnaucube/kzg-commitments-study)
- [FRI Commitments](https://github.com/arnaucube/fri-commitment)
- [IPA](https://github.com/coinstudent2048/verklebp)
- 

### 6. Bulletproofs
- [BulletProofs](https://github.com/dalek-cryptography/bulletproofs)

### 7. MPC
- [Awesome MPC](https://github.com/rdragos/awesome-mpc)
- [Zcash's MPC](https://github.com/zcash/mpc)
- [Swanky: A suite of rust libraries for secure multi-party computation](https://github.com/GaloisInc/swanky)
- [PSE's MPZ](https://github.com/privacy-scaling-explorations/mpz)
- [Multi-party computation for Zcash's "Sapling" zk-SNARK public parameters](https://github.com/zcash-hackworks/sapling-mpc)
- 


## Libraries

### 1. Groth16

### 2. PLONK

#### Implementations

- [Plonk: A pure Rust PLONK implementation](https://github.com/ZK-Garage/plonk)
- [Jellyfish: A Rust Implementation of the PLONK ZKP System and Extensions](https://github.com/EspressoSystems/jellyfish)
- [Plonk : Dust Network](https://github.com/dusk-network/plonk)

#### Halo2 

- Vanilla [Halo2](https://github.com/zcash/halo2) by Zcash
- Axiom's [Halo2](https://github.com/axiom-crypto/halo2-lib)
- Axiom's Open Source V1 Projects
  - [ZK circuits for verification of Poseidon2 hashes and AES-ECB encryption](https://twitter.com/axiom_xyz/status/1681333006492143620) 
  - [ZK circuits for multi-opens for KZG commitments on BN254](https://twitter.com/axiom_xyz/status/1684684468878258178)
  - [ZK circuits for verifying ed25519 signatures](https://twitter.com/axiom_xyz/status/1680970752202543106)
  - [ZK circuit for fixed point arithmetic in Halo2, which is important for any ML or numerical algorithm](https://twitter.com/axiom_xyz/status/1679883582960193542)
  - [ZK circuits for BLS signature verification in BN254](https://github.com/axiom-crypto/halo2-lib/pull/89)
- [More Halo2 Projects](https://github.com/stars/nullity00/lists/halo2)

#### Plonky2

- [Plonky2 BN254 Pairing](https://github.com/qope/plonky2-bn254-pairing)
- Succint Lab's [Gnark Plonky2 Verifier](https://github.com/succinctlabs/gnark-plonky2-verifier)
- [Plonky3](https://github.com/Plonky3/Plonky3)
- [Plonky](https://github.com/mir-protocol/plonky)
- [Plonky2 Projects](https://github.com/stars/nullity00/lists/plonky2)

#### Other

- [plonkit: zkSNARK toolkit to work with circom DSL in PLONK proof system](https://github.com/fluidex/plonkit)

### 3. Formal Verification, Static Analysis

- [Ecne: an engine for verifying the soundness of R1CS constraints](https://github.com/franklynwang/EcneProject)
- [Picus: Symbolic Virtual Machine for Automated R1CS Verification](https://github.com/Veridise/Picus)
- [Papyrus: A Symbolic Execution Tool for Cairo](https://github.com/Veridise/Papyrus)






