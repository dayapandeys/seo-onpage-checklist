# Technical SEO Checklist

## Crawlability

- [ ] Page can be crawled by search engines
- [ ] No accidental robots.txt blocking
- [ ] No accidental `noindex` directive
- [ ] Important content is accessible without unnecessary interactions
- [ ] Internal links are crawlable
- [ ] No important orphan pages

## Indexability

- [ ] Page is intended to be indexed
- [ ] Canonical points to the correct URL
- [ ] Canonical URL is indexable
- [ ] No conflicting canonical signals
- [ ] No conflicting robots directives
- [ ] URL is included in the appropriate XML sitemap
- [ ] Page is not unintentionally excluded from sitemap

## URL

- [ ] URL is descriptive
- [ ] URL is concise
- [ ] URL structure is logical
- [ ] Lowercase URLs used consistently
- [ ] Unnecessary URL parameters avoided
- [ ] Trailing slash format is consistent
- [ ] HTTPS version is used
- [ ] No unnecessary redirects

## Canonical

- [ ] Self-referencing canonical used where appropriate
- [ ] Canonical uses the preferred HTTPS URL
- [ ] Canonical does not point to an irrelevant page
- [ ] Canonical is not blocked from crawling
- [ ] Canonical matches preferred URL version

## Redirects

- [ ] HTTP redirects to HTTPS
- [ ] Non-preferred hostname redirects to preferred hostname
- [ ] Redirect chains avoided
- [ ] Redirect loops avoided
- [ ] Relevant redirects use 301/308 where appropriate
- [ ] Redirect destination is relevant
- [ ] Broken redirect destinations fixed

## Internal Links

- [ ] Important pages have internal links
- [ ] Internal links use crawlable HTML links
- [ ] Anchor text is descriptive
- [ ] Internal links are contextually relevant
- [ ] Broken internal links are fixed
- [ ] Excessive internal links avoided

## Mobile

- [ ] Page works correctly on mobile
- [ ] Important content is available on mobile
- [ ] Navigation works correctly
- [ ] Buttons and links are usable
- [ ] No important content is hidden unintentionally

## Core Web Vitals

- [ ] LCP reviewed
- [ ] INP reviewed
- [ ] CLS reviewed
- [ ] Page performance tested on mobile
- [ ] Large images optimized
- [ ] Unnecessary JavaScript minimized
- [ ] Render-blocking resources reviewed
- [ ] Layout shifts minimized

## Structured Data

- [ ] Relevant schema type identified
- [ ] Structured data matches visible content
- [ ] Required properties implemented
- [ ] Schema validated
- [ ] No invalid or misleading markup

## Technical QA

- [ ] Page returns HTTP 200
- [ ] No broken resources
- [ ] No mixed-content issues
- [ ] Images load correctly
- [ ] JavaScript does not block important content
- [ ] Page source reviewed where required
- [ ] Google Search Console inspected where relevant
