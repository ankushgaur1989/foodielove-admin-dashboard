# Foodie Love — Admin Dashboard (v2, isolated build)

This is a **completely separate project** from the main Foodie Love website.

- It has its own folder, its own GitHub repository, and its own Netlify site.
- It connects to the **same live Firebase database** as the main site (read-only for orders/data), so it always sees real, current information.
- It **cannot** affect the main website in any way — different files, different deploy, different everything.

## How to use

1. Deploy this folder to its own Netlify site (see setup steps provided separately).
2. Log in with the same owner email/password used on the main admin panel.
3. View live order data.

## Safe to experiment

Because this is fully isolated, it's safe to add new features, break things while testing, or redesign it entirely — none of that risk touches the real, live customer-facing website.
