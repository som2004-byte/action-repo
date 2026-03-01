# action-repo

Repository used for **GitHub actions** (Push, Pull Request, Merge). Webhooks from this repo are sent to the **webhook-repo** receiver.

---

## Purpose

- Push, open pull requests, and merge in **this repo**.
- GitHub sends webhook events to the URL configured in **Settings → Webhooks**.
- The webhook receiver (webhook-repo) stores events and displays them in its UI.

---

## Webhook configuration

1. In this repo: **Settings → Webhooks → Add webhook**.
2. **Payload URL:** Your webhook-repo endpoint, ` https://isidioid-charlotte-trilocular.ngrok-free.dev/webhook/receiver`.
3. **Content type:** `application/json`.
4. **Events:** Pushes, Pull requests.
5. Save; use “Redeliver” to test. A 200 response means the receiver is working.

---

## Submission

- **This repo (action-repo):** [GitHub – action-repo](https://github.com/som2004-byte/action-repo)
- **Webhook receiver:** [GitHub – webhook-repo](https://github.com/som2004-byte/webhook-repo)

Provided both links as per the assessment instructions.

