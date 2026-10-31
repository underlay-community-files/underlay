# Underlay privacy policy

_Last updated: October 31, 2026_

Underlay is a free browser extension that shows live backgrounds behind charts on tradingview.com. This page explains what data it handles.

## In short

- No account, no email, no password, no ads, no tracking, no analytics.
- Your settings and your own files stay on your computer.
- Only what **you choose to share** on the Community page leaves your computer, and it becomes public.

## What stays on your computer

Underlay stores these only in your browser, inside the extension:

- your settings (current backdrop, look controls, favourites, pets, auto-rotate);
- the **nickname** you pick;
- videos and pictures you add under **My media**;
- private delete keys for designs you shared, so you can delete them later.

Removing the extension deletes all of this.

## What leaves your computer: the Community page

The Community page talks to the Underlay Community server (`underlay-community.underlay.workers.dev`, run on Cloudflare). This happens when you open the Home or Community page, and when you share, add or report a design.

**When you browse or add designs**, the server sends the list of shared designs and their files. Nothing about you is saved.

**When you share a design**, these are sent and made **public**:
- the video or picture you chose;
- its title and a small preview image;
- your nickname;
- its size, frame rate and length.

Shared files are stored as public downloads on GitHub (`github.com/underlay-community-files/underlay-community`).

**To stop abuse**, the server:
- turns your IP address into a one-way code (a salted hash) to count uploads (up to 20 a day) and reports (one per person per design). **Your raw IP address is not stored.** Daily counters are deleted the next day.
- keeps a one-way code of each design's private delete key, so only the person who shared it can delete it.

**Reports.** If three different people report a design, it is hidden and its file is deleted.

## What Underlay does on tradingview.com

On tradingview.com, Underlay makes the chart background transparent, places the backdrop behind it, and can recolour candles to match. It remembers your original chart colours **in your browser only** and puts them back when you turn Underlay off. It does not read your account, orders, watchlists or any other page content, and sends nothing from TradingView anywhere.

## Sharing and selling

Underlay does not sell, rent or share your data, and does not use it for advertising or for anything other than running the extension and the Community page.

## Your choices

- **Don't use Community:** if you never share a design, nothing you add or set leaves your computer.
- **Delete a design you shared:** click **×** on it, from the computer you shared it from.
- **Ask for removal:** to report a legal or copyright problem, or have a design removed, open an issue at github.com/underlay-community-files/underlay/issues.

## Children

Underlay is not directed at children under 13.

## Changes

If this policy changes, the new version will be posted here with a new date.
