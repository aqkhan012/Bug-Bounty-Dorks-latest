# Bug Bounty Dorks

A curated collection of Google dorks to help beginners find active bug bounty and responsible disclosure programs. These dorks are designed to identify programs offering monetary rewards, swag, or Hall of Fame recognition, focusing on beginner-friendly opportunities.

## Purpose

This repository provides effective Google dorks to discover bug bounty programs, particularly those suitable for beginners. The dorks are optimized to reduce irrelevant results and target programs with clear reward structures, often hosted on platforms like Bugcrowd and HackerOne.

## Google Dorks

Below are the top recommended dorks for finding beginner-friendly bug bounty programs:

1. **`inurl:"bug bounty" intext:"reward"`**
   - Finds pages explicitly mentioning "bug bounty" and "reward," targeting active programs with incentives.
2. **`inurl:/responsible-disclosure/ intext:"bounty" | intext:"reward"`**
   - Targets responsible disclosure pages offering bounties or rewards, broadening the search with the `|` operator.
3. **`responsible disclosure hall of fame`**
   - Identifies programs with Hall of Fame recognition, ideal for beginners seeking practice and visibility.
4. **`"powered by bugcrowd" -site:bugcrowd.com | "powered by hackerone" -site:hackerone.com`**
   - Locates programs on Bugcrowd or HackerOne, excluding platform domains for company-specific results.
5. **`inurl:/security intext:"responsible disclosure" intext:"bounty"`**
   - Finds security pages with responsible disclosure programs offering bounties, filtering out generic content.

## Usage Instructions

1. **Search**: Copy and paste each dork into Google Search.
2. **Filter Results**:
   - Check the first 2–3 pages for company websites (e.g., `company.com/security`) or platform-hosted programs.
   - Verify the program is active, public, and offers rewards (monetary, swag, or recognition).
   - Review the scope (e.g., web vulnerabilities like XSS, CSRF) and submission guidelines.
3. **Prioritize**:
   - Focus on programs with broad scopes or low-severity vulnerabilities for easier findings.
   - Look for Bugcrowd/HackerOne programs, as they provide clear guidelines and beginner support.
4. **Cross-Check**: Use `inurl:/.well-known/security ext:txt` to find `security.txt` files, but verify if they link to active bounty programs.

## Tips for Beginners

- **Learn Common Vulnerabilities**: Start with XSS, CSRF, or IDOR. Resources like Bugcrowd University are great for learning.
- **Follow Guidelines**: Adhere to program rules to avoid disqualification.
- **Start Small**: Target programs offering swag or Hall of Fame for practice before chasing high bounties.
- **Use Platforms**: Sign up for Bugcrowd or HackerOne to access structured programs.
- **Stay Ethical**: Only test within the program’s scope and avoid unauthorized access.

## Example Programs

- **Tumblr**: Offers swag and up to $5,000 for vulnerabilities.
- **UXCam**: Bugcrowd-hosted, with Hall of Fame and rewards.
- **Bolt**: Public Bugcrowd program, beginner-accessible.
- **OffSec**: Pays $200–$1,000 for issues like XSS or file disclosure.

## Contribution

Feel free to submit pull requests with additional dorks or improvements! Please ensure dorks are relevant, tested, and beginner-friendly.

## Disclaimer

Use these dorks responsibly and follow ethical hacking practices. Always respect the scope and rules of bug bounty programs.