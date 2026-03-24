# 07 — SOS

[← Back to manual](../README.md)

---

> **If you are in immediate danger, call your local emergency number (911, 999, 112, or equivalent) first. Obserc SOS alerts your trusted circle — it does not contact emergency services.**

---

## What SOS Beacon is

SOS Beacon is an urgent alert that notifies every member of your active circle that you need help. When triggered, it sends your live location to your circle immediately and keeps updating it until the SOS is resolved.

SOS is designed to work with minimal interaction — one tap, a short countdown, and your people know where you are.

---

## Standard SOS vs Critical SOS

Obserc has two SOS states:

| | Standard SOS | Critical SOS |
|-|-------------|--------------|
| **When to use** | You feel unsafe or need help but are not in immediate physical danger | You are in immediate danger |
| **Alert level** | Urgent notification to your circle | High-priority alert — louder, more persistent |
| **Live location** | Yes | Yes — continuous updates |
| **Circle Feed** | Pinned at top | Pinned at top with Critical indicator |

Use **Standard SOS** when something feels wrong and you want your circle alerted immediately.

Use **Critical SOS** when you are in serious danger and need maximum urgency.

`[SCREENSHOT: docs/screenshots/sos/sos-standard.png]`

`[SCREENSHOT: docs/screenshots/sos/sos-critical.png]`

---

## How to trigger an SOS

### From the Status tab

1. Tap **SOS Beacon** on the Status tab
2. A countdown appears (a few seconds)
3. If you do not cancel, the SOS is sent

### From Night Out

Tap **SOS** in the Night Out dashboard. See [Night Out →](06-night-out.md).

`[SCREENSHOT: docs/screenshots/sos/sos-night-out.png]`

### From Drive

Tap **SOS** in the Drive screen. See [Drive →](08-drive.md).

`[SCREENSHOT: docs/screenshots/sos/sos-drive.png]`

---

## The countdown window

After tapping SOS, a short countdown gives you a moment to cancel if you triggered it accidentally. Once the countdown ends, the SOS is sent and your circle is notified.

Do not rely on the countdown in a genuine emergency — the SOS sends quickly.

---

## What happens after an SOS is sent

1. Every member of your active circle receives an urgent push notification
2. Your live location appears on their Circle map
3. An SOS event is pinned at the top of the Circle Feed
4. Your location continues updating in real time until the SOS is resolved

`[SCREENSHOT: docs/screenshots/sos/sos-sent.png]`

---

## What your circle sees

Circle members see:

- A high-priority notification with your name
- Your current location on the Circle map
- An active SOS item in the Circle Feed with your location and a timestamp
- An option to acknowledge the SOS

Members can tap the SOS item in the feed to open your live location and contact you directly.

---

## Cancelling an SOS

If you triggered an SOS by mistake or the situation is resolved:

1. Open Obserc
2. Tap **Cancel SOS** on the active SOS banner
3. Confirm cancellation

Your circle members will see that the SOS has been resolved. The event remains in the Circle Feed as a resolved item.

---

## Night Out SOS

If you trigger SOS during a Night Out session, your alert goes to both your active circle and your Night Out squad and wingman. The Night Out dashboard shows the active SOS state.

---

## Drive SOS

If you trigger SOS during an active Drive session, your SOS includes your current driving location and is sent to your active circle. The Drive screen shows the active SOS state.

---

## Tips for using SOS effectively

- **Set up your circle before you need it.** An SOS sent to an empty circle alerts nobody. Make sure you have at least one active circle member.
- **Keep location access set to Always Allow.** If Obserc cannot access your location, your SOS will still send — but without a precise location attached.
- **Do not hesitate.** SOS is reversible. It is always better to send and cancel than to not send at all.
- **Call emergency services too.** Obserc alerts your trusted people — it is not a substitute for calling 999 or 911.

---

*Next: [Drive →](08-drive.md)*
