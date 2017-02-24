# Blockchain Enabled Individual Identity Control Prototype

For Individual Identity, Personal Data and Electronic Contracts Project

## Use Bitcoin Keys for Signing App

For this project, following these steps:

* Install blockstack CLI

* If you have one name import it or if not ,then reserve a name (little bit of  bitcoin needed)

* Then once you have a name...

* Activate "advance mode" (look up help or such to see how to get advance mode)

* Then do blockstack wallet commend

From that output, you will get a structured blob with keys, and look for: data_privkey and data_pubkey because these are the secp256k1 keys and should be ECDSA API ready

## Relevant Links: 

* [Attestation](https://github.com/decentralized-identity/attestations/tree/master/implementations/azure)

* [Onename](https://onename.com/settings)

* [Blockstack - Docs](https://blockstack.org/docs)

* [Name Operations in Block #414646 | Blockstack Explorer](https://explorer.blockstack.org/nameops/414646)

* [gist:10cba763d1d5a0908ab5424a99fa9591](https://gist.github.com/jwalsh/10cba763d1d5a0908ab5424a99fa9591)

* [Bitcoin Address 34uRczW... | Bitcoin Block Explorer](https://blockexplorer.com/address/34uRczWSFuVUESrBk3q1PdV8LePKCZp9An)

* [Bitcoins the hard way: Using the raw Bitcoin protocol](http://www.righto.com/2014/02/bitcoins-hard-way-using-raw-bitcoin.html)

* [CIVICS/openpgpjs-secp256k1: Working repo for building secp256k1 capability into OpenPGPjs](https://github.com/CIVICS/openpgpjs-secp256k1)

* [CIVICS/openpgpjs-secp256k1: Working repo for building secp256k1 capability into OpenPGPjs](https://github.com/CIVICS/openpgpjs-secp256k1#encrypt-and-decrypt-string-data-with-pgp-keys)

* [ThePiachu/Golang-Koblitz-elliptic-curve-DSA-library: A library for ECDSA using Koblitz curves, such as secp256k1](https://github.com/ThePiachu/Golang-Koblitz-elliptic-curve-DSA-library)

* [therocktrading/bitjwt: JWT protocol implementation using Bitcoin secp256k1](https://github.com/therocktrading/bitjwt)

* [paulminer/secp256k1-build: Build of the secp256k1 library for Windows 64-bit](https://github.com/paulminer/secp256k1-build)

* [ethers/secp256k1-browserify: secp256k1-node compatability for browserify](https://github.com/ethers/secp256k1-browserify)

* [cryptape/ruby-bitcoin-secp256k1: Ruby binding to bitcoin's secp256k1 implementation.](https://github.com/cryptape/ruby-bitcoin-secp256k1)

* [tradle/nkey-secp256k1: nkey secp256k1 key implementation](https://github.com/tradle/nkey-secp256k1)

* [ikonovalov/file-force: Decentralized anonymous encrypted object/file sharing tools](https://github.com/ikonovalov/file-force)

* [GemHQ/secp256k1-rb: A Ruby gem wrapper for libsecp256k1](https://github.com/GemHQ/secp256k1-rb)

* [blockstack/elliptic-curve-js: Library for operations on secp256k1 keys.](https://github.com/blockstack/elliptic-curve-js)

* [czepluch/pysecp256k1: cffi wrapper for secp256k1](https://github.com/czepluch/pysecp256k1)

* [haskoin/secp256k1-haskell: Haskell bindings for secp256k1 library](https://github.com/haskoin/secp256k1-haskell)

* [BWallet/secp256k1: Optimized C library for EC operations on curve secp256k1](https://github.com/BWallet/secp256k1)

* [steveklabnik/bitcoin-secp256k1-rs: Rust language bindings for Bitcoin secp256k1 library.](https://github.com/steveklabnik/bitcoin-secp256k1-rs)

* [Bitcoin address / key functions](https://gist.github.com/shirriff/8e6b5650361bbe78a055)

## Adjacent Challenge: Remote Electronic Notarization

### Hypothesis

This [git+blockchain notarization design pattern] provides equivalent (or better) documentation (or record? or evidence?) of notarial acts as would be expected from a notarial journal?

### The Uniform Law:

* http://www.npa-section.com/images/RULONA_FINAL_10.pdf

### The Oregon Enactment:

https://www.oregonlegislature.gov/bills_laws/ors/ors194.html

Note: In section 194.300(3)(b) "(b) A description of the record, if any, and type of notarial act" is covered by the title and date of the document (eg: grant deed executed 2015).

  194.300 Journal. (1) Except as provided in subsection (11) of this section, a notary public shall maintain one or more journals in which the notary public chronicles all notarial acts that the notary public performs. The notary public shall retain the journal for 10 years after the performance of the last notarial act chronicled in the journal.
      (2) A journal may be created on a tangible medium or in an electronic format to chronicle all notarial acts, regardless of whether those notarial acts are performed for tangible or electronic records. If the journal is maintained on a tangible medium, it must be a permanent, bound register with numbered pages. If the journal is maintained in an electronic format, it must be in a permanent, tamper-evident electronic format complying with the rules of the Secretary of State.
      (3) An entry in a journal must be made contemporaneously with performance of each notarial act and must contain the following information:
      (a) The date and time of the notarial act;
      (b) A description of the record, if any, and type of notarial act;
      (c) The full name and contact address of each individual for whom the notarial act is performed;
      (d) If identity of the individual is based on personal knowledge, a statement to that effect;
      (e) If identity of the individual is based on satisfactory evidence, a brief description of the method of identification and the identification credential presented, if any, including the date of expiration of any identification credential;
      (f) The signature of each individual for whom the notarial act is performed; and
      (g) The fee, if any, charged by the notary public.
      (4)(a) If a notary public performs notarial acts involving duplicate originals of a single statement or document for the same individual on the same date, the notary public may, in lieu of recording individually in the journal the information required by subsection (3) of this section for each duplicate original, record a single entry in the journal for all notarial acts involving the statement or document. The entry shall set forth all the information required by subsection (3) of this section and the total number of duplicates of the statement or document notarized.
      (b) If a notary public performs notarial acts involving different statements or documents for the same individual on the same date, the notary public may, in lieu of recording individually in the journal the information required by subsection (3) of this section for each statement or document, record a single entry in the journal for all notarial acts involving the statements or documents. The entry shall set forth the number of statements or documents and the information required by subsection (3)(c) to (g) of this section and for each statement or document the information required by subsection (3)(a) and (b) of this section. If there are duplicate originals of any statement or document, the entry shall set forth the total number of duplicates of the statement or document notarized.
      (c) If a notary public performs notarial acts involving more than one statement, signature or document for the same individual but not on the same date, the notary public may, in lieu of recording individually in the journal the information required by subsection (3)(c) to (e) of this section for each notarial act performed for that individual, record a reference to a prior entry in the notarial journal for that person. The reference shall identify the page and line numbers of the prior entry. The prior entry shall set forth the information required by subsection (3)(c) to (e) of this section.
      (5) If a notary public’s journal is lost or stolen, the notary public shall notify promptly the Secretary of State on discovering that the journal is lost or stolen.
      (6) On expiration of, resignation from, or suspension of, a notary public’s commission, the notary public shall retain the notary public’s journal in accordance with subsection (1) of this section.
      (7) On revocation of a notary public’s commission, the notary public shall transmit the journal to the Secretary of State not later than 30 days after the date of revocation.
      (8) On the death or adjudication of incompetency of a current or former notary public, the notary public’s personal representative, guardian, conservator or trustee or any other person knowingly in possession of the notary public’s journal shall transmit the journal to the Secretary of State.
      (9) A journal in the possession of a notary public who is not a public official or public employee is exempt from disclosure under ORS 192.410 to 192.505. A journal in the possession of the Secretary of State, or in the possession of a notary public who is a public official or public employee, is not exempt from disclosure under ORS 192.410 to 192.505 unless the secretary or other custodian determines that the public interest in disclosure is outweighed by the interests of the parties to a notarial act in keeping the journal record of the notarial act confidential. A determination by the secretary or other custodian under this subsection is subject to review under ORS 192.410 to 192.505.
      (10) A notary public who is an employee may enter into an agreement with the employer under which the journal or journals of the notary public are retained by the employer upon termination of employment.
      (11) A notary public may, but is not required to, record in a journal any information about the following notarial acts performed by, or documents notarized by, the notary public:
      (a) Recording a protest of commercial paper required under ORS 194.380;
      (b) Administering an oath or affirmation;
      (c) Certifying or attesting a copy of a document;
      (d) Taking an affidavit;
      (e) Verifying a billing statement for media advertising; and
      (f) Taking a verification upon oath or affirmation. [2013 c.219 §18]

