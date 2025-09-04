# Ruth
Overview

This is a brief and unique Clarity smart contract for managing Requests for Proposal (RFPs) in Web3.
It ensures fairness, transparency, and trust using a commit–reveal mechanism and immutable on-chain winner recording.

✨ Features

🔒 Commit–reveal bidding for fair play

⏳ Deadlines enforced by block height

🏆 Immutable winner finalization

🪶 Lightweight (<35 lines) & auditable

🚀 Flow

create-rfp → Owner defines commit/reveal deadlines

commit → Vendors submit hash(proposal + salt)

reveal → Vendors reveal proposal with salt

finalize → Owner records winner on-chain

📜 License

MIT – Free to use, adapt, and extend.
