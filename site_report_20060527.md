# Site Report: campnawakwa.org (2026-05-27)

## ⚠️ Conflicting or Inaccurate Info  

Summer sessions in both June and July were originally planned, but it has been said there will only be the July session this year.   There are multiple contacts for these dates being out there as the flyer image was posted to 3rd party sites as well as campnawakwa.org site.  

Listing known touch points here

- [ ] Camp flyer on site here - https://www.campnawakwa.org/summer-camp-2026
- [ ] April 7 post on FB - https://www.facebook.com/campnawakwa
- [ ] April 7 post on IG - https://www.instagram.com/outdoor_journeys/
- [ ] ACTIVE - signup page - https://campscui.active.com/orgs/CampNawakwa?newcui=true#/selectSessions/3821636


## 🔴 Dead Link (404)

| URL | Location Found | Issue |
|-----|---------------|-------|
| `/aca-accredidation` | "Why Camp Nawakwa?" page (via ./rentaloverview -> ./whycampnawakwa -> "ACA Learn More" link at bottom of page) | **404 Not Found** — linked as proof of ACA accreditation. Note the URL also has a typo ("accredidation" instead of "accreditation"). |

---

## 🟡 Redirect / Mismatch Issues

These links resolve but silently redirect to a different page than labeled:

| Link Label | URL Used | Redirects To | Problem |
|---|---|---|---|
| **"About Us"** (nav + footer sitemap) | `/aboutus` | `/campnawakwaprograms` | "About Us" redirects to the Programs page — there's no actual About Us page |
| **"Program Offerings"** (footer sitemap) | `/program-offerings-1` | `/forest-kindergarten` | The parent dropdown item lands on Forest Kindergarten, not an overview page |
| **"Gallery"** (footer sitemap) | `/gallery-1` | `/gallery` | Duplicate slug with redirect; minor but slightly inconsistent |
| **"Home"** (footer) | `http://www.outdoorjourneys.org` | `https://www.campnawakwa.org` | The Outdoor Journeys parent org domain redirects to Camp Nawakwa — the separate org site doesn't appear to exist separately anymore |

---

## 🟠 Empty / Placeholder Page

| Page | URL | Issue |
|---|---|---|
| **Day Camp** | `/day-camp` | Page exists but only says "Coming soon!" — no actual content |

---

## ✅ All Other Pages — Working

Every other page in the nav loaded correctly: Camp Nawakwa Programs, Our History, Testimonials, Directions, Forest Kindergarten, Summer Camp 2026, Rental Packages, Rental Overview, Rental Inquiry, Rental FAQ, Gallery, Contact Us, and Why Camp Nawakwa.

---

**Priority fix:** The `/aca-accredidation` 404 is the most impactful issue — it breaks a credibility-building link about ACA accreditation. The slug should likely be `/aca-accreditation` (corrected spelling), or the page needs to be created/restored. Want me to dig deeper into any other aspect of the site?


---

# 📅 Date References Across the Site

Here's every page with a date or time-bound reference, assessed against today's date:

---

### ✅ Current / Future-Looking

**Summer Camp 2026** (`/summer-camp-2026`)
- References "Summer Camp at Camp Nawakwa 2026" — current and appropriate.
- No specific session dates listed (just "2026"), so nothing is technically stale yet.

**Forest Kindergarten** (`/forest-kindergarten`)
- "September–November 2026, $1,200, Wednesdays 10:00 AM–3:00 PM" — **upcoming**, still valid.
- "February–April 2027, $1,600, Wednesdays 10:00 AM–3:00 PM" — **future**, fine.

---

### 🔴 Stale / Past Events Presented as Ongoing

**Camp Nawakwa Programs** (`/campnawakwaprograms`)
- **"Swimming — Offered June through Mid-September"** — no year specified, so this is evergreen. Fine on its own, but worth noting it implies seasonal availability.
- **"Canoeing — Offered May–October"** — same as above, evergreen.

**Camp Programs / Why Camp Nawakwa** (`/why-camp-nawakwa`)
- References the pool as available **"Memorial Day to Labor Day"** — no year, evergreen.
- Mentions "Lower camp... June through September" — evergreen.

**Rental FAQ** (`/rentalfaq`)
- **"Pool is available during summer season only (Memorial Day to Labor Day)"** — evergreen, fine.
- **"Lower camp is predominantly used in the summer months (June through September)"** — evergreen, fine.

---

### 🟠 Potentially Stale — Instagram Feed on Homepage

The **homepage** (`/`) embeds an Instagram feed that is frozen in **April 2020** — "Outdoor Journeys TV" episode posts from April 2020 are displayed prominently as if they are current activity. Today is May 2026, so this feed is **over 6 years out of date** and gives a very poor first impression of an inactive organization.

