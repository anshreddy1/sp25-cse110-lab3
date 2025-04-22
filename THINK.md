# Browser Support Risks for :has() and Nested Selectors

According to caniuse.com, the `:has()` relational selector and nested selector syntax are not supported in Safari versions prior to 15.4, and many legacy mobile/enterprise browsers lack support as well. Using these selectors without fallbacks can break layouts or interactive styles for users on older devices. We therefore use them only for non‑critical cosmetic enhancements, ensuring core functionality remains intact for all users.

