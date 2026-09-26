# Shopping List by HPS

<img src="./shopping-list-icon.png" alt="Shopping List by HPS icon" width="128" height="128">

Turn materials already added to a ServiceM8 job into a practical shopping list for your next supplies run.

**[Visit the help website](https://ianhorne73.github.io/shopping-list-by-hps/)**

## Release status

**Submitted to the ServiceM8 Add-on Store — Waiting For Review.**

Submitted on 26 September 2026. Support details, privacy policy and demo screenshots are included. Public store availability is subject to ServiceM8 approval.

The account owner has confirmed iPhone presentation and retention of ticks and exclusions after reopening and across devices, including the previously affected job. If the app reports a save or reload error, refresh and verify the result before relying on it.

## Features

- View material descriptions, quantities and catalogue item codes where available.
- Tick collected items and keep them visible with a strikethrough.
- Exclude services or items already on hand, then restore them from the Excluded view.
- Copy outstanding materials into a text shopping list.
- Print the list with its job number and address.
- Automatically hide descriptions containing the whole word “labour” or “labor”.
- Open a separate shopping list for each job.

## Where it works

| Platform | How the list opens |
| --- | --- |
| ServiceM8 Online Dashboard | In a pop-up over the job card |
| ServiceM8 iPhone/iPad app | Through a job action that opens a web page |

Internet access is required. The mobile view is a web page, not a native checklist screen. Clipboard and printing options depend on the device and browser.

## Using the app

After your administrator activates the add-on:

1. Open a job in ServiceM8.
2. Choose **More → Shopping List by HPS**. On iPhone/iPad, use Edit Actions if you need to add it to your job-action favourites.
3. Review the materials and quantities.
4. Tick items as collected, or use **Exclude** for items you do not need to buy.
5. Use **Refresh** to retrieve saved changes from other devices.
6. Choose **Copy list** or **Print** when needed.

No separate app username or password is required.

## Important behaviour

- Quantities come from the job’s material lines; stock on hand is not deducted.
- Zero, negative and invalid quantities are omitted.
- Labour filtering uses description text. Other service lines may need to be excluded manually.
- Changing a material’s description, quantity or catalogue reference resets its shopping status for review.
- Coordinate simultaneous edits to the same job: the latest save can replace concurrent changes.
- Shopping status is stored separately in ServiceM8 add-on storage. The app does not change quotes, invoices, source job materials or inventory levels.

See the [help website](https://ianhorne73.github.io/shopping-list-by-hps/) for troubleshooting and workflow details.

## This repository

This public repository hosts the app’s artwork and help website. It does not contain the add-on’s backend source, credentials, customer records or job data.

| File | Purpose |
| --- | --- |
| [index.html](./index.html) | GitHub Pages help website |
| [shopping-list-icon.png](./shopping-list-icon.png) | Approved app and menu icon |
| [README.md](./README.md) | App overview and repository guide |

### Public links

- Website: https://ianhorne73.github.io/shopping-list-by-hps/
- Direct icon: https://raw.githubusercontent.com/Ianhorne73/shopping-list-by-hps/main/shopping-list-icon.png

## Support and privacy

Operated by **Horne Property Services Pty Ltd**.

Support and privacy: [ian.horne@hireahubby.com.au](mailto:ian.horne@hireahubby.com.au)

[Privacy policy](https://ianhorne73.github.io/shopping-list-by-hps/privacy.html)

The app is free. The submitted store listing has all region options enabled.

Do not post customer details, job addresses, passwords or access tokens in public GitHub issues.

Shopping List by HPS is an independent add-on. It is not developed or supported by ServiceM8.
