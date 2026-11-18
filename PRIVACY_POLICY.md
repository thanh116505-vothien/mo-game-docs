# Privacy Policy for Mò Game-.-

**Effective Date:** November 18, 2026  
**Developer:** VoThien (thanh116505-vothien)  
**Application Name:** Mò Game-.- (Tàng Kinh Các)

---

## 1. Introduction
This Privacy Policy outlines how the Discord bot **Mò Game-.-** ("the Bot") handles user data, permissions, and server interactions. By inviting or using the Bot in any Discord guild or channel, you agree to the practices described in this document.

## 2. Information We Process
To provide game search, patch discovery, and forum indexing, the Bot processes only the minimal necessary data:

- **Search Queries:** When a user triggers the `/timgame` command and enters keywords via the modal input, the query is processed entirely in-memory to find matching game translation patches. Search results are returned as ephemeral messages visible exclusively to the requesting user.
- **Forum Thread Metadata:** The Bot indexes thread titles, thread IDs, jump URLs, and channel names from Discord Forum channels where it has been explicitly granted `View Channel` and `Read Message History` permissions. This metadata is stored in temporary runtime memory (RAM) to deliver instant search and acronym matching.
- **Channel Categorization:** The Bot inspects channel names and parent category names solely to determine VIP/standard release tiers (e.g., distinguishing channels marked with `👑` or `MEMBER VIP`) so users are aware of access requirements before clicking links.
- **Unresolved Query Logs (Optional):** If an administrative log channel is specified by server managers, the Bot sends notifications of queries with no matches to assist admins in adding missing aliases. No user identity or sensitive information is included in these logs.

## 3. Data We Do NOT Collect
- We **do not** collect, store, read, or monitor regular user chat messages, direct messages (DMs), or voice channel communications.
- We **do not** collect personal identification information (PII), email addresses, IP addresses, or financial data.
- We **do not** maintain persistent user tracking profiles or behavioral analytics.

## 4. Data Storage and Security
- All indexed game titles and aliases are kept strictly in runtime memory on our private VPS server.
- No user personal data is sold, traded, transferred, or shared with third parties or external advertising networks.

## 5. Data Retention and Removal
- Because no personal user data is stored in permanent databases, removing the Bot from your Discord server immediately terminates all forum thread cache indexing for that server.
- Server administrators may request immediate cache flushes or report concerns by reaching out directly to the developer.

## 6. Contact Information
If you have any questions, inquiries, or feedback regarding this Privacy Policy, please contact:
- **Developer:** VoThien
- **Discord:** VoThien
- **GitHub:** [https://github.com/thanh116505-vothien](https://github.com/thanh116505-vothien)