All tiles in embedded IG secion are dead links on https://www.campnawakwa.org (scroll down)


---

### 🟡 History Page — Minor Staleness

**Our History** (`/ourhistory`)
- Says Outdoor Journeys was formed "in the Fall of 2014" and that it "has only been in existence for just a few years" — that language is now about **12 years stale**. The org has been around for over a decade.
- References "Camp Blue Sky" as a Day Camp program — no mention of whether this still exists.

---

## Date References Summary

| Page | Date Reference | Status |
|---|---|---|
| Summer Camp 2026 | "2026" season | ✅ Current |
| Forest Kindergarten | Sept–Nov 2026 / Feb–Apr 2027 | ✅ Current |
| Camp Programs | "June–September", "May–October" | ✅ Evergreen |
| Rental FAQ | "Memorial Day to Labor Day", seasonal notes | ✅ Evergreen |
| **Homepage** | **Instagram feed frozen at April 2020** | 🔴 **6 years stale** |
| **Our History** | **"only been in existence for a few years"** | 🟡 **12 years stale** |

The most actionable issues are the homepage Instagram feed (very visible, makes the site look abandoned) and the "Our History" copy that still reads like a brand-new organization. Want me to continue and look at any other aspects of the site?




# Site Hosting and Platform Information

## Summary

| Detail | Value |
|---|---|
| **CMS** | Squarespace (not hand-coded) |
| **Squarespace Site ID** | `5451689fe4b0156d29ef05ef` |
| **Hosting** | Squarespace (all-in-one) |
| **CDN** | Squarespace CDN (`squarespace-cdn.com`) |
| **Registrar** | GoDaddy.com |
| **SSL** | Active (HTTPS, issued via Squarespace) |
| **Domain age est.** | ~2014 (based on site ID) |
| **WHOIS privacy** | Enabled (personal info redacted) |

---

## 🌐 CMS / Platform

**Squarespace**

The source code is loaded with unmistakable Squarespace fingerprints:

- All images are served from `images.squarespace-cdn.com` and `static1.squarespace.com`
- The site's content ID in every URL: `5451689fe4b0156d29ef05ef` — this is the Squarespace site ID, present in every asset path
- The canonical URLs, og:image, and meta tags all point to Squarespace CDN infrastructure
- The site was built on Squarespace's older **"Version 6" / "Brine family" template** era (based on the layout structure and the 2014–2015 era site ID)
- It is **not hand-coded** — it's a standard Squarespace drag-and-drop website

---

## 🏠 Hosting

**Squarespace** hosts the site directly. Squarespace is an all-in-one platform — they both provide the CMS and host the content on their own infrastructure (Squarespace CDN). There's no separate web host.

---

## 📋 Registrar & Domain Info

### campnawakwa.org

| Field | Value |
|---|---|
| **Registrar** | GoDaddy.com, LLC (IANA ID: 146) |
| **Registered** | October 10, 2014 |
| **Expires** | October 10, 2026 |
| **Last Updated** | October 11, 2025 |
| **Name Servers** | `ns01.domaincontrol.com` / `ns02.domaincontrol.com` (GoDaddy) |
| **IP Address** | 198.49.23.145 (Squarespace hosting) |
| **WHOIS Privacy** | Enabled — via **Domains By Proxy, LLC** (GoDaddy's privacy service) |
| **Domain Status** | client delete prohibited, client renew prohibited, client transfer prohibited, client update prohibited |

> ⚠️ **Expiry Notice:** Expires **October 10, 2026** — about 4.5 months away. Confirm auto-renew is active.

---

### outdoorjourneys.org (Parent Org Domain)

| Field | Value |
|---|---|
| **Registrar** | GoDaddy.com, LLC (IANA ID: 146) |
| **Registered** | October 10, 2014 |
| **Expires** | October 10, 2026 |
| **Last Updated** | November 24, 2025 |
| **Name Servers** | `ns15.domaincontrol.com` / `ns16.domaincontrol.com` (GoDaddy) |
| **IP Address** | 3.33.251.168 (AWS) |
| **WHOIS Privacy** | Partial — registrant contact info redacted |
| **Domain Status** | client delete prohibited, client renew prohibited, client transfer prohibited, client update prohibited |

---

**Notable observations:**

Both domains were **registered on the same day — October 10, 2014** — and both expire on the same date, **October 10, 2026**, suggesting they were set up together as a package when the organization launched. Both are registered through GoDaddy with the same set of protective status locks. The `outdoorjourneys.org` IP resolves to AWS rather than Squarespace, which is interesting — it may be forwarding/redirecting at the DNS level rather than being a full hosted site, consistent with our earlier finding that visiting it just bounces you to Camp Nawakwa.
