# Diya Night

A single-page event invitation for a terrace supper. It has a hero with a row of flickering diyas, a days-to-go counter, event details, a timed schedule for the evening, and a reply section with a copy-number button.

The page is one self-contained file, `index.html`. It uses Google Fonts for type and has no build step or dependencies. It follows the visitor's light or dark setting.

## View it

Open `index.html` in any browser.

To host it, turn on GitHub Pages: go to Settings, then Pages, choose the `main` branch and the root folder, and save.

## Make it your own

All the content is plain text inside `index.html`. Search for these and replace them:

- **Event name:** "Diya Night" in the `<title>` and the `<h1>`
- **Hosts:** "Meera and Arjun" in the footer
- **Date and time:** "Saturday, 7 November 2026" and "7:00 PM onwards" in the hero. Also update the date in the script at the bottom (`new Date(2026, 10, 7, ...)`, where the month counts from 0), and the fallback text "In 23 days".
- **Venue:** the address under "Where"
- **Schedule:** the list under "How the evening goes"
- **Reply details:** the phone number in the "Will you come?" section, and the reply-by date
- **Colors:** the tokens at the top of the `<style>` block, with separate sets for light and dark

## Notes

The page has no form. Guests reply by calling or messaging the number shown.
