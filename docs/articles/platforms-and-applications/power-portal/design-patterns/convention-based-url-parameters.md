# Convention-based URL parameters

- Avoid URL parameters if possible, but if they are necessary... Consider cookies/local storage if the need becomes excessive.
- Make them longer if it assists in readability/hack-ability of a URL.
- Make them shorter if they are on every page/never required for a user/obvious even if short
    - c.f. "q=" in Google Search is so ubiquitous to the functionality that having 'q' over 'query' is acceptable
- Keep GUID reference names as standardised as possible, e.g. instead of "?mother-id=" and "?father-id=", preferable is "?parent-id" or "?family-member-id=" or simply "?id=" if possible as it allows convention-based web templates to consume them.
- They only need to be more specific if multiples ever appear at the same time.