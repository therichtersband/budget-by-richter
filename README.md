# Budget by Richter

A budget app for your iPhone Home Screen. Six setup questions on first open (pay, rent, bills, balances, savings goal, spending), then one screen tells you what's safe to spend until payday.

Everything people enter stays on their own phone. No account, no server, no bank login.

Live: https://budget.therichtersband.com/

## Share it

Send the link. The person opens it in **Safari**, taps **Share**, then **Add to Home Screen**, then opens it from the icon and answers the questions.

## Files

| File | What it does |
|:|:|
| `index.html` | The whole app: setup questions, layout, styles and logic |
| `manifest.webmanifest` | Name and icon for the Home Screen |
| `sw.js` | Offline support |
| `icons/` | App icons |
| `CNAME` | The web address GitHub Pages serves it at |

## Making changes

Edit `index.html`, bump `VERSION` in `sw.js` (`richter-v2`, and so on), then push to `main`. GitHub Pages updates in a minute or two. People's data isn't in the code, so updates never erase it.
