### Komunitas — A community fund where the vote is the disbursement

The vote does not produce a recommendation. It produces a payment.

Members contribute into a shared fund, then propose and vote on where it goes. The threshold is enforced in Rust — `2 * yes > member_count` — and a proposal that clears it can be disbursed by anyone, not just an admin.

|  |  |
|---|---|
| Live | [komunitas-rho.vercel.app](https://komunitas-rho.vercel.app) |
| Code | [luong0928472-maker/Komunitas](https://github.com/luong0928472-maker/Komunitas) |
| Stack | Soroban (Rust) · Next.js · TypeScript |
| Contract | [`CDNEHSQ5PW…`](https://stellar.expert/explorer/public/contract/CDNEHSQ5PWYC6AXNA4PIEAXCEUNUSVDAOKIVEBEHTRY2SEUJANSMWFVR) |

Keeping the admin out of the release path was the whole point. If a treasurer can veto a passed vote, it was never governance.
