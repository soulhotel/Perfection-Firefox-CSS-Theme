## ------------------ v1.6 (finale) ------------------

#### Ive created a new theme [ FF CSS ULTIMA ] `will upload soon.`

- With the creation of this theme i learned a lot,
- the Perfection Theme despite the name, was never that perfect,
- There were plenty of small annoyances when using it, plenty that could be fixed
- Well, now its fixed. This is the last update.
- Enjoy

![perfection 1](https://github.com/soulhotel/Perfection-Firefox-CSS-Theme/assets/155501797/0a8b7f9e-10a0-4739-abf2-93773bde1cfe)
![perfection 2](https://github.com/soulhotel/Perfection-Firefox-CSS-Theme/assets/155501797/4eb7f32b-9efc-4dd6-ac26-d787acb01e86)
![perfection 3](https://github.com/soulhotel/Perfection-Firefox-CSS-Theme/assets/155501797/f67c8412-e642-4af4-9f97-efc9a0e5d8e6)
![perfection 4](https://github.com/soulhotel/Perfection-Firefox-CSS-Theme/assets/155501797/77739115-843c-458b-962a-5b7cfc529bf8)
![perfection 5](https://github.com/soulhotel/Perfection-Firefox-CSS-Theme/assets/155501797/9bf462a1-0f56-4bd9-94fd-9d80771e6e30)
![perfection 6](https://github.com/soulhotel/Perfection-Firefox-CSS-Theme/assets/155501797/08f58bb2-e028-48eb-9f60-a9560d0ae6cb)

### NEW 
##### Recommended to delete old theme, and redownload.

- userchrome.css
- @import url(navbar/bookmarksbar.css);
- @import url(navbar/navbar-buttons.css);
- @import url(navbar/return-titlebar-buttons.css);
- @import url(themes/browser-rounded.css);
- @import url(CSS/smw.css);
- [ CSS/minmaxclose.css ] - REMOVED
- [ CSS/urlbar.css ] - REMOVED
- [ menu buttons on side ] - REMOVED
- 
---

---

---

# ------------------ v1.5 ------------------

#### -------------- CSS/Downsizewindow.css

- Ive modified the first section, previously I set some buttons as display none.
- It would cause some other buttons on the nav bar to remove themselves.
- this is due to firefox's weird button order, and spacing on the nav bar.
- fixed. `{ order: -2 !important;padding: 0 !important;margin: 0 !important;padding-inline: 0 !important;}`

#### ------------------ CSS/findbar.css

- Thin border color changed from default to black.

#### ----------------- CSS/Navigation-Sidebar.css

- File name changed to `menu-sidebar.css`
- If you want to remove this feature you can swap it out by changing this in userChrome.
  - In userChrome: -> `@import url(CSS/menu-sidebar.css);`
  - Becomes: -> `@import url(CSS/menu-button.css);`
  - This will return all extensions menu and sidebar button to nav bar.
  - While moving menu button to the sidebar header logo.
- Modified the buttons order attributes.

#### ------------------ WEBSITECSS/NewTab.css

- Background change

#### -------------- Images

![Screenshot_4](https://github.com/soulhotel/Perfection-Firefox-CSS-Theme/assets/155501797/a702ec23-2de3-4714-96a4-47c48f9737d9)
![sddb](https://github.com/soulhotel/Perfection-Firefox-CSS-Theme/assets/155501797/826f216f-e65f-46ca-91e8-f10dd2e81aa5)
![Screenshot_6](https://github.com/soulhotel/Perfection-Firefox-CSS-Theme/assets/155501797/096b905a-f9fc-4756-a0fe-d482e2a1fbe8)

# --------------------- v1.4 ---------------------

- Menu button moved to the sidebar logo.
- Bookmark Folder icons redone.

#### ------------------------- CSS/Perfectiontheme.css

- Fixed another dropdown menu showing up with white on white, black on black text
