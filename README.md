# NFT Event Ticketing Platform
This is a Next.js application built to modernize event ticketing through the use of NFTs and blockchain verification. Bootstrapped with create-next-app, this project enables event organizers to mint NFT-based tickets and attendees to receive, verify, and use them securely.

🔧 Current Functionality
The platform currently supports:

Multi-ticket minting, allowing organizers to issue multiple NFTs per event.

Automatic NFT delivery when users sign up for events—tickets are sent to their wallet.

QR-based verification at check-in: each NFT generates a signed payload, which is encoded into a QR code. The payload is then verified using a known public key to ensure ticket authenticity.

Post-event certification: After an event ends, organizers can mint and send certificates of participation as NFTs.

These features ensure secure ticket distribution and validation while offering immutable proof of participation.

Technical Highlights-
Cryptographic Signatures: Tickets are verified using a signed payload and a QR code. The check-in process decodes the QR and validates the signature with a public key.

Metadata Verification: Ticket check-ins verify metadata integrity and the creator's address to prevent forgery.

 Planned Enhancements
Several improvements and new features are planned to expand the platform’s capabilities:

Resell Restrictions: Option to freeze NFTs to prevent reselling when creating an event (not yet implemented).

Reselling Marketplace: A zone where users can list and buy secondary-market tickets (not yet implemented).

Map Integration: Ability to add physical locations using maps in the event creation flow.

Free Ticket Support: Users will be able to issue free tickets from the creation interface.

Organizer Dashboard (/host): A new tab that lists all events created by the user.

User Calendar (/calendars): This page will display all events for which the user has tickets or subscriptions.

Improved Event Listing: The current /events design is slated for a revamp to improve usability and aesthetics.
