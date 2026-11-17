<p align="center">
  <img src="media/logo.png" alt="Sorted logo" width="72" />
</p>

<h1 align="center">Sorted Mobile</h1>

<p align="center"><b>Keep your place. Pick it up later.</b><br/>
The Android companion to Sorted: save links as workspaces, get reminded when to come back, and plan phone time with intention.</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.sorted.mobile">Google Play</a> ·
  <a href="https://sorted-tab.in">Website</a> ·
  <a href="https://github.com/AaKaShhhhhhhhh/sorted-showcase">Sorted (browser)</a> ·
  <a href="https://github.com/AaKaShhhhhhhhh/sorted-scan-showcase">Sorted Scan</a>
</p>

<p align="center">
  <img src="media/banner.png" alt="Sorted Mobile — keep your place, pick it up later" width="100%" />
</p>

> **Production code is private.** This repository is a public product showcase with screenshots, a launch video and an overview. It contains no source code.

---

## The idea

Phones are where good intentions go to scroll. You find a link you mean to read, open an app "for a minute," and the plan is gone. Sorted Mobile gives those intentions a place to live and a time to come back.

## What it does

- **Workspaces in your pocket.** The same workspaces you save in the Sorted browser extension, synced to your phone.
- **Save from anywhere.** Share a link from any app straight into a workspace.
- **Reminders that bring things back.** Pick a time for a workspace or a single link, and Sorted brings it forward then.
- **Sessions for phone time.** Plan a time window with the apps, links, or notes you mean to use. A gentle nudge opens and closes the session.
- **Home-screen widgets.** Today's sessions, the next session, a session calendar, workspace shortcuts, upcoming reminders, and quick actions.
- **Activity and sharing.** See recent changes and workspaces shared with you.
- **Calm by design.** System, light, or dark appearance and a Reduce motion setting.
- **Private by default.** Sorted never tracks which apps you use. It plans the attention you choose to give.

---

## Launch video

<p align="center">
  <a href="media/video/sorted-mobile-launch.mp4"><img src="media/video/launch-preview.gif" alt="Sorted Mobile launch video preview" width="280" /></a><br/>
  <b>Launch film</b> (30s) — <a href="media/video/sorted-mobile-launch.mp4">watch the full video</a>
</p>

---

## Screenshots

<table>
  <tr>
    <td><img src="media/screens/01-home-dark.png" alt="Home with workspaces, dark theme" /></td>
    <td><img src="media/screens/02-todays-sessions.png" alt="Today's sessions" /></td>
    <td><img src="media/screens/03-plan-a-task.png" alt="Planning a session" /></td>
    <td><img src="media/screens/04-task-details.png" alt="Session details and destinations" /></td>
    <td><img src="media/screens/05-home-light.png" alt="Home in light theme" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Workspaces</sub></td>
    <td align="center"><sub>Today's sessions</sub></td>
    <td align="center"><sub>Plan a session</sub></td>
    <td align="center"><sub>Session destinations</sub></td>
    <td align="center"><sub>Light theme</sub></td>
  </tr>
</table>

---

## Tech stack

| Area | Technologies |
|---|---|
| App | Flutter, Dart |
| State | Provider |
| Accounts and sync | Firebase Authentication, Google Sign-In, Cloud Firestore |
| Notifications | Firebase Cloud Messaging, local scheduled notifications |
| Security | Firebase App Check, secure on-device storage |
| Android | Home-screen widgets, share-to-app intents, deep links |

## The Sorted family

| Product | What it is |
|---|---|
| [**Sorted**](https://github.com/AaKaShhhhhhhhh/sorted-showcase) | Browser extension + web dashboard for tab workspaces |
| **Sorted Mobile** (this page) | Android companion: saved links, reminders, and planned phone time |
| [**Sorted Scan**](https://github.com/AaKaShhhhhhhhh/sorted-scan-showcase) | Android document scanner and PDF editor on the same account |

## My role

Co-founder of Sorted and lead developer of Sorted Mobile. I built nearly all of the app, including the home-screen widgets, reminders and sessions, and account sync with the Sorted website.

---

<p align="center"><sub>© Sorted. Screenshots and videos are shared for portfolio purposes. All rights reserved.</sub></p>
