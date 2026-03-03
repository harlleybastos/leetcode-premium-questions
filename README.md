# LeetCode Premium Questions — Company Wise

A curated collection of **LeetCode premium questions** organized by company and time period. This dataset covers **200+ companies** across **537 CSV files**, making it easy to focus your preparation on the questions most frequently asked by your target employer.

## 📂 Structure

Each CSV file follows the naming convention:

```
{company}_{period}.csv
```

### Time Periods

| Period | Description |
|--------|-------------|
| `6months` | Questions asked in the last 6 months |
| `1year` | Questions asked in the last year |
| `2year` | Questions asked in the last 2 years |
| `alltime` | All questions ever reported |

### CSV Columns

| Column | Description |
|--------|-------------|
| `ID` | LeetCode problem number |
| `Title` | Problem title |
| `Acceptance` | Acceptance rate (%) |
| `Difficulty` | Easy, Medium, or Hard |
| `Frequency` | How frequently the question is asked (higher = more frequent) |
| `Leetcode Question Link` | Direct link to the problem |

## 🏢 Companies

<details>
<summary>Click to expand full company list (200+ companies)</summary>

Accolite · Adobe · Aetion · Affinity · Affirm · Airbnb · Airtel · Akamai · Akuna Capital · Alation · Alibaba · Amazon · American Express · AppDynamics · Apple · Arista Networks · Asana · Atlassian · Audible · Baidu · Barclays · BlackRock · Blizzard · Bloomberg · Bloomreach · Booking.com · Box · ByteDance · C3.ai · Capital One · Cisco · Citadel · Citrix · Cloudera · Clutter · CodeNation · Cohesity · Coupang · Coursera · Cruise Automation · Databricks · Dataminr · Delivery Hero · Dell · D.E. Shaw · Deutsche Bank · DiDi · DocuSign · DoorDash · Drawbridge · Dropbox · Druva · eBay · Electronic Arts · EMC · Epic Systems · Evernote · Expedia · F5 Networks · Facebook · FactSet · Fallible · Fidessa · Flexport · Flipkart · ForUsAll · Garena · GE Digital · Gilt Groupe · GoDaddy · Goldman Sachs · Google · Grab · Groupon · GSN Games · HBO · Helix · Honey · Hotstar · Houzz · HRT · Huawei · Hulu · IBM · IIT Bombay · Indeed · Infosys · InMobi · Intel · Intuit · IXL · Jane Street · Jingchi · JPMorgan · Jump Trading · Kakao · Karat · Leap Motion · LimeBike · LinkedIn · LiveRamp · Lyft · MachineZone · MAQ Software · MathWorks · McKinsey · Media.net · Meituan · Microsoft · MicroStrategy · Morgan Stanley · National Instruments · NetEase · Netflix · NetSuite · Nutanix · NVIDIA · Opendoor · Oracle · Palantir · PayPal · Paytm · PhonePe · Pinterest · Pocket Gems · Point72 · Pony.ai · Poshmark · Postmates · Poynt · Pramp · Pure Storage · Qualcomm · Qualtrics · Quantcast · Quip · Quora · Rackspace · Radius · Reddit · Redfin · Riot Games · Robinhood · Roblox · Rubrik · Salesforce · Samsung · SAP · Sapient · ServiceNow · Snapchat · Snapdeal · Splunk · Spotify · Square · Sumo Logic · Symantec · Tableau · TandemG · Tencent · Tesla · Thumbtack · Traveloka · TripAdvisor · Triplebyte · Turvo · Twilio · Twitch · Twitter · Two Sigma · Uber · UiPath · United Health Group · Valve · Virtu · Visa · VMware · Walmart · Wayfair · Wish · Works Applications · Yahoo

</details>

## 🚀 Quick Start

**Find questions for a specific company:**

```bash
# View Amazon questions from the last year, sorted by frequency
sort -t',' -k5 -rn amazon_1year.csv | head -20
```

**Search for a specific problem across companies:**

```bash
grep -l "Two Sum" *.csv
```

**List all companies that have 6-month data:**

```bash
ls *_6months.csv | sed 's/_6months.csv//'
```

## 📊 Highlights

- **537** CSV files covering **200+** companies
- Top companies by question count (last year): Amazon (605), Google (534), Facebook (428), Microsoft (356), Apple (288)
- Time-bucketed data to focus on the most recent and relevant questions
- Direct LeetCode links for every problem

## 📝 How to Use

1. **Identify your target company** — pick the CSV that matches your interview timeline
2. **Sort by frequency** — focus on the most commonly asked questions first
3. **Filter by difficulty** — start with Easy/Medium, then tackle Hard problems
4. **Cross-reference** — check if a question appears across multiple companies to find universally popular problems

## 📄 License

This repository is intended for personal educational use and interview preparation.
