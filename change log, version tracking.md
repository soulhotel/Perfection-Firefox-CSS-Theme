# --------------------- Changes for v1.5 ---------------------

#### ------------------------- CSS/Downsizewindow.css

- Ive modified the first section, previously I set some buttons as display none.
- It would cause some other buttons on the nav bar to remove themselves.
- this is due to firefox's weird button order, and spacing on the nav bar.
- fixed. `{ order: -2 !important;padding: 0 !important;margin: 0 !important;padding-inline: 0 !important;}`

#### ------------------------- CSS/findbar.css

- Thin border color changed from default to black.

#### ------------------------- CSS/Navigation-Sidebar.css

- File name changed to `menu-sidebar.css`
- If you want to remove this feature you can swap it out by changing this in userChrome.
  - In userChrome: -> `@import url(CSS/menu-sidebar.css);`
  - Becomes: -> `@import url(CSS/menu-button.css);`
  - This will return all extensions menu and sidebar button to nav bar.
  - While moving menu button to the sidebar header logo.
- Modified the buttons order attributes.

#### ------------------------- WEBSITECSS/NewTab.css

- Background change
